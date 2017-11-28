# boostrap-theme
Repositorio para customizar un theme de bootstrap 4 utilizando el códigp fuente *.scss

El tema creado esta inicialmente basado en la visual que define: www.santafe.gov.ar/assets pero con soporte completo para bootstrap 4.

Intructivo:
==========

1- Instalar nodejs (preferentemente con el gestor de versiones: https://github.com/creationix/nvm)

2- Ejecutar npm install para instalar las dependencias del proyecto (si las requiere).

3- Dentro de la carpeta scss/ se encuentra el archivo custom.scss sobre este se realiza el import de todos los componentes de  boostrap 4 y se realiza el override o extend de las variables y estilos scss (Ref: https://getbootstrap.com/docs/4.0/getting-started/theming/ ). 

4- Luego utilizando node-sass custom.scss custom.css (para instalar node-sass: https://www.npmjs.com/package/node-sass ) vamos generando el theme de bootstrap customizado.-
