!SLIDE subsection
#Facebook, por dentro. Autenticación, Rest API, Graph API#

!SLIDE smaller
#OAuth 2.0#

###Es un protocolo de autenticación###
###Mediante tokens, permite autenticar a los usuarios.###
    +--------+                                  +---------------+
    |        |--(C)--- Client Credentials ----->| Authorization |
    |        |                                  |     Server    |
    |        |<-(D)------ Access Token ---------|               |
    |        |                                  +---------------+
    | Client |
    |        |                                  +---------------+
    |        |--(E)------ Access Token -------->|    Resource   |
    |        |                                  |     Server    |
    |        |<-(F)---- Protected Resource -----|               |
    +--------+                                  +---------------+

[http://developers.facebook.com/docs/authentication/](http://developers.facebook.com/docs/authentication/)

!SLIDE bullets incremental

#Rest API#

* Es el sistema tradicional
* Lo llaman old REST API
* La documentación está mas escondida

!SLIDE bullets incremental

#Graph API#

* http://graph.facebook.com
* Es un sistema relativamente reciente de comunicación
* Mas REST que antes
* Simplifica mucho el proceso para los desarrolladores. 

!SLIDE

#Graph API#

##Mediante llamadas a la API obtenemos datos JSON en un formato similar para todas las opciones (usuarios, páginas, eventos, grupos, etc)##

!SLIDE small code

#Graph API#

    {
       "name": "Facebook Platform",
       "type": "page",
       "website": "http://developers.facebook.com",
       "username": "platform",
       "founded": "May 2007",
       "company_overview": "Facebook Platform enables anyone to build...",
       "mission": "To make the web more open and social.",
       "products": "Facebook Application Programming Interface (API)...",
       "fan_count": 449921,
       "id": 19292868552,
       "category": "Technology"
    }
    
###Podemos ver [algunos ejemplos](http://developers.facebook.com/docs/api) de qué datos podemos obtener y en qué formato.###


