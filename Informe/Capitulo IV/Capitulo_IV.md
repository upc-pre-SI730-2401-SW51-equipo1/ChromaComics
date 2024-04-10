# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1.General Style Guidelines

![](https://lh7-us.googleusercontent.com/d892mPIjqBQroRelhQCan5lLKRWxaLp_65sdK7YPj4FNjY1bkqRV0xTiVsBd5IbLtuPayYc-PlVXL6lphP96pePHCFVnEgDNVrgRAKlM7FjckxpxItQnYGz2pDmzsTGZPLtjlYIUUR_NwUZwU9KiQtc)

Enlace para el figma: [https://shorturl.at/fT389](https://shorturl.at/fT389)

### 4.1.2. Web Style Guidelines. 
![](https://lh7-us.googleusercontent.com/XI4pRLNd71Ra287PkxbVuMFCBx2C4YT2TVgR9lQQLN_03qjK_NhUP6NPqOe765nwnlnzuyetlIeRdhfuZSXskw9Llwx5AtcBdmnSyqrZ11fO73THEGbtnfe4tDnciGEG_k6s3DNUw_y6RheuEvk6TL8)

Enlace para el figma: [https://shorturl.at/fT389](https://shorturl.at/fT389)

## 4.2. Information Architecture

### 4.2.1. Organization Systems
La organización de la información en la plataforma se basará en una serie de sistemas que facilitarán la búsqueda y el acceso al contenido por parte de los usuarios. Se crearán categorías que agrupen las obras por género, demografía y temática.

### 4.2.2. Labeling Systems 
Se podrán etiquetar las obras con palabras clave para facilitar su búsqueda. Los usuarios también tendrán la posibilidad de crear colecciones de sus obras favoritas.Se implementará un sistema de etiquetado que incluya etiquetas descriptivas y relevantes al contenido de las obras. Se utilizarán sinónimos y palabras clave para facilitar la búsqueda por parte de los usuarios.

### 4.2.3. SEO Tags and Meta Tags
Se añadirán etiquetas SEO y meta etiquetas para que la plataforma sea visible en los motores de búsqueda.

### 4.2.4. Searching Systems
Se implementará un sistema de búsqueda que permitirá a los usuarios encontrar las obras que buscan de forma rápida y sencilla. Este sistema tendrá en cuenta las categorías, etiquetas, títulos y descripciones de las obras.

### 4.2.5. Navigation Systems
Intuitiva, con menú principal, pie de página y breadcrumbs.

## 4.3. Landing Page UI Design. 

Enlace para el figma: [https://shorturl.at/fT389](https://shorturl.at/fT389)

### 4.3.1. Landing Page Wireframe

![](https://lh7-us.googleusercontent.com/ZNDNVuFk93bKNpw2VevZsLl_gMuI8TPN6Wu0NFlbPQOvwuTKom5sD-E2RPUPIyAhsGerNtfCicjJsCiD1x_tD9789iTZ1mnI6OBmw4U6KaMbcbABTgK85LQ12HJ5KnOGNVIMf4E4Nla7jmqGuaPfLA4)

Enlace para el figma: [https://shorturl.at/fT389](https://shorturl.at/fT389)

### 4.3.2. Landing Page Mock-up. 6/34 V1.0

**![image](https://github.com/upc-pre-SI730-2401-SW51-equipo1/ChromaComics/assets/145626151/e6c0c8d4-6683-4f62-9cb8-9772384040e6)**

Enlace para el figma: [https://www.figma.com/file/Q36lXagtHafwvymDgoRmJn/PROJECT-CHROMA-COMICS-(Copy)?type=design&node-id=7-82&mode=design&t=gN8dvcxRHqDoxXCY-0](https://www.figma.com/file/Q36lXagtHafwvymDgoRmJn/PROJECT-CHROMA-COMICS-(Copy)?type=design&node-id=7-82&mode=design&t=gN8dvcxRHqDoxXCY-0)

## 4.4. Web Applications UX/UI Design. 
### 4.4.1. Web Applications Wireframes.

<img src="https://github.com/upc-pre-SI730-2401-SW51-equipo1/ChromaComics/blob/Informe/assets/Captura%20de%20pantalla%202024-04-09%20211806.png" width="300"/>

#### enlace figma: https://www.figma.com/file/KfWXjIlXJKS37xUiRLbRF3/ChromeComics?type=design&node-id=0%3A1&mode=design&t=vdFAD6nMQxCXaJNB-1

### 4.4.2. Web Applications Wireflow Diagrams. 

### 4.4.2. Web Applications Mock-ups


figma:https://www.figma.com/file/Q36lXagtHafwvymDgoRmJn/PROJECT-CHROMA-COMICS-(Copy)?type=design&node-id=91%3A189&mode=design&t=RjzO2SV7g0vA73Cu-1

### 4.4.3. Web Applications User Flow Diagrams. 

## 4.5. Web Applications Prototyping. 
## 4.6. Domain-Driven Software Architecture. 
### 4.6.1. Software Architecture Context Diagram.
<img src="https://github.com/upc-pre-SI730-2401-SW51-equipo1/ChromaComics/blob/Informe/assets/structurizr-87456-SystemContext-001%20(1).png" width="500"/>

### 4.6.2. Software Architecture Container Diagrams.

<img src="https://github.com/upc-pre-SI730-2401-SW51-equipo1/ChromaComics/blob/Informe/assets/structurizr-87456-Container-001%20(5).png" width="300"/>

### 4.6.3. Software Architecture Components Diagrams. 
<img src="https://github.com/upc-pre-SI730-2401-SW51-equipo1/ChromaComics/blob/Informe/assets/structurizr-87456-Component-001.png" width="300"/>

## 4.7. Software Object-Oriented Design. 
### 4.7.1. Class Diagrams. 

<img src="https://github.com/upc-pre-SI730-2401-SW51-equipo1/ChromaComics/blob/Informe/assets/class%20diagram_page-0001.jpg" width="300"/>

### 4.7.2. Class Dictionary. 
1. **Empleado**
    - **Descripción**: Representa a un empleado de la tienda.
    - **Atributos**: 
        - idEmpleado (String)
        - nombre (String)
        - puesto (String)
    - **Métodos**: 
        - gestionarInventario()
        - responderChat()
        - resolverTicket()

2. **Gerente**
    - **Descripción**: Representa al gerente de la tienda.
    - **Atributos**: 
        - idGerente (String)
        - nombre (String)
    - **Métodos**: 
        - supervisarEmpleados()

3. **Cliente**
    - **Descripción**: Representa a un cliente de la tienda.
    - **Atributos**: 
        - idCliente (String)
        - nombre (String)
    - **Métodos**: 
        - iniciarChat()
        - consultarBaseConocimientos()
        - crearTicketSoporte()

4. **AplicacionMovil**
    - **Descripción**: Representa la aplicación móvil que los clientes utilizan para interactuar con la tienda.
    - **Atributos**: 
        - idApp (String)
        - version (String)
    - **Métodos**: 
        - iniciarSesion()
        - realizarCompra()

5. **SistemaRecomendacion**
    - **Descripción**: Representa el sistema que genera recomendaciones para los clientes.
    - **Atributos**: 
        - idSistema (String)
    - **Métodos**: 
        - generarRecomendaciones()

6. **RealizarCompras**
    - **Descripción**: Representa el proceso de realizar compras en la aplicación móvil.
    - **Atributos**: 
        - idCompra (String)
        - idCliente (String)
    - **Métodos**: 
        - procesarCompra()

7. **ProcesamientoCompras**
    - **Descripción**: Representa el proceso de procesamiento de las compras realizadas.
    - **Atributos**: 
        - idProcesamiento (String)
        - idCompra (String)
    - **Métodos**: 
        - procesarPago()
        - actualizarInventario()

8. **InventarioEnTiempoReal**
    - **Descripción**: Representa el inventario en tiempo real de la tienda.
    - **Atributos**: 
        - idInventario (String)
        - productos (List<Producto>)
    - **Métodos**: 
        - gestionarInventario()
        - actualizarInventario()

9. **AlmacenamientoYAnalisisDatosNube**
    - **Descripción**: Representa el almacenamiento y análisis de datos en la nube.
    - **Atributos**: 
        - idAlmacenamiento (String)
    - **Métodos**: 
        - almacenarDatos()
        - analizarDatos()

10. **ServiciosPagoEnLinea**
    - **Descripción**: Representa los servicios de pago en línea utilizados para procesar los pagos de las compras.
    - **Atributos**: 
        - idServicio (String)
    - **Métodos**: 
        - procesarPago()

11. **SistemaSoporteCliente**
    - **Descripción**: Representa el sistema de soporte al cliente.
    - **Atributos**: 
        - idSoporte (String)
    - **Métodos**: 
        - iniciarChat()
        - consultarBaseConocimientos()
        - crearTicketSoporte()

12. **ChatEnVivo**
    - **Descripción**: Representa el chat en vivo utilizado para la comunicación en tiempo real entre los clientes y los empleados.
    - **Atributos**: 
        - idChat (String)
        - idCliente (String)
        - idEmpleado (String)
    - **Métodos**: 
        - iniciarChat()
        - enviarMensaje()
        - recibirMensaje()
        - finalizarChat()

13. **BaseConocimientos**
    - **Descripción**: Representa la base de conocimientos que los clientes pueden consultar para obtener información útil.
    - **Atributos**: 
        - idBase (String)
        - articulos (List<Articulo>)
    - **Métodos**: 
        - consultarArticulo()

14. **SistemaTickets**
    - **Descripción**: Representa el sistema de tickets que los clientes pueden utilizar para reportar problemas y los empleados pueden resolver.
    - **Atributos**: 
        - idTicket (String)
        - idCliente (String)
        - idEmpleado (String)
    - **Métodos**: 
        - crearTicket()
        - resolverTicket()



## 4.8. Database Design. 
### 4.8.1. Database Diagram.
<img src="https://github.com/upc-pre-SI730-2401-SW51-equipo1/ChromaComics/blob/Informe/assets/Captura%20de%20pantalla%202024-04-08%20150916.png" width="700"/>


