# Any Nou Xinès amb Barcelona 🏮

## 📋 Descripció del Projecte

**Any Nou Xinès amb Barcelona** és un lloc web oficial dedicat a la celebració de l'Any Nou Xinès a Barcelona. Aquest projecte digital promociona i documenta una de les festivitats culturals més importants de la comunitat xinesa a Catalunya, oferint informació completa sobre tradicions, esdeveniments, galeries fotogràfiques i detalls de contacte per als organitzadors.

### 🎯 Propòsit

El lloc web serveix com a plataforma principal per a:
- Informar sobre la història i tradicions de l'Any Nou Xinès
- Promocionar esdeveniments i activitats a Barcelona
- Documentar mitjançant galeries les celebracions passades
- Facilitar el contacte entre organitzadors i participants
- Crear un pont cultural entre la comunitat xinesa i Barcelona

## ✨ Característiques Principals

### 🌐 **Lloc Multilingüe**
- **Català (CAT)**: Idioma principal
- **Espanyol (ES)**: Idioma secundari
- **Xinès (CN)**: Per a la comunitat xinesa

### 📱 **Disseny Responsiu**
- Optimitzat per a dispositius mòbils, tauletes i escriptori
- Navegació adaptativa amb menú hamburguesa per a mòbils
- Disseny fluid que s'ajusta a qualsevol mida de pantalla

### 🎨 **Experiència Visual Rica**
- Carrusel interactiu d'imatges
- Galeria amb lightbox integrat
- Efectes d'animació i transicions suaus
- Tipografies personalitzades (IvyOra Display i Avenir)
- Paleta de colors inspirada en l'estètica xinesa tradicional

### ⚡ **Funcionalitats Interactives**
- Comptador regressiu dinàmic a l'Any Nou Xinès
- Secció FAQ amb elements expandibles
- Formulari de contacte funcional
- Navegació suau entre seccions
- Efectes de parallax i scroll

## 🗂️ Estructura del Projecte

```
anyNouXines/
├── 📁 assets/                    # Recursos multimèdia
│   ├── 📁 images/               # Imatges del lloc
│   │   ├── 📁 2025/            # Galeria de fotos 2025
│   │   ├── 📁 any.xines/       # Imatges temàtiques
│   │   ├── 📁 button/          # Icones de navegació
│   │   └── 📁 quiSom/          # Logos d'organitzadors
│   └── 📁 typography/          # Fonts personalitzades
│       ├── 📁 Avenir/          # Família tipogràfica Avenir
│       └── 📁 IvyOra display/  # Família tipogràfica IvyOra
├── 📁 css/                     # Fulls d'estil
│   ├── 📄 style.css           # Estils principals
│   ├── 📄 navigation.css      # Navegació
│   ├── 📄 carousel.css        # Carrusel d'imatges
│   ├── 📄 galeria-2025.css    # Galeria de fotos
│   ├── 📄 faq.css            # Preguntes freqüents
│   ├── 📄 contact-form.css    # Formulari de contacte
│   ├── 📄 footer.css         # peu de pàgina
│   ├── 📄 responsive.css     # Estils responsius
│   └── 📄 fixes.css          # Correccions i ajustos
├── 📁 js/                      # Scripts JavaScript
│   ├── 📄 main.js             # Funcionalitat principal
│   ├── 📄 navigation.js       # Navegació
│   ├── 📄 carousel.js         # Carrusel interactiu
│   ├── 📄 galeria-2025.js     # Galeria amb lightbox
│   ├── 📄 language-selector.js # Selector d'idiomes
│   ├── 📄 faq.js             # Interacció FAQ
│   └── 📄 mobile-menu-fix.js  # Menú mòbil
├── 📄 index.html              # Pàgina principal
├── 📄 any-nou-xines.html      # Història i tradicions
├── 📄 galeria-2025.html       # Galeria de fotos 2025
├── 📄 qui-som.html            # Informació organitzadors
├── 📄 404.html                # Pàgina d'error
└── 📄 README.md               # Aquest arxiu
```

## 🛠️ Tecnologies Utilitzades

### **Frontend**
- **HTML5**: Estructura semàntica i accessible
- **CSS3**: Estils moderns amb Flexbox i Grid
- **JavaScript (ES6+)**: Funcionalitat interactiva vanilla
- **Font Awesome 6.0**: Iconografia professional
- **Google Fonts**: Tipografia Noto Sans com a suport

### **Tipografies Personalitzades**
- **IvyOra Display**: Per a títols i elements destacats
- **Avenir**: Per a text de cos i navegació

### **Característiques Tècniques**
- **Responsive Design**: Enfocament mobile-first
- **Progressive Enhancement**: Funcionalitat escalable
- **Accessibility**: Atributs ARIA i navegació per teclat
- **Performance**: Imatges optimitzades i codi eficient
- **SEO**: Meta tags i estructura semàntica

## 🚀 Instal·lació i Configuració

### **Requisits Previs**
- Servidor web local (Apache, Nginx, o similar)
- Navegador web modern (Chrome, Firefox, Safari, Edge)

### **Instal·lació Ràpida**

1. **Clonar o descarregar el projecte**
   ```bash
   git clone [URL_DEL_REPOSITORI]
   cd anyNouXines
   ```

2. **Configurar servidor local**
   
   **Opció A: XAMPP/WAMP/MAMP**
   ```bash
   # Copiar arxius a la carpeta htdocs
   cp -r . /xampp/htdocs/anyNouXines
   ```
   
   **Opció B: Python (servidor simple)**
   ```bash
   python -m http.server 8000
   ```
   
   **Opció C: Node.js (live-server)**
   ```bash
   npx live-server
   ```

3. **Accedir al lloc**
   - Obrir navegador a `http://localhost/anyNouXines` (XAMPP)
   - O `http://localhost:8000` (Python/Node.js)

### **Configuració Personalitzada**

#### **Configuració de Rutes**
Si el lloc es desplega en un subdirectori diferent, actualitzar les rutes a:
- Enllaços de navegació en tots els arxius HTML
- Rutes d'imatges en CSS
- Referències de scripts JavaScript

#### **Personalització de Contingut**
- **Imatges**: Reemplaçar arxius a `/assets/images/`
- **Textos**: Editar directament en arxius HTML
- **Estils**: Modificar variables CSS a `:root` en `style.css`
- **Configuració d'idiomes**: Actualitzar `language-selector.js`

## 📄 Pàgines del Lloc

### **🏠 Pàgina Principal (index.html)**
- **Hero Section**: Missatge de benvinguda amb comptador regressiu
- **Informació Cultural**: Targetes informatives sobre tradicions
- **Carrusel de Moments**: Galeria rotativa d'anys anteriors
- **FAQ**: Preguntes freqüents sobre l'esdeveniment
- **Footer**: Informació de col·laboradors

### **📚 Història de l'Any Nou Xinès (any-nou-xines.html)**
- **Disseny de Scroll Horitzontal**: Navegació cinematogràfica
- **Seccions Narratives**: 
  - Història i origen de la festivitat
  - Llegenda del monstre Nian
  - Tradicions i celebracions modernes
  - Celebració global i a Barcelona
- **Animacions**: Efectes de fade-in en fer scroll
- **Navegació per Seccions**: Botons d'anterior/següent

### **🖼️ Galeria 2025 (galeria-2025.html)**
- **Grid Responsiu**: Layout adaptatiu per a totes les pantalles
- **Lightbox**: Visualització ampliada d'imatges
- **Navegació de Galeria**: Controls d'anterior/següent
- **Lazy Loading**: Càrrega optimitzada d'imatges

### **👥 Qui Som (qui-som.html)**
- **Informació Organitzadors**: Detalls d'entitats promotores
- **Formulari de Contacte**: Sistema de contacte funcional
- **Secció de Patrocinadors**: Grid de logos organitzats per categories
- **Informació de Contacte**: Dades completes de contacte

### **⚠️ Pàgina 404 (404.html)**
- **Missatge d'Error**: Pàgina personalitzada per a enllaços trencats
- **Navegació de Retorn**: Enllaços per tornar al lloc principal

## ⚙️ Funcionalitats Detallades

### **🎠 Sistema de Carrusel**
```javascript
// Carrusel circular amb 5 elements visibles
const VISIBLE = 5;
const HALF = (VISIBLE - 1) / 2;

// Auto-play amb pausa en interacció
let timer = setInterval(next, 2800);
```

### **🖼️ Galeria amb Lightbox**
```javascript
// Sistema de galeria amb navegació per teclat
document.addEventListener('keydown', function(e) {
    if (e.key === 'Escape') closeLightbox();
    if (e.key === 'ArrowLeft') showPreviousImage();
    if (e.key === 'ArrowRight') showNextImage();
});
```

### **📱 Menú Responsiu**
```javascript
// Detecció automàtica de mida de pantalla
function checkScreenSize() {
    if (window.innerWidth <= 768) {
        enableMobileMenu();
    } else {
        enableDesktopMenu();
    }
}
```

### **⏰ Comptador Regressiu**
```javascript
// Càlcul dinàmic fins al proper Any Nou Xinès
function updateCountdown() {
    const currentDate = new Date();
    const chineseNewYearDate = new Date(currentYear, 1, 17);
    const daysDiff = Math.ceil(timeDiff / (1000 * 3600 * 24));
}
```

### **🌐 Selector d'Idiomes**
```javascript
// Sistema de canvi d'idioma sense recàrrega
const languageContent = {
    'cat': { /* contingut en català */ },
    'es': { /* contingut en espanyol */ },
    'cn': { /* contingut en xinès */ }
};
```

## 🎨 Guia d'Estils

### **🎨 Paleta de Colors**
```css
:root {
    --primary-green: #5a7860;      /* Verd principal */
    --secondary-green: #92af83;    /* Verd secundari */
    --light-green: #c5d6c2;       /* Verd clar */
    --white: #ffffff;             /* Blanc pur */
    --text-color: #435947;        /* Color de text */
}
```

### **📱 Breakpoints Responsius**
```css
/* Mobile First */
@media (max-width: 480px)  { /* Mòbils petits */ }
@media (max-width: 768px)  { /* Tauletes i mòbils */ }
@media (max-width: 1024px) { /* Tauletes grans */ }
@media (min-width: 1200px) { /* Escriptori gran */ }
```

### **✨ Animacions i Transicions**
```css
/* Transició global */
--transition: all 0.3s ease;

/* Efecte fade-in */
.fade-in {
    opacity: 0;
    transform: translateY(20px);
    transition: all 0.6s ease;
}

.fade-in.visible {
    opacity: 1;
    transform: translateY(0);
}
```

## 🏢 Organitzadors i Col·laboradors

### **🎭 Organitzat per:**
- **Associació Grupo Artistas Huaxing**
  - Adreça: Passeig Sant Joan, 34, Local - Barcelona
  - Email: hola@anynouxines.barcelona

### **🤝 Amb el suport de:**
- **Institut Confuci de Barcelona**
- **Casa Àsia**
- **Ajuntament de Barcelona**
- **Consolat General de la R.P. Xina**

### **💼 Patrocinadors:**
- **Assessoria del CYM**
- **TeaPanda**
- **Haier**
- I altres col·laboradors locals

## 🔧 Personalització i Desenvolupament

### **🎨 Modificar Estils**
```css
/* Canviar colors principals */
:root {
    --primary-green: #el-teu-color-aquí;
    --secondary-green: #el-teu-color-aquí;
}

/* Canviar tipografies */
:root {
    --title-font: 'La-Teva-Font', serif;
    --body-font: 'La-Teva-Font', sans-serif;
}
```

### **📝 Actualitzar Contingut**
1. **Textos**: Editar directament en arxius HTML
2. **Imatges**: Reemplaçar arxius a `/assets/images/`
3. **Idiomes**: Modificar objectes a `language-selector.js`

### **⚡ Afegir Funcionalitats**
```javascript
// Exemple: Afegir nova secció al carrusel
const newImages = [
    'assets/images/nova-imatge.jpg',
    // ... més imatges
];

// Integrar en el sistema existent
images.push(...newImages);
```

### **📱 Optimitzar Performance**
- **Imatges**: Usar formats WebP quan sigui possible
- **CSS**: Minificar arxius per a producció
- **JavaScript**: Implementar lazy loading addicional
- **Fonts**: Precarregar fonts crítiques

## 🐛 Resolució de Problemes

### **❓ Problemes Comuns**

**P: El menú mòbil no funciona**
```javascript
// Verificar càrrega del script
console.log('Mobile menu script loaded:', typeof initializeMobileMenu);

// Forçar inicialització
document.addEventListener('DOMContentLoaded', initializeMobileMenu);
```

**P: Les imatges no carreguen**
```html
<!-- Verificar rutes relatives -->
<img src="assets/images/imatge.jpg" alt="Descripció">
<!-- En lloc de rutes absolutes -->
```

**P: El comptador no actualitza**
```javascript
// Verificar data de l'Any Nou Xinès
const chineseNewYearDate = new Date(2026, 1, 17); // 17 de febrer 2026
```

**P: Problemes de tipografies**
```css
/* Assegurar fallbacks */
font-family: 'IvyOra Display', 'Georgia', serif;
font-family: 'Avenir', 'Helvetica Neue', Arial, sans-serif;
```

### **🔍 Mode Debug**
```javascript
// Activar logs de debug
const DEBUG = true;
if (DEBUG) console.log('Debug info:', data);
```

## 📱 Compatibilitat

### **🌐 Navegadors Suportats**
- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Opera 57+

### **📱 Dispositius Testejats**
- ✅ iPhone (iOS 12+)
- ✅ Android (8.0+)
- ✅ iPad
- ✅ Tauletes Android
- ✅ Escriptori (Windows/macOS/Linux)

## 🚀 Optimització i Performance

### **⚡ Mètriques de Performance**
- **Temps de càrrega**: < 3 segons
- **Lighthouse Score**: > 90
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s

### **🔧 Optimitzacions Implementades**
- Imatges optimitzades i responsives
- CSS i JS minificats
- Fonts amb font-display: swap
- Lazy loading d'imatges
- Compressió d'assets

## 📈 Analytics i Seguiment

### **📊 Configuració Recomanada**
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

### **🎯 Esdeveniments a Rastrejar**
- Clics en navegació
- Interaccions amb carrusel
- Enviaments de formulari de contacte
- Canvis d'idioma
- Clics en galeria

## 🔐 Seguretat

### **🛡️ Consideracions de Seguretat**
- Validació de formularis en client i servidor
- Sanitització d'inputs
- Headers de seguretat configurats
- HTTPS recomanat per a producció

### **📋 Checklist de Seguretat**
- [ ] Formularis validats
- [ ] No exposició de dades sensibles
- [ ] Headers de seguretat configurats
- [ ] Certificat SSL instal·lat
- [ ] Backups regulars configurats

## 🌍 Accessibilitat

### **♿ Característiques d'Accessibilitat**
- ✅ Navegació per teclat completa
- ✅ Atributs ARIA implementats
- ✅ Contrast de colors AA
- ✅ Text alternatiu en imatges
- ✅ Skip links per a navegació
- ✅ Formularis etiquetats correctament

### **🔧 Testeig d'Accessibilitat**
```bash
# Usar eines com:
# - axe-core
# - Lighthouse accessibility audit
# - WAVE Web Accessibility Evaluator
```

## 📚 Recursos Addicionals

### **📖 Documentació**
- [Guia d'HTML5](https://developer.mozilla.org/docs/Web/HTML)
- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [JavaScript ES6+](https://developer.mozilla.org/docs/Web/JavaScript)

### **🎨 Recursos de Disseny**
- [Paleta de Colors Xinesa](https://www.color-hex.com/color-palette/chinese)
- [Tipografies Chinese-friendly](https://fonts.google.com/?subset=chinese-simplified)

### **📱 Eines de Testing**
- [Responsive Design Checker](https://responsivedesignchecker.com/)
- [GTmetrix](https://gtmetrix.com/)
- [PageSpeed Insights](https://pagespeed.web.dev/)

## 📄 Llicència i Drets d'Autor

```
© 2025 Any Nou Xinès amb Barcelona
Tots els drets reservats.

Aquest projecte està desenvolupat per a la promoció cultural de l'Any Nou Xinès a Barcelona.
Les imatges, logos i contingut estan protegits per drets d'autor dels seus respectius propietaris.

Organitzadors:
- Associació Grupo Artistas Huaxing
- Institut Confuci de Barcelona  
- Casa Àsia
- Ajuntament de Barcelona
- Consolat General de la R.P. Xina
```

### **⚖️ Ús i Distribució**
- ✅ Ús personal i educatiu permès
- ✅ Contribucions i millores benvingudes
- ❌ Ús comercial requereix autorització
- ❌ Redistribució sense atribució prohibida

## 📞 Contacte i Suport

### **💬 Informació de Contacte**
- **Email**: hola@anynouxines.barcelona
- **Adreça**: Passeig Sant Joan, 34, Local - Barcelona
- **Responsable**: Associació Grupo Artistas Huaxing

### **🐛 Reportar Issues**
Si trobes algun problema o tens suggeriments:
1. Verifica que no sigui un problema conegut
2. Proporciona detalls del navegador i dispositiu
3. Inclou passos per reproduir el problema
4. Adjunta captures de pantalla si és rellevant

### **🤝 Contribuir al Projecte**
Les contribucions són benvingudes! Per contribuir:
1. Fork del repositori
2. Crear branch per al teu feature: `git checkout -b feature/nova-funcionalitat`
3. Commit dels canvis: `git commit -m 'Afegir nova funcionalitat'`
4. Push del branch: `git push origin feature/nova-funcionalitat`
5. Crear Pull Request

---

**¡Gràcies per visitar Any Nou Xinès amb Barcelona! 🏮🎊**

*Que l'Any Nou porti prosperitat, felicitat i bona fortuna per a tots.*

*新年快乐！恭喜发财！*
