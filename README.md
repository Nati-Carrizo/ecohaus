[README.md](https://github.com/user-attachments/files/28613036/README.md)
# EcoHaus — Landing Page

Sitio web institucional de **EcoHaus**, estudio de arquitectura y construcción especializado en eficiencia, con sede en Mar del Plata, Argentina.

> Construir una casa energéticamente eficiente no debería restarte energía.

---

## Acerca de EcoHaus

EcoHaus diseña y construye hogares, casas vacacionales y complejos turísticos con foco en la eficiencia energética y la integración al entorno costero. Trabaja con el sistema constructivo de **paneles SIP** (Structural Insulated Panels) y ofrece una solución integral llamada **Sistema A+**, que cubre todas las etapas del proceso: desde el diagnóstico del terreno hasta la entrega final de obra.

- **Instagram:** [@ecohausmdq](https://instagram.com/ecohausmdq)
- **WhatsApp:** [+54 9 223 306 0322](https://wa.me/5492233060322)
- **Ubicación:** Mar del Plata, Buenos Aires, Argentina

---

## Sobre este sitio

Una landing page de una sola página (single-page) construida con HTML, CSS y JavaScript puro, sin frameworks ni dependencias de build. Está optimizada para presentar la propuesta de valor del estudio y derivar consultas al canal principal de comunicación: WhatsApp.

### Secciones

1. **Hero** — Encabezado con logo, propuesta de valor y CTA principal.
2. **Nuestro Compromiso** — Tres tarjetas que describen la forma de trabajar.
3. **Sistema A+** — Las diez etapas del proceso integral.
4. **Construcción con Paneles SIP** — Tecnología constructiva, cinco ventajas y galería de obras.
5. **Contacto** — CTA a WhatsApp con datos de contacto.

### Características

- Diseño responsive (móvil, tablet, escritorio)
- Tipografía Futura con fallback a Jost (Google Fonts)
- Animaciones de aparición al hacer scroll
- Botón flotante de WhatsApp con mensaje pre-escrito
- Imágenes optimizadas en formato WebP y JPG
- Sin dependencias externas ni proceso de build

---

## Estructura del proyecto

```
ecohaus-landing/
├── index.html                  Sitio completo (HTML, CSS y JS en un solo archivo)
├── ecohaus-logo.jpg            Logo del estudio
├── obra-01.webp                Foto de cocina
├── obra-02.webp                Foto de living
├── obra-03.webp                Foto de fachada lateral
├── obra-04-panoramica.jpg      Foto panorámica de fachada
├── obra-05-sip.jpg             Foto de obra en construcción con sistema SIP
├── textos-ecohaus-editables.docx   Documento con todos los textos del sitio
├── GUIA-INSTALACION.md         Guía paso a paso de instalación y despliegue
└── README.md                   Este archivo
```

---

## Instalación local

### Opción rápida

Abrí `index.html` haciendo doble clic. Funciona para previsualizar.

### Opción recomendada (servidor local con Python)

```bash
cd ecohaus-landing
python3 -m http.server 8000
```

Abrí el navegador en `http://localhost:8000`.

### Con Visual Studio Code

Instalá la extensión **Live Server**, abrí la carpeta en VS Code, hacé clic derecho sobre `index.html` y elegí **Open with Live Server**.

> Para instrucciones más detalladas, consultá `GUIA-INSTALACION.md`.

---

## Despliegue en Vercel

### Camino 1: Vercel + GitHub (recomendado)

1. Crear un repositorio en GitHub y subir todos los archivos.
2. Crear una cuenta en [Vercel](https://vercel.com) e iniciar sesión con GitHub.
3. En el panel de Vercel: **Add New → Project**, seleccionar el repositorio.
4. Dejar todas las opciones por defecto y hacer clic en **Deploy**.

Vercel asigna automáticamente una URL del tipo `https://ecohaus-landing.vercel.app`.

### Camino 2: CLI de Vercel

```bash
npm install -g vercel
cd ecohaus-landing
vercel --prod
```

> La guía completa, con capturas conceptuales y resolución de problemas, está en `GUIA-INSTALACION.md`.

---

## Edición de contenidos

Todo el contenido del sitio (textos, títulos, descripciones) está disponible en el archivo `textos-ecohaus-editables.docx`. Recomendamos:

1. Editar el documento en Word, Google Docs o LibreOffice.
2. Mantener un largo similar al original para conservar el equilibrio visual.
3. Enviar el documento editado y aplicar los cambios al `index.html`.

### Reemplazo de imágenes

Para reemplazar una imagen, guardá la nueva foto con el mismo nombre de archivo que la anterior y subila al repositorio. El sitio la usará automáticamente.

| Archivo | Ubicación en el sitio |
|---|---|
| `ecohaus-logo.jpg` | Logo en navegación, hero y footer |
| `obra-04-panoramica.jpg` | Fondo del Hero y de la sección Contacto |
| `obra-05-sip.jpg` | Imagen principal de la sección Paneles SIP |
| `obra-03.webp` | Primera imagen de la galería SIP |
| `obra-02.webp` | Segunda imagen de la galería SIP |
| `obra-01.webp` | Tercera imagen de la galería SIP |

### Cambiar el número de WhatsApp

En `index.html`, reemplazar todas las apariciones de `5492233060322` por el nuevo número (formato internacional, sin signo `+` ni espacios). Aparece en:

- Botón principal de WhatsApp en la sección de contacto
- Botón flotante de WhatsApp (esquina inferior derecha)
- Enlace en la sección de datos de contacto

---

## Stack técnico

- **HTML5** semántico
- **CSS3** con variables custom, grid y flexbox
- **JavaScript** vanilla (Intersection Observer para animaciones)
- **Google Fonts** — Jost (fallback de Futura)
- **Sin frameworks, sin build, sin dependencias**

### Compatibilidad

Probado en versiones recientes de Chrome, Firefox, Safari y Edge. Compatible con dispositivos móviles iOS y Android.

---

## Próximas mejoras posibles

- Formulario de contacto con envío por correo
- Sección de testimonios de clientes
- Página detallada de proyectos realizados
- Integración con Google Analytics
- Open Graph y Twitter Cards para compartir en redes
- Dominio propio (ej. `ecohausmdq.com.ar`)

---

## Créditos

- **Cliente:** EcoHaus — Estudio de arquitectura y construcción
- **Logo y fotografías:** Propiedad de EcoHaus
- **Tipografía:** [Jost](https://fonts.google.com/specimen/Jost) (Google Fonts), alternativa libre a Futura

---

## Licencia

Todo el contenido (textos, imágenes, logo, fotografías) es propiedad de EcoHaus. El código del sitio fue desarrollado a medida para este proyecto.

© 2026 EcoHaus · Hogares Eficientes
