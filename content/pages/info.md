---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/moonset.webp
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-d
    backgroundSize: full
    text: >
      ## Hiya! I'm Annie, a programmer with a passion for problem-solving.


      Whether its tackling a coding challenge or a solving puzzles in other
      mediums, I thrive on finding solutions.


      I hold a certificate in Full-Stack Web Development and a Bachelor's degree
      from Arizona State University, where my undergrad research focused on
      evolving relationships between humans and technology, AI and robot ethics,
      and prompt engineering.


      As I continue to grow my knowledge and proficiency in dozens of web
      languages, I have developed a special interest in cybersecurity,
      particularly as a part of the development lifecycle rather than waiting
      until production to meet compliance standards. I'm also exploring both
      software and hardware development as I expand my knowledge of programming
      languages and integrated systems.


      My dedication to experimentation, agile development, and securing the
      intersection of technology and humanity drives me to deliver user-centric,
      trustworthy, and innovative solutions.
    media:
      type: ImageBlock
      url: /images/annie.png
      altText: Hero image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: JavaScript + libraries
      - type: Label
        label: React
      - type: Label
        label: Node.js
        url: ''
      - type: Label
        label: Express.js
        url: ''
      - type: Label
        label: Next.js
      - type: Label
        label: Responsive Design
        url: ''
      - type: Label
        label: GraphQL
        url: ''
      - type: Label
        label: Postgres/SQL
      - type: Label
        label: MongoDB/Mongoose ODM
      - type: Label
        label: Authentication
      - type: Label
        label: API Consumption
      - type: Label
        label: Custom APIs
      - type: Label
        label: SBOM Generation
        url: ''
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: >+
          **Current**


          *   freelance development for Protec Accessories


          <!---->


          *   design, build, deploy, and monitor an ecommerce site designed for
          individual and wholesale retail


          **2017 - 2023**


          *   seasonal work at Spirit Halloween


          <!---->


          *   3 years of management, promoted each year


          <!---->


          *   top-grossing store location in state all 3 years

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |+
          **Feb-Aug 2024**

          *   excelled in a 24 week bootcamp program

          *   discovered a love for backend development

          **Pandemic 2020**

          *   began coding as a hobby

          **Aug 2019 - May 2023**

          *   completed Bachelor's degree, graduating with honors

          **May 2019**

          *   graduated with high school diploma + 30 community college credits

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/fairybones'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Linkedin
            url: 'https://www.linkedin.com/in/annie-schalnat/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Profile
            url: 'https://www.linkedin.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions: []
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions: []
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions: []
        styles:
          self:
            textAlign: left
    columns: 3
    spacingX: 120
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    subtitle: 'You can find me here:'
  - type: TextSection
    variant: variant-a
    subtitle: ''
    colors: colors-f
    text: >+
      <div style="text-align:
      center">[aeschalna@gmail.com](mailto:thisismyemail.@myemail.me)</div>

  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s chat... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your idea or project!
          isRequired: true
          width: full
          type: TextareaFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
---
