# InvoiceInternational
Examen Final - Análisis de Sistemas II
# TECNOLOGÍA
>ASP.NET CORE
```
El backend del proyecto está desarrollado en ASP.NET Core, el cual es un framework de
código abierto y multiplataforma para la creación de aplicaciones modernas conectadas a
Internet, como aplicaciones web y APIs Web. Se diseñó para proporcionar un framework de
desarrollo optimizado para las aplicaciones que se implementan tanto en la nube como en
servidores dedicados en las instalaciones del cliente
Millones de desarrolladores han usado ASP.NET 4.x (y siguen usándolo) para crear
aplicaciones web. ASP.NET Core es un nuevo diseño de ASP.NET 4.x que cuenta con
cambios en la arquitectura que dan como resultado un marco más sencillo y modular.
ASP.NET Core se integra perfectamente con bibliotecas y marcos populares del lado cliente,
que incluyen Blazor, Angular, React y Bootstrap.
```

# RAMAS
```
1. master: En la rama máster se encuentran las releases estables de nuestro software. Esta es la rama que un usuario típico se descargará para usar nuestro software, por lo que todo lo que hay en esta rama debería ser funcional. Sin embargo, puede que las últimas mejoras introducidas en el software no estén disponibles todavía en esta rama
2. develop: En esta rama surge de la última release de master. En ella se van integrando todas las nuevas características hasta la siguiente release.
3. feature-favio: Cada nueva mejora o característica que vayamos a introducir en nuestro software tendrá una rama que contendrá su desarrollo. Las ramas de feature salen de la rama develop y una vez completado el desarrollo de la mejora, se vuelven a integrar en develop.
4. release: Las ramas de release se crean cuando se va a publicar la siguiente versión del software y surgen de la rama develop . En estas ramas, el desarrollo de nuevas características se congela, y se trabaja en arreglar bugs y generar documentación. Una vez listo para la publicación, se integra en master y se etiqueta con el número de versión correspondiente. Se integran también con develop, ya que su contenido ha podido cambiar debido a nuevas mejoras.
5. Hotfix: Si nuestro código contiene bugs críticos que es necesario parchear de manera inmediata, es posible crear una rama hotfix a partir de la publicación correspondiente en la rama master. Esta rama contendrá únicamente los cambios que haya que realizar para parchear el bug. Una vez arreglado, se integrará en master, con su etiqueta de versión correspondiente y en develop.
```

