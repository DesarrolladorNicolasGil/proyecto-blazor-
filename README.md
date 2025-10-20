# proyecto-blazor-
# EventEase - Aplicación de Gestión de Eventos (Proyecto Blazor)

Este proyecto fue desarrollado utilizando el marco Blazor y asistido en gran medida por Microsoft Copilot, siguiendo los requisitos de la tarea calificada.

## Asistencia de Microsoft Copilot en el Desarrollo

| Tarea Clave | Requisito de la Tarea | Cómo Ayudó Copilot |
| :--- | :--- | :--- |
| **Generación de Componente** | Componente fundacional Event Card con campos y vinculación de datos bidireccional. | Proporcionó el *boilerplate* de la estructura Razor, las propiedades `[Parameter]` para el modelo y sugirió la sintaxis correcta para la vinculación bidireccional (`@bind-checked` en el componente hijo). |
| **Enrutamiento** | Implementación y depuración de la funcionalidad de enrutamiento. | Ayudó a definir la directiva `@page` en `Registration.razor` y en `Index.razor` (usando `Match="NavLinkMatch.All"`) y sugirió los componentes `NavLink` en `NavMenu.razor`. |
| **Funciones Avanzadas (Validación)** | Formulario de registro con validación. | Generó la clase `UserModel` con las `DataAnnotations` (`[Required]`, `[EmailAddress]`, etc.) y ensambló la estructura `EditForm` con `DataAnnotationsValidator` y `ValidationSummary`, asegurando la validación del lado del cliente. |
| **Optimización y Gestión de Estados** | Optimización del rendimiento y gestión de estados/asistencia. | Ayudó a estructurar la lógica asíncrona simulada en `HandleValidSubmit` y sugirió el uso de una propiedad booleana `IsRegistered` en `EventCard` para manejar eficientemente el estado de asistencia de manera local y reactiva. |
