# 👕 Sistema de Gestión de Entrega de Uniforme y EPP

*(Coloca aquí una captura de pantalla de la aplicación, mostrando el logotipo superior izquierdo, el título "ENTREGA DE UNIFORME Y EPP" y el panel de filtros)*.

**Plataforma web colaborativa y en tiempo real para la digitalización, control y trazabilidad de entregas masivas de indumentaria corporativa (Ej. Temporada Verano 2027).**

### 🎯 El Desafío Operativo
La entrega de dotación a cientos de trabajadores generaba largas filas y dependía de búsquedas manuales en planillas de Excel. Además, era complejo mantener la cuadratura contable por centro de costo y gestionar las excepciones del personal (licencias, vacaciones o desvinculaciones) al momento de emitir las actas físicas para la firma.

### 🚀 La Solución y Características Clave
Desarrollé una interfaz ágil conectada bidireccionalmente a Google Sheets que resuelve el ciclo completo de entrega y reportería:

* **Sincronización Multi-Computador en Tiempo Real:** Permite a varios asistentes de bodega operar simultáneamente sin duplicar entregas ni generar conflictos de datos en la base maestra.
* **Control de Estados y Filtros *Sticky*:** Navegación optimizada con filtros flotantes al hacer scroll para segmentar rápidamente al personal por estado (Activo, Licencia, Vacaciones, Desvinculado).
* **Gestión de Errores (Botón ↩️):** Funcionalidad de reverso inmediato que anula una entrega por error y actualiza automáticamente el inventario en la hoja de cálculo.
* **Reportería y Actas en PDF:** Exportación dinámica de reportes consolidados por área y centro de costo, y generación automática de actas de recepción (formato PV2) con espacio designado para firmas.
* **Accesibilidad Visual:** Integración de un *toggle* de modo daltónico con niveles ajustables de alto contraste, garantizando la usabilidad para todos los operadores.
* **UI/UX Operativa:** Botón de alternancia rápido entre la vista de "Reportes" y "Acciones", y renderizado de imágenes servidas desde GitHub.

### 🛠️ Stack Tecnológico y Arquitectura
* **Frontend:** HTML5, CSS3, Vanilla JavaScript.
* **Backend y Endpoints:** Google Apps Script para la comunicación asíncrona.
* **Base de Datos:** Google Sheets (Lógica de estructuración avanzada de columnas y mapeo de datos).
* **Gestión de Activos:** GitHub Pages/Repositorio para el alojamiento de logos e iconografía.

