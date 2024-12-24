# inf-roadmap
Un pequeño proyecto base para la sección del roadmap

---
## **Ideas Generales**

### **1. Funcionalidades Básicas del Roadmap**

#### **1.1. Gestión de Nodos**
Los nodos en el roadmap representan secciones o áreas del conocimiento que pueden incluir los siguientes elementos:

##### **1.1.1. Crear Nodos Personalizados**
- **Título del Nodo:** Nombre del tema o subtema dentro de la especialización.
- **Descripción Breve:** Un resumen conciso que explica el objetivo del nodo o de la sección.
- **Etiquetas/Categorías:** Posibilidad de asignar etiquetas para clasificar el nodo en temas como: “Algoritmos”, “Bases de Datos”, “Desarrollo Web”, etc.
- **Enlaces a Recursos Relacionados:**
  - **Artículos:** Enlaces a publicaciones académicas, blogs, tutoriales, etc.
  - **Videos:** Videos educativos, conferencias o tutoriales.
  - **Documentación:** Enlaces a manuales o recursos más extensos.
  - **Imágenes:** Diagramas, ilustraciones, o gráficos que ayudan a entender el tema.
  - **Código:** Repositorios de GitHub u otros enlaces a ejemplos de código relacionados.
- **Referencias Internas:** Sección donde se pueden añadir referencias específicas de la universidad, como:
  - **Cursos:** Cursos relevantes ofrecidos por la universidad para ese nodo.
  - **Profesores:** Incluir nombres y perfiles de profesores que impartan clases relacionadas con el nodo o que sean expertos en el tema.
  - **Tareas o Proyectos:** Proyectos o asignaciones que se relacionen con el nodo (por ejemplo, proyectos finales, investigaciones, etc.).
- **Referencias Externas:**
  - **Local (Latam/país):** Referencias a otras universidades de la región (por ejemplo, cursos, programas o iniciativas académicas).
  - **Global (Internacional):** Referencias a universidades o recursos globales que pueden ser relevantes (cursos, conferencias, programas de intercambio, etc.).

##### **1.1.2. Editar Nodos Existentes**
- **Modificar Título y Descripción:** Posibilidad de actualizar la información general del nodo.
- **Añadir/Eliminar Recursos:** Los usuarios pueden agregar o quitar enlaces a artículos, videos, o imágenes.
- **Actualizar Referencias:** Posibilidad de actualizar las referencias internas (nuevos cursos, profesores) y las externas (actualización de recursos internacionales o locales).

##### **1.1.3. Eliminar Nodos**
- **Eliminar un Nodo:** La opción de borrar un nodo, con una confirmación previa para evitar eliminaciones accidentales.
- **Impacto en el Grafo:** Al eliminar un nodo, se ajustan las relaciones de dependencia entre otros nodos que pudieran verse afectados.

---

#### **1.2. Gestión de Relaciones**
Las relaciones entre los nodos permiten representar cómo se conectan o dependen entre sí, lo que facilita una visión más estructurada y completa del roadmap.

##### **1.2.1. Crear Relaciones (Aristas) Entre Nodos**
- **Dependencias:**
  - Relacionar nodos que deben completarse en un orden específico (por ejemplo, “Algoritmos” debe completarse antes de “Estructuras de Datos”).
  - Visualizar el flujo lógico de aprendizaje o especialización.
- **Relación Conceptual:**
  - Conectar nodos que están relacionados temáticamente, aunque no sea necesario completarlos en un orden secuencial.
  - Permitir múltiples relaciones entre nodos para representar conexiones interdisciplinarias o complementarias.
- **Dirección y Peso de las Aristas (? - por definir)**
- **Resaltar Relaciones:** Los usuarios pueden ver claramente las relaciones de dependencia o conexión entre nodos mediante colores, estilos de línea, o diferentes grosores.

##### **1.2.2. Editar Relaciones Existentes**
- **Modificar Dependencias o Relaciones Conceptuales:** Cambiar la dirección o peso de una relación.
- **Eliminar Relaciones:** Los usuarios pueden borrar relaciones que ya no sean necesarias.

---

#### **1.3. Visualización del Grafo**
La representación visual del roadmap debe ser dinámica e intuitiva para facilitar la navegación y el análisis de la especialización.

##### **1.3.1. Visualización Interactiva del Grafo**
- **Nodos y Relaciones:** Mostrar todos los nodos interconectados por las relaciones de dependencia y conexión conceptual.
- **Zoom y Panorámica:** Permitir al usuario hacer zoom in/out y mover el grafo para explorar distintas áreas del roadmap.
- **Modos de Visualización:**
  - **Modo de Dependencia:** Mostrar el grafo enfocándose en las relaciones de dependencia entre nodos.
  - **Modo Conceptual:** Visualizar las conexiones conceptuales entre nodos, sin priorizar dependencias secuenciales.
  - **Modo Popularidad:** Mostrar los nodos más populares según las reacciones o visitas.

##### **1.3.2. Filtros y Búsqueda Avanzada**
- **Filtrar por Categorías o Etiquetas:** Filtrar nodos según su tema, categoría o etiqueta.
- **Filtrar por Nivel de Complejidad:** Mostrar nodos según su nivel (básico, intermedio, avanzado).
- **Búsqueda de Nodos:** Buscar nodos por nombre, etiqueta o palabra clave.
- **Resaltar Nodos Completados:** Los usuarios registrados pueden resaltar nodos que han completado, proporcionando una visión clara de su progreso.

##### **1.3.3. Interacción con el Grafo**
- **Reacciones en Nodos:** Los usuarios pueden interactuar con los nodos (e.g., "Me gusta", "Interesante", "Lo he completado").
- **Nodos Populares:** Los nodos más comentados o con más reacciones pueden destacarse visualmente en el grafo.
- **Visualización de Progresos de los Usuarios:** Permitir a los usuarios visualizar el progreso de otros usuarios en el roadmap.

---

### **2. Interacción**
#### **2.1. Sin autenticación (usuarios no registrados)**
- Visualizar el roadmap completo y navegar por los nodos y relaciones.
- Acceso público al contenido relacionado de los nodos (enlaces, descripción).

#### **2.2. Con autenticación (usuarios registrados)**
- **Reacciones a nodos:**
  - Agregar reacciones predefinidas (e.g., “Me gusta”, “Interesante”, “Lo he completado”).
  - Visualizar un contador de reacciones por tipo.
- Personalización de vistas (e.g., marcar nodos completados en su propio perfil).

#### **2.3. Sistema de Login Simple**
- Registro/inicio de sesión por:
  - Usuario y contraseña.
  - Integración con redes sociales (Google, GitHub) (por definir).

---

### **3. Herramientas Administrativas**
#### **3.1. Gestión del Roadmap**
- Crear, editar y eliminar nodos o relaciones desde una interfaz administrativa.
- Gestión de categorías y etiquetas para organizar los nodos.

#### **3.2. Análisis y Estadísticas**
- Seguimiento de popularidad por nodo:
  - Número de visitas.
  - Número de reacciones.
  - Progresión de los usuarios (nodos más completados).
- Exportación de datos del roadmap (JSON, CSV, etc.) para análisis externo.

---

### **4. Escalabilidad y Comunidad**
#### **4.1. Escalabilidad del Roadmap**
- Posibilidad de añadir múltiples roadmaps (e.g., diferentes especializaciones o temas dentro de la informática).
- Navegación entre roadmaps.

#### **4.2. Comunidad**
- Foro o sección de comentarios para discutir sobre nodos específicos.
- Función de compartir nodos específicos en redes sociales.

---

# Referencias
- https://roadmap.sh/
- https://github.com/apeman/awesome_computer_science
- https://github.com/ossu/computer-science
- https://bulletin.sfsu.edu/colleges/science-engineering/computer-science/bs-computer-science/roadmap-i-ii-eng/

![image](https://github.com/user-attachments/assets/bd8482f7-0e4b-44c3-a6e3-be3b894b40ff)

