+++
categories = ["web-dev"]
coders = ["josema294"]
date = 2023-08-20T12:00:00Z
description = "Pagina web personal con portafolio, descripción, blog y metodo de contacto. Realizada con el framework Hugo."
github = ["https://github.com/josema294/personalpage"]
image = "/images/capturasproyectos/personalwebpage_capture1.png"
title = "Pagina web personal"
type = "post"

[[tech]]
logo = "https://res.cloudinary.com/samrobbins/image/upload/v1591793276/logos/logos_hugo_h2xbne.svg"
name = "Hugo"
url = "https://gohugo.io/"

[[tech]]
logo = "/logos/html5.svg"
name = "HTML5"
url = "https://www.w3.org/html/"

[[tech]]
logo = "/logos/css3.svg"
name = "CSS3"
url = "https://www.w3.org/Style/CSS/"

[[tech]]
logo = "/logos/cloudflare.svg"
name = "Cloudflare"
url = "https://https://www.cloudflare.com/"

[[tech]]
logo = "/logos/javascript.svg"
name = "JavaScript"
url = "https://www.javascript.com/"

+++

Página web personal desarrollada utilizando el versátil framework Hugo. La base de la estructura de este portafolio digital proviene del tema [Developer Portfolio](https://themes.gohugo.io/themes/hugo-developer-portfolio/), reconocido por su diseño limpio y profesional. Sin embargo, lejos de quedarme con la propuesta inicial, decidí emprender un viaje de personalización para asegurarme de que reflejase fielmente mi visión y necesidades.

Entre las adaptaciones realizadas, destaco la localización completa al español, permitiendo que la página sea amigable para aquellos que se comunican en este idioma. Además, llevé a cabo modificaciones significativas en diversas secciones, desde la reestructuración de contenidos hasta la adaptación de la interfaz visual, buscando ofrecer una experiencia única y memorable a cada visitante.

Este proyecto, más allá de ser un reflejo de mi trabajo, es también una muestra de mi capacidad para adaptar y personalizar soluciones existentes, dándoles un giro propio y garantizando que satisfagan requisitos específicos. Es un testimonio de mi compromiso con la calidad y la atención al detalle.



## Secciones

### Homepage

![Homepage Screenshot](/images/capturasproyectos/personalwebpage/personalwebpage_capture0.png "Homepage Screenshot")

La "homepage" ofrece una panorámica de mi perfil profesional a través de las siguientes secciones:

* Redes y Correo de Contacto: Enlaces directos a mis redes sociales y una dirección de correo para facilitar la comunicación y conexión.

* Habilidades: Presentación de las competencias técnicas y soft skills más destacadas que he desarrollado en mi carrera.

* Experiencia: Resumen de posiciones y roles desempeñados en diferentes empresas o proyectos.

* Cursos y Formación Online: Listado de capacitaciones, talleres y certificaciones obtenidas a través de plataformas de educación en línea.

* Educación: Descripción de mis estudios formales, desde grados hasta posgrados, incluyendo instituciones y fechas relevantes.

### Sobre mi

![Sobre mí Screenshot](/images/capturasproyectos/personalwebpage/personalwebpage_capture2.png "Sobre mí Screenshot, con un texto descriptivo y una foto de carnet")

La sección "Sobre mí" sirve como presentación personal y profesional dentro de la página. En ella, los visitantes pueden encontrar una descripción concisa de mi perfil, abarcando desde aspectos personales hasta motivaciones profesionales. Esta sección está diseñada para dar una visión global y humana sobre quién soy, brindando un contexto a las habilidades, experiencia y formación que se muestran en otras partes de la web.

### Blog

![Blog](/images/capturasproyectos/personalwebpage/personalwebpage_capture3.png)

La sección "Blog" se dedica a la publicación y recopilación de artículos y entradas escritas por mí. Aquí, los visitantes pueden explorar diversos temas, reflexiones y aprendizajes relacionados con mi área de expertise y otros intereses. Esta sección no solo sirve como plataforma para compartir conocimientos y opiniones, sino también como un registro cronológico de mi evolución y crecimiento profesional.

### Portafolio

![Portafolio](/images/capturasproyectos/personalwebpage/personalwebpage_capture4.png)

La sección "Portafolio" funciona como una vitrina digital de mis proyectos tanto personales como profesionales. Aquí, los visitantes tienen la oportunidad de visualizar y explorar los trabajos que he realizado, desde su concepto inicial hasta su ejecución final. Cada proyecto está acompañado de detalles relevantes y, en algunos casos, enlaces a demos o sitios en vivo. Esta sección es esencial para quienes estén interesados en conocer la calidad, diversidad y enfoque de mi trabajo, ofreciendo una muestra tangible de mis habilidades y experiencia.

### Contacto

![Contacto](/images/capturasproyectos/personalwebpage/personalwebpage_capture5.png)

La sección "Contacto" ofrece un formulario directo para quienes deseen comunicarse conmigo. Es el medio más rápido y sencillo para enviar consultas, comentarios o propuestas relacionadas con mi trabajo.

<!-- ## Installation

### Integrating into your site

To install this theme, first create a themes folder in your site with

```bash
mkdir themes
```

Then move into this directory with

```bash
cd themes
```

The repository can then be added either by cloning or adding as a submodule

```bash
# Cloning
git clone https://github.com/samrobbins85/hugo-developer-portfolio hugo-developer-portfolio
# Submodule
git submodule add https://github.com/samrobbins85/hugo-developer-portfolio hugo-developer-portfolio
```

In the `config.toml` file in your site directory add

```toml
theme="hugo-developer-portfolio"
```

### Creating a new site

If you just want to get set up with a new site, you can start from the Example Site I have provided. To do this:

1. Cut the `exampleSite` folder out of the theme and paste it wherever you want
2. Create a `theme` directory within the `exampleSite folder`
3. Paste the theme into this directory, ensuring is has the name `hugo-developer-portfolio`

## CMS

For the content management system I have used Forestry CMS. This provides great flexibility for adding and editing content and integrates great with Hugo as it commits markdown files directly to GitHub.

## Configuration

This is a highly configurable site, and as such, it will be unlikely that it will work with your existing site.

### Config.toml

`Config.toml` provides the basic structure of the site, it contains a range of sections

#### Base information

In the example site, the base information looks as follows

```toml
baseURL = "http://example.com" # The URL of your site
languageCode = "en-gb" # The language you want to display the site in
title = "Sam Robbins" # The title you want to appear in the address bar
theme = "hugo-developer-portfolio" # The theme, don't change this
```

#### Plugins

These are the essential plugins required to run the site, but you can add more if you need

```toml
[params.plugins]
  # CSS Plugins
  [[params.plugins.css]]
  URL = "https://cdn.jsdelivr.net/npm/uikit@3.2.6/dist/css/uikit.min.css"
  # JS Plugins
  [[params.plugins.js]]
  URL = "https://cdn.jsdelivr.net/npm/uikit@3.2.6/dist/js/uikit.min.js"
  [[params.plugins.js]]
  URL = "https://cdn.jsdelivr.net/npm/uikit@3.2.6/dist/js/uikit-icons.min.js"
```

#### Navigation

This specifies the titles for the entries in the taskbar. `name` can be changed to show a different name. `URL` should not be changed in most situations as the pages will exist at the old URLs rather than the new ones, so this will result in dead links.

```toml
# navigation
[menu]
  [[menu.main]]
  name = "About"
  URL = "about"
  [[menu.main]]
  name = "Blog"
  URL = "blog"
  [[menu.main]]
  name = "Portfolio"
  URL = "portfolio"
  [[menu.main]]
  name = "Contact"
  URL = "contact"
```

#### Params

This contains the other configuration information

```toml
[params]
home = "Home" # What you want the homepage to show up as in the menu bar
# Meta data
description = "The website of Sam Robbins, 2nd Year Computer Science Student at Durham University"
author = "Sam Robbins"


  [params.contact]
  formAction = "https://formspree.io/<Insert code>" # Add your formspree URL here to get emails

  # This contains the contact information for the footer
  [params.footer]
  email = "samrobbinsgb@gmail.com"
  address = "Durham, UK"
  googlemaps = "https://www.google.com/maps/embed/v1/place?q=place_id:ChIJwbHYJaUqfEgRK0Ui9dVGimc&key=AIzaSyAE_4rVAKux_DSPcb_OdSRDaovtPOSk_3U"
```

### homepage.yml

This file is stored in `data/homepage.yml`. It determines the content of the homepage and contains many sections

#### banner

This is the text in the hero section, change it to whatever you want

```yml
banner:
  title: Hi! I’m Sam
```

#### social

Put all of your social links here and they will appear in the social section

```yml
social:
  twitter: ""
  linkedin: sam-robbins-gb
  github: samrobbins85
  gitlab: ""
  facebook: ""
  instagram: ""
  gmail: samrobbinsgb
```

#### about

* `enable` can be used to hide this section
* `content` determines what text is shown here
* `btnText` changes the text on the button
* `URL` changes the URL the button directs to

```yml
about:
  enable: true
  content: 2nd Year Durham Computer Science Student
  button:
    btnText: Find out more
    URL: "/about"
```

#### skill

* `enable` can be used to hide this section
* `title` determines the text both under the image and in the modal
* `logo` determines the image that shows up
* `description` is the text that appears inside the modal

```yml
skill:
  enable: true
  item:
    - title: JavaScript
      logo: https://res.cloudinary.com/samrobbins/image/upload/v1591793272/logos/logos_javascript_adj1dx.svg
      description: Details coming soon, contact me if you want to know more
```

#### experience

* `enable` can be used to hide this section
* `logo` determines the image that shows up
* `title` is the main text that appears in the card
* `company` is the secondary text in the card
* `duration` is the tertiary text in the card

```yml
experience:
  enable: true
  item:
    - logo: https://res.cloudinary.com/samrobbins/image/upload/f_auto,q_auto/v1591793271/logos/logos_google_id6v9a.svg
      title: init.g
      company: Google
      duration: November 2019
```

#### hackathons

```yml
hackathons:
  enable: true
  item:
    - title: Hack Cambridge 2019
      description: Climate change simulator
      image: https://res.cloudinary.com/samrobbins/image/upload/f_auto,q_auto/v1591793405/stickers/Hack_Cambridge_101_ozoq5d.png
      url: javascript:void(0)
``` -->