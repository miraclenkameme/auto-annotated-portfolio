---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Technical Support & Systems Developer | Azure • Copilot • Automation
    subtitle: >-
      Helping businesses build secure, automated, and user-friendly IT
      solutions. Skilled in Microsoft 365, Azure AI, and technical support —
      blending cybersecurity discipline with hands-on problem-solving to deliver
      reliable results.
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
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions: []
    text: >+
      Hello! I’m Miracle Nkameme (Dike) — a Cybersecurity & Cloud Specialist
      pivoting into AI workflow automation and technical support.


      I am Azure-certified (AZ-900, SC-900) with hands-on experience in:


      *   Supporting users with Microsoft 365 tools (SharePoint, Teams,
      OneDrive, Power Platform).


      *   Building automation with Azure AI Foundry, Copilot Studio, and Power
      Automate.


      *   Troubleshooting, customer service, and technical issue resolution.


      *   Applying security frameworks (NIST, ISO, CIS) to protect business
      data.


      I combine strong technical support skills with system development and
      automation to help teams deliver secure, efficient, and user-friendly IT
      solutions.




    media:
      type: ImageBlock
      url: /images/profile_photo.jpg
      altText: >-
        Professional headshot of Miracle Nkameme (Cybersecurity & Cloud
        Specialist)
      caption: Miracle Nkameme (Dike) - Cybersecurity & Cloud Specialist
      elementId: ''
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Projects
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
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
      submitLabel: "Submit \U0001F680"
      styles:
        self:
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
        flexDirection: row
        textAlign: left
---
