Índice de Plantillas

**Ubicación**: `PartXI/DocumentationManagement/Templates/index.md`

Este archivo sirve como **índice principal** para todas las **plantillas** que se utilizan en la documentación de GAIA AIR, siguiendo el marco COAFI. Cada plantilla está diseñada para un propósito específico (p. ej., Overviews, Specifications, Analyses, etc.) y busca fomentar la consistencia y la trazabilidad de la información.

---

## 1. Objetivo

1. **Unificar** el formato de los documentos para evitar confusiones y redundancias.
2. **Facilitar** la elaboración de nuevos documentos sin partir de cero.
3. **Asegurar** que todos los metadatos relevantes (autor, fecha, código COAFI, estado) estén presentes.

---

## 2. Estructura de las Plantillas

1. **Cabecera de Metadatos**  
   - Formato de encabezado con información sobre autor, fecha, revisión, etc.
2. **Secciones Mínimas**  
   - Objetivo, Alcance, Contenido principal, Conclusiones.
3. **Secciones Opcionales**  
   - Dependiendo del tipo de documento (p. ej., Test Procedure, Maintenance).

---

### Plantillas Disponibles (Available Templates)

The following document templates are available to ensure consistency across COAFI documentation:

*   **Overview Document Template (OV)**
    *   **Document Type Code:** `OV`
    *   **Description:**  Use this template for creating high-level overview documents for systems, subsystems, processes, or project areas. Provides a general introduction and summary.
    *   [Overview Document Template (OV)](OV-Template.md)  *(Link to OV-Template.md file)*

*   **Specification Document Template (SP)**
    *   **Document Type Code:** `SP`
    *   **Description:** Use this template for creating detailed technical specifications for components, systems, materials, or performance requirements.
    *   [Specification Document Template (SP)](SP-Template.md) *(Link to SP-Template.md file)*

*   **Test Procedure Template (TE)**
    *   **Document Type Code:** `TE`
    *   **Description:** Use this template for documenting test procedures, test setups, and data collection methods for verification and validation activities.
    *   [Test Procedure Template (TE)](TE-Template.md) *(Link to TE-Template.md file)*

*   ... *(List other templates: MA, AN, DG, IP, etc.)* ...

---

## 4. Cómo Usar las Plantillas

1. **Copiar el Archivo**  
   - Seleccionar la plantilla adecuada y copiarla a un nuevo `.md` con el **código COAFI** asignado.
2. **Completar Metadatos**  
   - Añadir autor, fecha, estado (Draft, In Review, Approved), y el número de versión.
3. **Desarrollar Contenido**  
   - Rellenar cada sección según la estructura sugerida. Elimina las secciones no relevantes o añade campos extra si es necesario.
4. **Revisión & Pull Request**  
   - Sube el nuevo documento a la rama correspondiente, asigna revisores y espera la aprobación.
5. **Enlazar en Índices**  
   - Agregar un enlace en el `index.md` correspondiente (p. ej., `PartII/Airframe/index.md` si es sobre estructuras).

---

## 5. Referencias Cruzadas

- [../index.md](../index.md) (índice principal de `DocumentationManagement/`)
- [../../VersionControl/](../../VersionControl/) (definición de estrategias de ramas y merges)
- [../../README.md](../../README.md) (visión general de Part XI)

---

### Conclusión

Este índice de plantillas es fundamental para mantener una **coherencia editorial** en GAIA AIR, asegurando que todos los documentos cumplan con el estándar de calidad y organización definido en el COAFI. Mantenerlo actualizado y al día con nuevas plantillas (o revisiones de las existentes) es una labor continua que beneficia a todo el proyecto.


