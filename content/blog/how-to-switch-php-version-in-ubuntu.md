---
path: How to Switch PHP Version in Ubuntu
date: 2022-10-09T12:36:21.422Z
title: How to Switch PHP Version in Ubuntu
description: How to Switch PHP Version in Ubuntu on apache cli & browser
---
<!--StartFragment-->

How to Switch php version in ubuntu. I have 3 php versions namely, php 5.6, php 7.0 and php 7.1. I will try to switch from php 5.6 to php 7.0 and vice versa. im using ubuntu 16.04



### Apache

**From php5.6 to php7.0.**



sudo a2dismod php5.6

sudo a2enmod php7.0

sudo service apache2 restart







**From php7.0 to php5.6**



sudo a2dismod php7.0

sudo a2enmod php5.6

sudo service apache2 restart





and now try to check http: //localhost/info.php

[![Switch php version in ubuntu](https://2.bp.blogspot.com/-PTxby3uZS2Q/WauOzSV3DcI/AAAAAAAAANg/h4BDYHF8PWovlXl43LJNiohTif78pHKjQCLcBGAs/s320/Screenshot%2Bfrom%2B2017-09-03%2B12-08-30.png "Switch php version in ubuntu")](https://2.bp.blogspot.com/-PTxby3uZS2Q/WauOzSV3DcI/AAAAAAAAANg/h4BDYHF8PWovlXl43LJNiohTif78pHKjQCLcBGAs/s1600/Screenshot%2Bfrom%2B2017-09-03%2B12-08-30.png)



[![Switch php version in ubuntu](https://2.bp.blogspot.com/-0HvChVabwO4/WauOd51cOYI/AAAAAAAAANY/bEe8GA7pj38-HGBKMcGxRgs5afFe--qLwCEwYBhgL/s320/image.jpg "Switch php version in ubuntu")](https://2.bp.blogspot.com/-0HvChVabwO4/WauOd51cOYI/AAAAAAAAANY/bEe8GA7pj38-HGBKMcGxRgs5afFe--qLwCEwYBhgL/s1600/image.jpg)



[![Switch php version in ubuntu](https://3.bp.blogspot.com/-On3W-sQkgxQ/WauOmUB4dsI/AAAAAAAAANc/jXrWrfXiNAgR4vvdM9_0nJI2DdkYS2DVACEwYBhgL/s320/image%2B%25281%2529.jpg "Switch php version in ubuntu")](https://3.bp.blogspot.com/-On3W-sQkgxQ/WauOmUB4dsI/AAAAAAAAANc/jXrWrfXiNAgR4vvdM9_0nJI2DdkYS2DVACEwYBhgL/s1600/image%2B%25281%2529.jpg)





### why the php version on the command line has not changed?

[![Switch php version in ubuntu](https://1.bp.blogspot.com/-L5sKW8kswA4/WauPyPYpjFI/AAAAAAAAANo/B3cwOG7LSnEypndcwdoU33Hie0QmOp5tgCLcBGAs/s320/Screenshot%2Bfrom%2B2017-09-03%2B12-14-31.png "Switch php version in ubuntu")](https://1.bp.blogspot.com/-L5sKW8kswA4/WauPyPYpjFI/AAAAAAAAANo/B3cwOG7LSnEypndcwdoU33Hie0QmOp5tgCLcBGAs/s1600/Screenshot%2Bfrom%2B2017-09-03%2B12-14-31.png)



The way is quite easy, enter to the command line:



sudo update-alternatives --set php /usr/bin/php-version





Example



**PHP 5.6**



sudo update-alternatives --set php /usr/bin/php5.6

and now,

php -v

[![Switch php version in ubuntu](https://1.bp.blogspot.com/-7fSMWWnVyLk/WauQQOl2oWI/AAAAAAAAANs/F5LZmVdfK8MeD_skasriXlFVLonK97hLACLcBGAs/s320/Screenshot%2Bfrom%2B2017-09-03%2B12-14-31.png "Switch php version in ubuntu")](https://1.bp.blogspot.com/-7fSMWWnVyLk/WauQQOl2oWI/AAAAAAAAANs/F5LZmVdfK8MeD_skasriXlFVLonK97hLACLcBGAs/s1600/Screenshot%2Bfrom%2B2017-09-03%2B12-14-31.png)



**PHP 7.0**



sudo update-alternatives --set php /usr/bin/php7.0

and ,

php -v

[![](https://4.bp.blogspot.com/-opTQsBu934A/WauQmniWPXI/AAAAAAAAAN0/cy1q3GTaS6ECNF2LcNhg_dAyOk9_rN7RQCLcBGAs/s320/Screenshot%2Bfrom%2B2017-09-03%2B12-18-04.png)](https://4.bp.blogspot.com/-opTQsBu934A/WauQmniWPXI/AAAAAAAAAN0/cy1q3GTaS6ECNF2LcNhg_dAyOk9_rN7RQCLcBGAs/s1600/Screenshot%2Bfrom%2B2017-09-03%2B12-18-04.png)



<!--EndFragment-->