# Zero - Kit Digital Astro

Proyecto base para lanzar tu negocio online con Astro 5.9.3 y Tailwind CSS 4. Incluye estructura modular, componentes reutilizables y estilos personalizados.

## 🚀 Características

- **Astro 5.9.3**: Framework moderno para sitios rápidos y optimizados.
- **Tailwind CSS 4**: Utilidad para estilos rápidos y personalizables.
- **Componentes modulares**: Navbar, Hero, Servicios, Beneficios, Contacto y Footer.
- **Colores y fuentes personalizadas**.
- **SEO y metadatos sociales listos**.
- **Responsive y optimizado para móviles**.

## 📦 Estructura del proyecto
src/ components/ Navbar.astro HeroSection.astro ServicesSection.astro ServiceCard.astro BenefitsSection.astro BenefitItem.astro ContactSection.astro Footer.astro layouts/ Layout.astro pages/ index.astro styles/ global.css public/ (archivos estáticos e imágenes)


## 🛠️ Instalación

1. Clona el repositorio:
   ```bash
   git clone <url-del-repo>
   cd Zero

### Instala dependencias:
```npm install
#### Inicia el servidor de desarrollo:
``` npm run dev
Abre http://localhost:4321 en tu navegador.

🖌️ Personalización
Colores y fuentes: Edita src/styles/global.css para cambiar colores y tipografías.
Contenido: Modifica los archivos en src/components/ y src/pages/index.astro para adaptar textos, imágenes y enlaces.
SEO: Ajusta los metadatos en src/layouts/BaseLayout.astro.

🏗️ Estructura de componentes
Navbar.astro: Menú de navegación.
HeroSection.astro: Sección principal de bienvenida.
ServicesSection.astro y ServiceCard.astro: Servicios ofrecidos.
BenefitsSection.astro y BenefitItem.astro: Beneficios destacados.
ContactSection.astro: Llamada a la acción y contacto por WhatsApp.
Footer.astro: Pie de página.

🧑‍💻 Desarrollo
Estilos: Usa clases de Tailwind para personalizar rápidamente.
Props: Los componentes aceptan props para mayor flexibilidad.
Imágenes: Coloca imágenes en public/ o usa URLs externas.

📝 Notas
Si modificas los colores en global.css, asegúrate de usar las clases de Tailwind (bg-primary, bg-secondary, etc.) en tus componentes.
No se utiliza DaisyUI por defecto para evitar conflictos de colores.
Compatible con despliegue en Vercel, Netlify, etc.

📄 Licencia
Este proyecto es para uso puramente personal. No está permitido su uso comercial, redistribución ni publicación como propio.

Hecho con ❤️ usando Astro y Tailwind CSS.
