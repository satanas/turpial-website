---
layout: post
title: Continúan los problemas con los DMs
published: true
author: satanas
comments: true
date: 2011-07-30 03:07:15
tags: [ ]
categories:
    - mejoras
    - cambios-en-twitter
permalink: /2011/07/continuan-los-problemas-con-los-dms
---
Hemos recibido muchos comentarios de que aún persisten los problemas para acceder a los DMs desde Turpial, sin embargo yo seguí los pasos que describí en el [artículo anterior][1] y me funcionó. Me parece que el problema es que Twitter tarda algo de tiempo en revocar el token autenticado, mi recomendación para los que aún presentan este problema es la siguiente: 1.- Entra a tu perfil en [twitter.com][2], busca la sección de Opciones y en Aplicaciones revoca el acceso a Turpial. 2.- Espera un par de minutos e inicia sesión con Turpial 3.- Verifica que Turpial aparece registrado como aplicación con los permisos tal y como se muestran en la imagen a continuación: [][3] Si Turpial no aparece con esos permisos repite los pasos 1 y 2 hasta que aparezca, yo tuve que intentarlo varias veces hasta que funcionó. Y es que al parecer a veces cuesta que Twitter procese la petición de revocación de permisos (así como ocurre cuando intentamos cambiar la imagen de perfil). Espero que con estos pasos todos puedan solucionar el problema y sigan usando Turpial sin problema

 [1]: http://turpial.org.ve/2011/07/twitter-y-las-nuevas-politicas-de-seguridad-dm/
 [2]: http://twitter.com
 [3]: http://turpial.org.ve/wp-content/uploads/2011/07/permisos_dms.png