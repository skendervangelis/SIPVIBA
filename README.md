# 🚀 SipViba Print & Design Studio

![SipViba Preview](https://via.placeholder.com/1200x630/0B0F19/00E5FF?text=SipViba+Print+%26+Design+Studio)

> Un ecosistema web de alto rendimiento y diseño *Premium Agency* para un estudio de impresión, diseño y señalética en la Ciudad de México. Desarrollado con el ecosistema de **Astro** y **TailwindCSS**.

## 🎨 Filosofía de Diseño: Glassmorphism Neón
El proyecto está conceptualizado como un lienzo fotográfico oscuro, inspirado en interfaces de alta tecnología y laboratorios creativos.
- **Micro-interacciones completas:** Cursor personalizado reactivo magnéticamente a los elementos (Gota de tinta + Guía de registro de impresión).
- **Glassmorphism avanzado:** Componentes suspendidos con `backdrop-blur` que logran efectos de espejo y cristal sobre videos e imágenes de alto contraste.
- **Luz fluida (Plasma):** Efectos dinámicos en el fondo estilo "Aurora Boreal" renderizados puramente en CSS.

## ⚡ Performance "Zero-JS"
Esta aplicación utiliza el patrón **Island Architecture** de Astro para reducir drásticamente el peso del JavaScript.
- **Puntaje estimado Lighthouse:** 98 - 100
- Todo el HTML se renderiza en el servidor (SSG), lo que permite tiempos de carga milisegundos.
- Se ha aplicado `loading="lazy"` y `decoding="async"` a todas las imágenes "below the fold".

## 🔎 SEO Localizado (Search Engine Optimization)
Diseñado para dominar la búsqueda local en Google (CDMX).
- **JSON-LD Schema (LocalBusiness):** La meta-estructura detalla los servicios exactos de impresión y rotulación.
- **Tarjetas Sociales (Open Graph & Twitter Cards):** Al compartir el sitio, la previsualización es limpia, atractiva y coherente en cualquier plataforma de chat o red social.

## 🛠️ Stack Tecnológico
- **Framework:** [Astro](https://astro.build/) (v4.x)
- **Estilos:** [Tailwind CSS](https://tailwindcss.com/)
- **Animaciones:** CSS Keyframes personalizados y JS vainilla ultra-ligero para cursores e intersecciones (`IntersectionObserver`).
- **Accesibilidad (a11y):** Semántica de árbol perfecta y ocultación activa de adornos para lectores de pantalla.

---

## 💻 Desarrollo Local

Para inicializar este proyecto en tu entorno local:

1. Clona el repositorio
```bash
git clone https://github.com/tu-usuario/sipviba.git
cd sipviba
```

2. Instala las dependencias
```bash
npm install
```

3. Levanta el servidor de desarrollo local
```bash
npm run dev
```
La aplicación estará disponible en `http://localhost:4321`.

## 📦 Comandos Disponibles

| Comando | Acción |
| :--- | :--- |
| `npm install` | Instala todas las dependencias |
| `npm run dev` | Inicia un servidor de desarrollo local `localhost:4321` |
| `npm run build` | Compila el sitio para producción en la carpeta `dist/` |
| `npm run preview` | Previsualiza el proyecto compilado antes de mandarlo a producción |

---

*Diseñado y desarrollado para brillar en un portafolio Frontend.*
