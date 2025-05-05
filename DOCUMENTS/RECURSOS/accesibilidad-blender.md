# Guía de accesibilidad para Blender: Adaptaciones para alumnado con discapacidad visual

Esta guía proporciona instrucciones detalladas para adaptar la interfaz de Blender a las necesidades de estudiantes con discapacidad visual, basándose en las posibilidades actuales del software.

![Captura de pantalla 2025-05-02 a les 18.45.26](/Users/jorgemuyo/Library/Application Support/typora-user-images/Captura de pantalla 2025-05-02 a les 18.45.26.png)

## 1. Configuración inicial de la interfaz

### 1.1 Aumento de escala y mejora de contraste

1. **Aumentar la escala de resolución:**
   - Abrir el menú: **Edit → Preferences**
   - Seleccionar la sección **Interface**
   - Aumentar el **Resolution Scale** hasta un valor entre 1.5 y 3.0 según las necesidades del estudiante
   - Activar la opción **Line Width: Thick** para mejorar la visibilidad de las líneas y contornos

2. **Cambiar el tema para mejorar el contraste:**
   - En Preferences, ir a la sección **Themes**
   - Seleccionar "Blender Light" para un tema de fondo claro con texto oscuro
   - Alternativamente, instalar el tema "Print-Friendly Theme" que está diseñado específicamente para mejorar la legibilidad

3. **Personalizar colores específicos:**
   - En la sección Themes, personalizar los colores de elementos específicos según las necesidades del estudiante
   - Aumentar el contraste entre texto y fondo
   - Hacer más visibles los elementos seleccionados con colores brillantes

### 1.2 Configuración de fuentes

1. **Cambiar el tipo de fuente:**
   - En Preferences → Interface → Font
   - Seleccionar una fuente de alta legibilidad (como Arial, Verdana o una específica para dislexia)
   - Ajustar el tamaño de la fuente según sea necesario

## 2. Optimización del espacio de trabajo

### 2.1 Creación de un espacio de trabajo simplificado

1. **Eliminar áreas innecesarias:**
   - Mantener solo las áreas esenciales: 3D Viewport, Properties y Outliner
   - Organizar estas áreas en secciones grandes y bien definidas

2. **Guardar espacio de trabajo personalizado:**
   - Configurar una distribución óptima
   - Guardar como espacio de trabajo personalizado con nombre descriptivo
   - Establecer como predeterminado: **File → Defaults → Save Startup File**

### 2.2 Técnicas de maximización de visualización

1. **Uso de modo pantalla completa para cada editor:**
   - Enseñar el atajo **Ctrl+Espacio** para alternar el modo de pantalla completa en el área bajo el cursor
   - Utilizar **Ctrl+Alt+Espacio** para pantalla completa sin menús asociados
   - **Shift+F5** para cambiar al Viewport 3D, **Shift+F7** para Properties, **Shift+F9** para Outliner

2. **Reducción de elementos distractores:**
   - Usar tecla **T** para mostrar/ocultar la barra de herramientas lateral
   - Usar tecla **N** para mostrar/ocultar el panel de propiedades
   - Desactivar los gizmos de navegación con **Ctrl+`** o desde el menú desplegable
   - Desactivar el suelo de cuadrícula desde "Show Overlays" si resulta distractivo

## 3. Navegación eficiente mediante atajos de teclado

### 3.1 Configuración del menú de búsqueda rápida

1. **Configurar la barra espaciadora para búsqueda:**
   - En Preferences → Keymap
   - Cambiar la función de **Spacebar** a **Search**
   - Esto permite acceder rápidamente a cualquier función escribiendo parte de su nombre

2. **Lista de atajos esenciales:**
   - **Tab**: Alternar entre modo objeto y modo edición
   - **G, R, S**: Mover, rotar y escalar
   - **Shift+A**: Menú para añadir objetos
   - **F3**: Búsqueda de comandos (alternativa al espacio configurado para búsqueda)
   - **Numpad 1, 3, 7**: Vistas frontal, lateral y superior
   - **Numpad 0**: Vista de cámara
   - **Numpad 5**: Alternar entre vista perspectiva y ortográfica

### 3.2 Navegación mediante teclado numérico

Crear una lista impresa de comandos del teclado numérico para facilitar la navegación en la vista 3D:
- **Numpad .**: Centrar vista en objeto seleccionado
- **Numpad +/-**: Acercar/alejar
- **Numpad 2/4/6/8**: Rotación de vista (alternativa al ratón)

## 4. Estrategias didácticas de apoyo

### 4.1 Enfoque por fases

1. **Introducción progresiva:**
   - Comenzar con un subconjunto pequeño de herramientas
   - Añadir gradualmente más funcionalidades conforme aumente la confianza
   - Crear hojas de referencia impresas con alto contraste

2. **Trabajo colaborativo:**
   - Considerar el sistema de compañero de apoyo para ciertas tareas
   - Fomentar la exploración verbal del modelo 3D

### 4.2 Materiales de apoyo

1. **Crear guiones detallados:**
   - Desarrollar tutoriales paso a paso con capturas de pantalla ampliadas
   - Incluir descripciones textuales precisas de las ubicaciones de los elementos UI

2. **Utilizar modelos físicos complementarios:**
   - Cuando sea posible, proporcionar modelos físicos táctiles para complementar el trabajo digital
   - Permitir que el estudiante explore formas tridimensionales con las manos para mejorar la comprensión espacial

## 5. Consideraciones adicionales

### 5.1 Hardware complementario

- Considerar monitores de mayor tamaño o resolución
- Evaluar la posibilidad de usar tabletas gráficas (que permiten entrada más táctil)
- Ratones con configuración de sensibilidad personalizada

### 5.2 Software complementario

- Explorar la posibilidad de usar software de magnificación de pantalla del sistema operativo
- Integrar con lectores de pantalla cuando sea posible (actualmente limitado en Blender)
- Considerar el uso de complementos de Blender que puedan simplificar ciertas tareas

---

## Recursos adicionales

- [Enlace al tema "Print-Friendly Theme" para Blender](https://extensions.blender.org/themes/theme-print-friendly/)
- [Foro de la comunidad Blender para consultas sobre accesibilidad](https://www.blender.org/community/)
- [Sitio oficial de documentación de Blender, sección "User Interface"](https://docs.blender.org/manual/en/latest/interface/index.html)
