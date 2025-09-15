# 📌 Gestión de Bajas Técnicas  

Aplicación web desarrollada en **ASP.NET Core** con **Entity Framework Core** y base de datos **MySQL**.  
El sistema automatiza la **gestión de bajas técnicas** en una empresa de infocomunicaciones, optimizando el control del inventario, los procesos de mantenimiento, traslados y bajas de equipos.  

---

## 🎯 Objetivos del Sistema
- Digitalizar la gestión de **equipos y su ciclo de vida** (alta, mantenimiento, traslado y baja).  
- Reducir el riesgo de pérdida de información mediante un sistema centralizado.  
- Facilitar la **toma de decisiones** con reportes y estadísticas.  
- Evaluar el **desempeño del personal técnico** a través de métricas de efectividad y costos.  

---

## ⚙️ Funcionalidades Implementadas
- 📦 **Inventario de equipos** con identificador único, tipo, estado, ubicación y fecha de adquisición.  
- 🛠️ **Gestión de mantenimientos** con registro de fecha, tipo, costo y técnico responsable.  
- 🔄 **Traslados de equipos** entre áreas, con origen, destino, responsables y receptores.  
- ❌ **Procesos de baja técnica**, con causa, destino final, fecha y persona receptora.  
- 👨‍🔧 **Gestión de técnicos**, incluyendo datos personales, experiencia, especialidad, historial de intervenciones y valoraciones.  
- 📊 **Reportes dinámicos y consultas avanzadas**:  
  - Equipos dados de baja en el último año.  
  - Historial de mantenimientos por equipo.  
  - Equipos trasladados entre secciones.  
  - Correlación entre rendimiento técnico y longevidad de equipos.  
  - Equipos con más de tres mantenimientos en el último año (para reemplazo).  
  - Comparación de técnicos para definir bonificaciones o penalizaciones.  
- 📑 **Exportación de reportes a PDF** y posibilidad de ordenar resultados por columnas.  

---

## 🛠️ Tecnologías Utilizadas
- **Framework Backend:** ASP.NET Core  
- **ORM:** Entity Framework Core  
- **Base de Datos:** MySQL  
- **Frontend:** Razor Pages con soporte de CSS personalizado  
- **Generación de Reportes:** Tablas y gráficos con exportación a PDF  
- **Pruebas:** Unitarias en back-end y front-end  
- **Arquitectura:** desacoplada, extensible y mantenible  
- **Control de versiones y planificación:** GitHub Projects e Issues  
