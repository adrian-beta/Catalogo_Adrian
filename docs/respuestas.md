79. ¿Cómo identificaste el comando necesario cuando la práctica no lo proporcionó?
Recorde lo que hice en el anterior trabajo por ejemplo primero installar el entorno virtual y antes de instalar las dependencias debia activa el entorno

80. ¿Qué diferencia existe entre preparar un archivo para un commit y crear el commit?
La diferencia es que primero revisamos que archivos fueron cambiados con git status y los agregamos con git add . para asi tener preparado el archivo para cuando creamos el commit

81. ¿Cómo puedes comprobar en qué rama estás trabajando?
git branch te marca con un * la rama que estas utilizando

82. ¿Cómo puedes determinar qué archivos fueron modificados antes de registrarlos?
git status te muestra los archivos que fueron modificados y que no han sido registrados

83. ¿Cómo puedes observar exactamente qué cambió dentro de un archivo?
puedes cambiar de rama a la main para saber que fue modificada o en github en el pull request puedes revisar los archivos que fueron modificados

84. ¿Por qué debe reconstruirse .venv después de obtener un repositorio?
Por que contiene el entorno virtual de una computadora en especifico y normalmente no se sube al repositorio

85. ¿Qué relación existe entre requirements.txt y .gitignore?
los dos tienen funciones ya establecidas uno tiene las dependecias que necesitas para el trabajo y el otro no permite que ciertos archivos como el .venv se guardan al hacer commits o subirlo al repositorio de la nube

86. ¿Por qué la colaboración se realiza desde una rama y no directamente desde main?
Para evitar que los cambios dde cada persona afecten el codigo principal antes de ser revisados

87. ¿Por qué una solicitud de cambios no requiere crear un Pull Request nuevo?
Por que una solicitud de cambios ya esta abierta para esa rama, si haces mas cambos y los subes a la misma rama esos commits se agregan automaticamente

88. Después de realizar el merge en GitHub, ¿por qué todavía es necesario actualizar el repositorio local?
Por que los cambios se realizaron en el repositorio de la nuve pero en el local sigues teniendo una version antigua del trabajo


## Pregunta de control
¿Por qué el repositorio que tienes ahora en tu computadora no es el
mismo concepto que el fork creado en GitHub?

es un clone para no trabajar sobre el repositorio original y evitar algun problema a futuro