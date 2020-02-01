# Workflow GIT
Documentación de flujo de trabajo con GIT

## Organización

Se recomienda crear una organización que sea la propietaria del repositorio principal. A partir de dicho repositorio los miembros o colaboradores podrán hacer un fork hacia sus cuentas personales.

### Pasos para crear una organización

1. Click en tu foto perfil (Esquina superior derecha)
2. Click en Settings
3. Click en Organizaciones (Menú izquierdo)
4. Click en Nueva organización
5. Elegir plan y llenar datos

## Creación de Fork

Para crear un fork debes iniciar sesión en GitHub y luego ingresar a la landing page del proyecto del que quieras sacar tu Frok.

## Como trabajar con 2 o más remotos

Listar remotos git remote -v

Agregar remotos git remote add flow-git https://github.com/workflow-nacho/flow-git

Eliminar remotos git remote remove flow-git


## Creando etiquetas

Es necesario entender que las etiquetas o releases como buena practica, sólo deben ser creadas a partir de la rama master... 

Para entender cómo llamar o categorizar tus versiones te recomendamos un artículo en el blog de EDTeam: https://ed.team/blog/como-se-deciden-las-versiones-del-software


# Resumen
1. Crear una organización
2. Crear un proyecto dentro de la organización
3. Si el pryecto es privado agregar a todos los colaboradores
4. Cada colaborador debe tener un Fork en su cuenta
5. Cada desarrollador debe tener un clone en su máquina
6. El programador debe agregar los remotos correspondientes del proyecto original
7. Se debe asegurar que todo este correctamente sincronizado
8. Se creará una nueva rama para agregar una funcionalidad
9. Una vez terminado el trabajo, el desarrollador sube (push) esa rama a su fork
10. En GitHub aparecerá la opción de hacer un pull request
11. Una vez creado el pull request, el administrador lo revisará
12. Se aprueba o se rechaza el pull request
13. Cada dev debe revisar constantemente (fetc) si no hubo cambios en el proyecto original
14. Se debe eliminar las ramas que ya fueron aprobadas/rechazadas
