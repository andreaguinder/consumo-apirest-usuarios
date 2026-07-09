# Consumo de API REST de Usuarios y renderizado

## Descripción del Proyecto

Esta aplicación es un buscador dinámico de usuarios desarrollado con React y Vite. La aplicación consume una API pública para obtener un listado de perfiles y permite visualizar la información a través de tarjetas personalizadas, además de ofrecer una búsqueda inteligente que filtra los resultados por nombre y nombre de usuario en tiempo real.

Este proyecto fue desarrollado para practicar la integración de servicios externos y el flujo de datos entre componentes en React, implementando:

* Consumo de APIs: Uso de fetch con async/await dentro de useEffect para la obtención de datos.

* Gestión de Estado: Implementación de estados para manejar el ciclo de vida de la petición (loading, error, data).

* Elevación de Estado (Lifting State Up): Centralización de la lógica de búsqueda en el componente padre (App) para sincronizar el buscador con la lista.

* Componentización: Arquitectura modular dividiendo la responsabilidad entre Usuarios, UsuarioCard y Search.

---

## Funcionalidades Implementadas

* Renderizado Condicional: La interfaz responde de manera fluida mostrando estados de carga, manejo de errores en caso de fallo, o la lista de usuarios.

* Búsqueda en Tiempo Real: Filtrado de usuarios por name y username de manera simultánea mientras el usuario escribe.

* Componentes Reutilizables: La presentación visual se maneja mediante UsuarioCard, facilitando la escalabilidad y el mantenimiento de los estilos.

---

## Estructura de Archivos Principal

La aplicación está organizada para favorecer la limpieza y la separación de responsabilidades:

* src/components/: 

    * Search/: Componente de entrada para la búsqueda.
    * Usuarios/: Contenedor principal que gestiona el fetch y el filtrado.
    * UsuarioCard/: Componente visual para cada usuario.

* src/styles/: Estilos modulares (.module.scss) aplicados a cada componente para un diseño encapsulado.

---

## ¿Te gustaría colaborar o tenés un desafío laboral?

¡Me encantaría conectar con vos! Estoy abierta a nuevas oportunidades, proyectos desafiantes o simplemente charlar sobre tecnología.

* **Email:** [andreabelen.guinder@gmail.com](mailto:andreabelen.guinder@gmail.com)
* **LinkedIn:** [https://www.linkedin.com/in/andrea-guinder/](https://www.linkedin.com/in/andrea-guinder/)
* **Portfolio:** [https://andreaguinder.com/](https://andreaguinder.com/)
