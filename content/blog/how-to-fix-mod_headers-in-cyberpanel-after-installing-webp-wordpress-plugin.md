---
path: How To fix mod_headers In Cyberpanel after Installing WEBP Wordpress Plugin
date: 2022-10-09T12:57:59.587Z
title: How To fix mod_headers In Cyberpanel after Installing WEBP Wordpress Plugin
description: How To fix mod_headers In Cyberpanel after Installing WEBP Wordpress Plugin
---
<!--StartFragment-->

f you install webp express plugin to convert image jpg or png to webp format, encountered an error "install mod headers" you can fix the error this way Problem:



### Problem

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgWAOpzmXifVse3P2tVscSRhZLcfPurSg8I67RV3sW4B5X_civ0NLl1XYgixzJTan-V_ocIW6ZoSzJFea9_c0CbutKrgwaLwC6hvPwaT5gp68WyfmSQV6YyZXsRnwyxamNF8Eh26tOu1FweII12whtFJlPEstJlyhplwGnpNCkHnvt6xYz7Wl8lUAfB7Q/w683-h220/mod%20headers.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgWAOpzmXifVse3P2tVscSRhZLcfPurSg8I67RV3sW4B5X_civ0NLl1XYgixzJTan-V_ocIW6ZoSzJFea9_c0CbutKrgwaLwC6hvPwaT5gp68WyfmSQV6YyZXsRnwyxamNF8Eh26tOu1FweII12whtFJlPEstJlyhplwGnpNCkHnvt6xYz7Wl8lUAfB7Q/s1717/mod%20headers.jpg)[](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgWAOpzmXifVse3P2tVscSRhZLcfPurSg8I67RV3sW4B5X_civ0NLl1XYgixzJTan-V_ocIW6ZoSzJFea9_c0CbutKrgwaLwC6hvPwaT5gp68WyfmSQV6YyZXsRnwyxamNF8Eh26tOu1FweII12whtFJlPEstJlyhplwGnpNCkHnvt6xYz7Wl8lUAfB7Q/s1717/mod%20headers.jpg)[](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgWAOpzmXifVse3P2tVscSRhZLcfPurSg8I67RV3sW4B5X_civ0NLl1XYgixzJTan-V_ocIW6ZoSzJFea9_c0CbutKrgwaLwC6hvPwaT5gp68WyfmSQV6YyZXsRnwyxamNF8Eh26tOu1FweII12whtFJlPEstJlyhplwGnpNCkHnvt6xYz7Wl8lUAfB7Q/s1717/mod%20headers.jpg)

### Solution

1. Login to cyberpanel
2. List Website
3. Click a manage website
4. Vhost Conf
5. Add script to end of line

context / {

extraHeaders Access-Control-Allow-Origin *

}

6. Save

<!--EndFragment-->