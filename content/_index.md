---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
sections:
  - block: about.biography
    id: about
    content:
      title: Sobre mí...
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Habilidades
      items:
        - name: Gestión de datos de investigación
          description: Apoyo a proyectos de investigación y revisiones sistemáticas de literatura en todo el ciclo de gestión de datos, desde la planeación del manejo de los datos, búsqueda y descarga de información de fuentes bibliográficas, normalización y limpieza de datos y creación de matrices para en análisis y extracción de datos a través de Excel y Vantage Point. Promoviendo los principios FAIR y el uso de metodologías ágiles de investigación.
          icon: magnifying-glass-chart
          icon_pack: fas
        - name: Análisis y visualización de datos de investigación
          description: Acompañamiento a procesos investigativos desde el conocimiento adquirido en cursos con la Research Data Management Librarian Academy (RDMLA) e Introducción a la revisión sistemática de la literatura ofrecido por la OMS. Uso de herramientas libres como Gephi, Flourish, VosViewer.
          icon: chart-line
          icon_pack: fas
        - name: Ciencia abierta y publicación académica
          description: Diseño y desarrollo de planes de publicación científica orientados a promover el acceso abierto a la información en revistas académicas en open access y aprovechando los acuerdos transformativos de la Universidad y las editoriales. Apoyo a publicación de datos de investigación en repositorios como Mendeley Data.
          icon: person-chalkboard
          icon_pack: fas
  - block: experience
    content:
      title: Experiencia laboral
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Profesional en servicios especializados
          company: Pontificia Universidad Javeriana
          company_url: 'https://www.javeriana.edu.co/biblos'
          company_logo: Logo_Javeriana_Actualizado (1)
          date_start: '2021-07-01'
          date_end: ''
          description: Bibliotecóloga enlace con las facultades de Estudios ambientales y rurales, Ciencias y Filosofía, donde se ha acompañado la articulación de los procesos de docencia, investigación y servicio con 
        - title: Professor of Semiconductor Physics
          company: University X
          company_url: ''
          company_logo: org-x
          location: California
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
