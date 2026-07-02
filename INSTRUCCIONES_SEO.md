# INSTRUCCIONES PARA EL SEO — FERTILITY SOLUTIONS CENTER

---

## CÓMO ESTÁ ARMADO EL SITIO

El sitio web de FSC está construido en HTML/CSS puro (sin WordPress, sin constructores visuales).
Funciona con tres servicios conectados entre sí:

```
GITHUB → NETLIFY → DOMINIO
(archivos)   (publica)   (dirección web)
```

### 1. GITHUB — Donde viven los archivos
**URL:** https://github.com/Corsa1909/FSC-Website

Aquí están todos los archivos HTML, imágenes y PDFs del sitio.
Cuando subes un cambio a GitHub, Netlify lo detecta automáticamente y actualiza el sitio en menos de 1 minuto.

**Acceso:** Solicitar invitación como colaborador a sfertilidad@gmail.com

---

### 2. NETLIFY — Quien publica el sitio
**URL actual:** https://illustrious-monstera-4030c5.netlify.app

Netlify toma los archivos de GitHub y los publica en internet automáticamente.
No necesitas entrar a Netlify para hacer cambios — solo trabajas en GitHub.

---

### 3. DOMINIO — La dirección web
**Dominio:** fertilitysolutionscenter.com (comprado en Wix)

El dominio todavía apunta a Wix. Hay que hacer el cambio de DNS para que apunte a Netlify.
Esto lo coordina el administrador de la cuenta Wix.

---

## CÓMO HACER CAMBIOS AL SITIO

1. Ve a https://github.com/Corsa1909/FSC-Website
2. Encuentra el archivo que quieres editar (ej. FSC_LandingPage.html)
3. Haz clic en el archivo → clic en el ícono del lápiz (editar)
4. Haz tus cambios directamente en el editor de GitHub
5. Baja y haz clic en "Commit changes"
6. Espera 1 minuto → el sitio se actualiza automáticamente

También puedes trabajar localmente con Git y hacer push al repositorio.

---

## PÁGINAS DEL SITIO

| Archivo | Página |
|--------|--------|
| FSC_LandingPage.html | Inicio / Home |
| FSC_About.html | Nosotros |
| FSC_Programs.html | Programas y costos |
| FSC_Testimonials.html | Testimoniales |
| FSC_Blog.html | Blog (índice) |
| FSC_Blog_Amparo.html | Blog: El proceso Amparo |
| FSC_Blog_Surrogacy_Mexico.html | Blog: Subrogación en México |
| FSC_Blog_Single_Dads.html | Blog: Padres solteros |
| FSC_Contact.html | Contacto |
| FSC_WhyFamilies.html | Por qué elegirnos |
| FSC_Amparo.html | El proceso Amparo (página completa) |
| FSC_HIV.html | Programas VIH |
| FSC_Magazine.html | Recursos / Revista |
| FSC_GP.html | Propuesta Guaranteed (privada, no indexar) |
| FSC_FET.html | Propuesta FET (privada, no indexar) |

---

## PRIORIDADES DE TRABAJO

### URGENTE — Semana 1
- [ ] Hacer el sitio responsivo para móvil (media queries en todas las páginas)
- [ ] Crear `sitemap.xml` y subirlo a GitHub
- [ ] Crear `robots.txt` (excluir FSC_GP.html y FSC_FET.html)
- [ ] Agregar Open Graph tags en todas las páginas (og:title, og:description, og:image)
- [ ] Instalar Google Analytics GA4
- [ ] Registrar en Google Search Console
- [ ] Conectar dominio fertilitysolutionscenter.com a Netlify (cambio de DNS en Wix)

### SEMANA 2-3
- [ ] Agregar Schema markup (LocalBusiness + MedicalBusiness) en FSC_LandingPage.html
- [ ] Optimizar imágenes — convertir JPG/PNG a WebP para mejorar velocidad
- [ ] Conectar formularios a Formspree (reemplazar YOUR_FORM_ID en FSC_Amparo.html y FSC_LandingPage.html)
- [ ] Crear Google Business Profile

### MES 2 EN ADELANTE
- [ ] Publicar nuevos artículos de blog consistentemente
- [ ] Palabras clave objetivo: "surrogacy Mexico", "subrogación Cancún", "gestación subrogada México", "surrogacy agency Mexico", "same sex surrogacy Mexico"
- [ ] Link building en directorios de salud y fertilidad
- [ ] Estrategia de reseñas en Google

---

## COLORES Y ESTILOS DEL SITIO

```css
--purple:  #7B68AE
--purple2: #6657A0
--dark:    #3D2C6E
--navy:    #2D1F5E
--light:   #F4F1FA
--gray:    #F8F7FC
--text:    #2C2C2C
--soft:    #4A4A6A
--muted:   #6B7280
--white:   #FFFFFF
--border:  #E2DCF0
```

Fuente principal: `'Segoe UI', system-ui, -apple-system, sans-serif`

---

## CONTACTO ADMINISTRACIÓN

- **Email:** sfertilidad@gmail.com
- **Sitio actual:** https://illustrious-monstera-4030c5.netlify.app
- **Repositorio:** https://github.com/Corsa1909/FSC-Website
