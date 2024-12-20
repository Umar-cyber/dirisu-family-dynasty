---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 38
  url: /images/Abeokuta_Forest_Nursery.jpg
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: DIRISU FAMILY DYNASTY
    subtitle: "The Dirisu Family Dynasty is closely associated with Okpella in Edo State, Nigeria, where they have played significant roles in leadership, cultural preservation, and community development.\_A prominent figure in this lineage is His Royal Majesty, Alhaji (Dr.) Andrew Yesufu Eshioramhe Dirisu, who held the title of *Okuokpellagbe* of Okpella for decades. His reign marked significant advancements in education, infrastructure, and unity in Okpella, transforming it into an industrial hub within Edo State due to its rich mineral resources.The late monarch was instrumental in the establishment of educational institutions, including the Anglican Grammar School (now Ikpomaza Grammar School), and facilitated the town's connection to the national electricity grid. His leadership fostered peace and industrial growth, attracting companies to Okpella for mineral exploitation.Additionally, Alhaji Dirisu was recognized nationally and internationally, holding positions like Vice-President of the Nigerian Supreme Council for Islamic Affairs and receiving honors for his dedication to community service and development, such as leadership awards from the Afenmai World Congress.The family continues to hold cultural and leadership significance in Okpella, representing the legacy of resilience, innovation, and commitment to communal progress."
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Contact...\U0001F4AC"
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
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
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
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
