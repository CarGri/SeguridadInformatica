# Configurar un servidor para una pequeña empresa

Configurar correctamente el servidor es muy importante, porque **es una parte básica de la organización.** Interviene en muchas tareas esenciales y de él depende el buen funcionamiento de la informática de la empresa.

Hay una serie de pasos para configurar un servidor, que podemos reducir a los 5 siguientes:

## Seleccione el [hardware](https://aratecnia.es/glosario/hardware/) del servidor

Los servidores pueden realizar una amplia variedad de tareas, pero **se utilizan mejor cuando realizan sólo una o unas pocas tareas específicas**

En un ámbito empresarial, **los usos más comunes de los servidores** son:

- Servidor de archivos
- Servidor de [base de datos](https://aratecnia.es/glosario/base-de-datos/)
- Servidor web
- Servidor de correo
- Servidor de impresión
- Servidor de dominio y
- Servidor de aplicaciones

Determinadas aplicaciones de servidor requerirán **características específicas**, por ejemplo:

- Los servidores de bases de datos deben admitir RAID (matriz redundante de discos independientes) y tener discos duros capaces de alcanzar velocidades de escritura rápidas.
- Los servidores web se benefician de una alta [RAM](https://aratecnia.es/glosario/ram/) y [redundancia](https://aratecnia.es/glosario/redundancia/) de hardware.
- Lo ideal es que los servidores de archivos tengan múltiples puertos de unidades intercambiables en caliente.

**Cada tipo de servidor tiene su propio hardware y características específicas que determinan sus capacidades.** Por lo tanto, al elegir su servidor, debe prestar especial atención al tamaño de la [CPU](https://aratecnia.es/glosario/cpu/), el almacenamiento en el disco duro y la RAM con respecto al propósito del servidor.

## Seleccione el sistema operativo del servidor

Los servidores necesitan sistemas operativos especializados que sean más robustos y estén diseñados para soportar muchos usuarios simultáneamente.

Los sistemas operativos más comunes para servidores son:

- Windows Server Essentials
- Linux Ubuntu Server   
- Red Hat Enteprise Linux x  
- CentOS

Seleccionar el correcto [sistema](https://aratecnia.es/glosario/sistema/) operativo para su servidor es una decisión importante que impacta directamente en el coste

Hay unos factores a considerar antes de elegir un sistema operativo de servidor

1**. Facilidad de uso**

La facilidad de instalación, [configuración](https://aratecnia.es/glosario/configuracion/) y uso es un factor extremadamente importante a considerar al elegir un sistema operativo de servidor. Esto es especialmente crítico para las pequeñas y medianas empresas que quizás no cuenten con personal de TI dedicado.

2. **Apoyo**

Los sistemas operativos de servidor de Windows suelen ser populares entre los usuarios de Windows porque tienen una apariencia muy similar al sistema operativo Windows para PC. Por otro lado, los sistemas operativos Linux tienen una curva de aprendizaje muy pronunciada y requerirán un experto en Linux para su instalación, operación y mantenimiento.

Como Linux es un sistema operativo de [código](https://aratecnia.es/glosario/codigo/) abierto, es probable que tenga que pasar mucho tiempo investigando en línea cada vez que haya un problema con tu servidor. Sin embargo, Microsoft ofrece soporte al cliente multicanal de alta calidad.

Los requisitos de soporte suelen desempeñar un papel fundamental en la elección de un sistema operativo. Para la mayoría de las pequeñas empresas es difícil tener personal de TI dedicado a su servidor Linux y, por lo tanto, el sistema operativo Windows Server a menudo se convierte en la opción predeterminada.

3. **Personalización**

Si tiene experiencia técnica y está familiarizado con Linux, son bastante flexibles y le brindan más opciones de personalización que el sistema operativo Windows.

 **4. Coste**

Como software de código abierto, Linux es más barato de ejecutar que los sistemas operativos de servidor Windows. Sin embargo, también es necesario considerar el costo total de las operaciones de TI , incluido el tiempo y la experiencia técnica necesarios para la operación y el mantenimiento del servidor.

## **Elegir una ubicación para el servidor en la oficina**

Idealmente, **debería tener una sala dedicada para albergar su servidor**. Aunque puede optar por un servidor de torre pequeño, vale la pena tener un espacio separado para su servidor. Además de aislar el servidor ruidoso, también es recomendable desde el punto de vista de la seguridad. **Al controlar el acceso físico al servidor, puede mitigar muchos riesgos de seguridad de los datos**. Esto puede incluso ser una necesidad para ciertos cumplimientos normativos.

**Su sala de servidores debe ser una sin ventanas, pero con capacidad para instalar equipos de refrigeración y energía de respaldo**. Las altas temperaturas pueden dañar el hardware de su servidor, por lo que debe tener un sistema de enfriamiento que pueda funcionar continuamente. La sala debe ser lo suficientemente grande como para permitirle llegar al frente y a la parte trasera del servidor. Aunque puede instalar fácilmente el servidor en un escritorio o mesa, **es mucho más beneficioso invertir en un montaje en rack adecuado.** Los bastidores mantienen el hardware de su servidor seguro y organizado, lo que permite una mejor escalabilidad.

Un aspecto que a menudo se pasa por alto al configurar un servidor es la gestión de cables. **Los trabajos de reparación y mantenimiento, así como la resolución de problemas de hardware, son mucho más fáciles si los cables están bien organizados** y etiquetados correctamente. Incluso una oficina relativamente pequeña puede terminar teniendo una gran cantidad de cables, lo que hace que su sala de servidores sea un desastre de cables enredados. Por lo tanto, es muy recomendable invertir en un panel de conexiones para ayudar a organizar los cables.

## Configuración del servidor

Antes de que pueda comenzar a configurar su servidor, debe instalar el sistema operativo. Este proceso no es muy diferente de la instalación en su PC o Mac desde un DVD, USB o medio [virtual](https://aratecnia.es/glosario/virtual/). En algunos casos, el servidor puede venir con el sistema operativo preinstalado. En tal caso, puede comenzar la configuración de inmediato.

Después de instalar el sistema operativo, aquí se muestran algunas **configuraciones típicas para servidores de oficina**:

- Establezca una contraseña de administrador segura para el servidor.
- Configurar redes; la configuración de red predeterminada suele ser suficiente.
- Agregue cuentas de administrador local a cada computadora y conéctelas al servidor.
- Configure su servidor como controlador de dominio para que todas las computadoras de su red puedan unirse al nuevo entorno centralizado y el servidor pueda autenticar las credenciales de los usuarios.
- Configure el acceso [remoto](https://aratecnia.es/glosario/remoto/) y las opciones para compartir.
- Configure la [copia de seguridad](https://aratecnia.es/glosario/copia-de-seguridad/) del servidor. Siga la estrategia de copia de seguridad de datos de su organización.
- Configure el firewall para proteger el servidor de intrusiones.

Los pasos anteriores variarán según la función del servidor. La complejidad de los pasos también variará dependiendo de si se va a funcionar como servidor web, servidor de base de datos, servidor de [impresora](https://aratecnia.es/glosario/impresora/), etc.

## Implementación de la seguridad del servidor

Su servidor es probablemente la pieza de hardware más importante de su oficina. Están en el corazón de toda la actividad empresarial, desde el suministro de servicios a los clientes hasta el intercambio de datos y la gestión de bases de datos, entre muchos otros. Debido a que son tan vitales para el funcionamiento diario de una organización, **los servidores son un objetivo atractivo para los piratas informáticos. Por tanto, la seguridad del servidor debe tomarse muy en serio.**

Los servidores pueden ser atacados desde múltiples vectores. Los servidores web y de correo se conectan directamente a Internet y, por lo tanto, pueden ser atacados por malware. Incluso cuando su servidor no se conecta directamente a Internet, digamos en el caso de los servidores de bases de datos, aún pueden ser vulnerables a través de una intrusión lateral desde su red interna. Algunos de los **métodos de ataque comunes** son:

- Correos electrónicos de phishing
- Puertos abiertos no seguros
- Ataques desde vehículos
- troyanos
- DDoS

A continuación, se muestran algunas **formas en las que puede mejorar la seguridad de sus servidores:**

- Establecer controles de acceso físicos y virtuales para limitar el acceso al servidor,
- Instalar y mantener actualizado el software antivirus y antimalware,
- Configurar y mantener un firewall,
- Activar los sistemas de detección y prevención de intrusos,
- Cifre sus datos,
- Realice copias de seguridad periódicas de los datos críticos,
- Utilice software para monitorear el estado del servidor y las anomalías del tráfico.
- Analizar periódicamente los [registros](https://aratecnia.es/glosario/registros/) y
- Realizar periódicamente auditorías de seguridad de la red.

….



