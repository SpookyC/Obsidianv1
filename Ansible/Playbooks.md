Ansible es una de las herramientas más poderosas para la automatización de la administración de máquinas, permitiendo especificar mediante un lenguaje declarativo el estado requerido para las máquinas gestionadas.

Si no conoces todavía Ansible, antes de la lectura de este artículo te recomendamos echar un vistazo al post [Qué es Ansible](https://www.arsys.es/blog/ansible). En este caso partimos de un servidor de control configurado y un servidor al que nos vamos a conectar, para administrarlo remotamente. Si no sabes completar estas configuraciones, están explicadas en el artículo [Primeros pasos con Ansible](https://www.arsys.es/blog/primeros-pasos-con-ansible).

En Ansible se llaman «Playbooks» a los **archivos de texto que describen de manera declarativa el estado necesario a aplicar en los servidores administrados**. Estos archivos se escriben en un lenguaje de texto plano y se usarán desde el ordenador que hace las veces de nodo de control. Queda para Ansible la elección de los módulos que sean necesarios para producir los efectos requeridos.

![[Pasted image 20220429152750.png]]

Relacionado a >> [[Ansible]]