# How to display graphs from an (external hosted) extranet

**Cacti version :** 1.2.11

**Cookie domain option changed :** my-domain.net - file : /usr/share/cacti/site/include/config.php

**CSRF token is fixed :** 'sid:af0face4d4b906e1dccb1496b9d3ce2d22ba2365,1584620899' - file : include/vendor/csrf/csrf-magic.php

**Cookie SameSite option changed as 'None':** - file : /etc/apache2/conf-enabled/cacti.conf

## **Cacti server** 

**VM :** cacti.my-domain.net => Public IP Y.Y.Y.Y

**Apache version :** 2.4.25

**PHP version :** 7.0.19-1

## **Extranet server**

**VM :** - extranet.my-domain.net => Public IP Z.Z.Z.Z

**Apache version :** 2.4.10

**PHP version :** 5.6.40-0


## **Browsers working :**

**Internet Explorer** 11.xx

## **Browsers NOT working :**

**Chrome** 80.xx

**Firefox** 74

**Safari** 5.1.7
