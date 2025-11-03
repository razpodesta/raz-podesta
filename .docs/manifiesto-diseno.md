Manifiesto de Diseño: El Ecosistema "raz-podesta-blog"
Filosofía: "Contenido Soberano, Experiencia Fluida". El diseño debe servir al contenido, haciéndolo accesible y agradable de consumir. Creamos un sistema modular, adaptable y con personalidad, donde cada elemento tiene un propósito claro y contribuye a una experiencia de usuario serena y enfocada, tanto en la claridad del día como en la calma de la noche.
I. Fundamentos del Sistema (Átomos)
Estos son los bloques de construcción indivisibles de nuestra UI.
Paleta de Colores (Dualidad Dinámica):
Modo Claro:
Fondo Principal: #FFFFFF (Blanco puro)
Fondo Secundario: #F9FAFB (Gris muy claro para acentos sutiles)
Texto Primario: #111827 (Negro profundo)
Texto Secundario: #6B7280 (Gris medio)
Acento Primario: Un azul vibrante, ej. #3B82F6 (para enlaces, botones y categorías)
Acento Secundario: Un color cálido, ej. #F59E0B (para tags especiales o notificaciones)
Modo Oscuro:
Fondo Principal: #111827 (El negro del modo claro se convierte en el fondo principal)
Fondo Secundario: #1F2937 (Gris oscuro para elevar elementos como las tarjetas)
Texto Primario: #F9FAFB (El gris claro del modo claro es ahora el texto principal)
Texto Secundario: #9CA3AF (Gris más suave)
Acento Primario: El mismo azul vibrante #3B82F6 para consistencia.
Acento Secundario: El mismo color cálido #F59E0B.
Tipografía (Jerarquía Clara):
Fuente para Títulos (font-headings): Una fuente con carácter pero legible, como Poppins o Lora (Serif para un toque elegante).
Fuente para Cuerpo (font-body): Una fuente sans-serif altamente legible, como Inter o Roboto.
Jerarquía: Títulos (h1-h6), Párrafos, Metadatos (fecha, tiempo de lectura), Enlaces.
Iconografía (Sistema Minimalista):
Utilizaremos un set consistente como Heroicons o Lucide Icons.
Íconos clave: Sol/Luna (theme toggle), Lupa (búsqueda), Redes Sociales (Twitter, GitHub, LinkedIn), Sobre (newsletter), Menú (móvil).
Espaciado e Interfaz:
Sistema basado en múltiplos de 4 u 8px para un ritmo vertical consistente.
Bordes sutilmente redondeados (rounded-lg) en tarjetas e imágenes para una apariencia suave.
II. Componentes Reutilizables (Moléculas y Organismos)
Estos son los componentes funcionales que el usuario verá y con los que interactuará.
Header (El Ancla de Navegación)
Propósito: Proveer identidad y acceso a las secciones principales del blog.
Elementos:
Logo: Tu logo "raz-podesta".
NavLinks: Enlaces de navegación con un sutil indicador de página activa.
NavDropdown: Para agrupar sub-secciones como "Archivo".
ActionIcons: Un grupo de íconos que incluye ThemeToggle y SearchTrigger.
Innovación: El header tendrá un fondo semitransparente con efecto blur al hacer scroll, manteniéndose visible sin ser intrusivo.
Hero (La Declaración de Intenciones)
Propósito: Capturar la atención y presentar al autor.
Elementos:
Headline: "Hola, soy [Tu Nombre]".
Bio: Tu descripción como profesional.
Avatar: Tu foto, con un borde degradado sutil o formas abstractas animadas de fondo.
Innovación: Las formas abstractas de fondo se animarán sutilmente al mover el mouse, creando una sensación de profundidad y dinamismo.
PostCard (La Puerta de Entrada al Conocimiento)
Propósito: Presentar un resumen atractivo de cada artículo en los listados.
Elementos:
FeaturedImage: Imagen principal con efecto de zoom sutil al pasar el cursor.
CategoryBadge: Etiqueta de categoría con color de acento.
PostTitle: Título del post.
Excerpt: Resumen corto del contenido.
PostMeta: Agrupa PublishDate y ReadingTime.
Innovación: Al hacer hover, la tarjeta se elevará ligeramente con una sombra más pronunciada (efecto lift), invitando al clic.
NewsletterForm (El Puente hacia la Comunidad)
Propósito: Capturar suscriptores para el boletín.
Elementos:
Title y Subtitle.
InputFields: Campos de texto para nombre y email con validación en tiempo real.
SubmitButton: Botón con micro-interacción en los estados de carga y éxito (ej. muestra un check ✓).
Innovación: En lugar de un ícono estático, podemos usar una animación Lottie ligera para hacerlo más atractivo.
Footer (El Cierre de la Conversación)
Propósito: Ofrecer enlaces secundarios, información de contacto y copyright.
Elementos:
Logo y Tagline.
SocialLinks: Iconos de redes sociales.
LinkColumns: Columnas de enlaces (Navegación, Archivo, Contacto).
Copyright.
Innovación: El footer puede incluir una sección "On this day..." que muestre un post publicado en la misma fecha en años anteriores.
III. Features y Funcionalidades Clave
La inteligencia que une los componentes para crear una experiencia completa.
Theming Claro/Oscuro: Implementado con variables CSS y el selector dark: de Tailwind 4.0. La transición será suave y animada.
Búsqueda Global: Al hacer clic en el SearchTrigger, se abrirá un modal a pantalla completa (Command Palette) donde el usuario podrá buscar artículos por título o contenido.
Sistema de Tags y Autores: Páginas dedicadas que listan todos los posts asociados a una etiqueta o a un autor específico, reutilizando el componente PostCard.
Internacionalización (i18n): La arquitectura de componentes se construirá pensando en la traducción. Los textos se gestionarán desde archivos de localización.
Zona de Comentarios Interactiva:
No es visible en el screenshot, pero es un requisito.
Se creará un componente CommentsSection que se integrará con un servicio como Giscus (basado en GitHub Discussions) o Commento.
Tendrá estados de carga, manejo de errores y un diseño que se alinee con el tema del blog.
Este manifiesto será la "fuente única de verdad" para el desarrollo de la interfaz de raz-podesta-blog, asegurando que cada nueva pieza del rompecabezas encaje perfectamente en el conjunto.

---


