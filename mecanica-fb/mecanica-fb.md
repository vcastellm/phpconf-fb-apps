!SLIDE
#OAuth 2.0#

<pre style="font-size:1em">
+--------+                                  +---------------+
|        |--(C)--- Client Credentials ----->| Authorization |
|        |                                  |     Server    |
|        |&lt;-(D)------ Access Token ---------|               |
|        |                                  +---------------+
| Client |
|        |                                  +---------------+
|        |--(E)------ Access Token -------->|    Resource   |
|        |                                  |     Server    |
|        |&lt;-(F)---- Protected Resource -----|               |
+--------+                                  +---------------+
</pre>

Es un protocolo de autenticación
<p>Mediante tokens, permite autenticar a los usuarios.</p>

[http://developers.facebook.com/docs/authentication/](http://developers.facebook.com/docs/authentication/)

!SLIDE
#Mecánica de la API de Facebook#
##Graph API##
<p>Es un sistema relativamente reciente de comunicación que simplifica mucho el proceso para los desarrolladores. Mediante llamadas a la API obtenemos datos JSON en un formato similar para todas las opciones (usuarios, páginas, eventos, grupos, etc)</p>
Podemos ver [algunos ejemplos](http://developers.facebook.com/docs/api) de qué datos podemos obtener y en qué formato.

