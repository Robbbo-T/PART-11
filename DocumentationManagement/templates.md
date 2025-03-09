# PartXI/DocumentationManagement/Templates — Índice de Plantillas

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

## 3. Plantillas Disponibles

1. **OV (Overview)**  
   - Archivo: `template_OV.md` (ejemplo de documento de visión general).
   - Uso: Proporcionar un panorama amplio de un subsistema, tema o parte.

2. **SP (Specification)**  
   - Archivo: `template_SP.md` (requisitos y características técnicas).
   - Uso: Detallar especificaciones y criterios de aceptación.

3. **AN (Analysis)**  
   - Archivo: `template_AN.md` (análisis de cargas, estudios de fatiga, etc.).
   - Uso: Presentar metodologías, resultados e interpretaciones técnicas.

4. **MA (Maintenance)**  
   - Archivo: `template_MA.md` (procedimientos de mantenimiento e inspección).
   - Uso: Describir rutinas de revisión, intervalos, y pasos de reparación.

5. **TE (Test Procedure)**  
   - Archivo: `template_TE.md` (protocolo de pruebas y ensayos).
   - Uso: Explicar métodos de test, equipamiento, criterios de aprobación, registro de resultados.

*(Estos nombres y categorías son orientativos. Ajustar o ampliar conforme a las necesidades de GAIA AIR.)*

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


