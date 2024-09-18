---
type: PostLayout
title: Reflecting On SBOM-a-rama 2024
colors: colors-c
date: '2024-09-16'
author: content/data/team/doris-soto.json
excerpt: 'A cybersecurity conference hosted by CISA in Denver, CO'
featuredImage:
  type: ImageBlock
  url: /images/sbom-a-ramaLOGO.jpg
  altText: Post thumbnail image
bottomSections:
  - elementId: ''
    type: RecentPostsSection
    colors: colors-f
    variant: variant-d
    subtitle: Recent posts
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 2
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
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
    showFeaturedImage: true
    showReadMoreLink: true
  - type: ContactSection
    backgroundSize: full
    title: Stay up-to-date with my words ✍️
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
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
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
Over September 11-12, I was fortunate to attend SBOM-a-rama, a critically important conference hosted by CISA, America’s Cyber Defense Agency. CISA exists to mitigate risks in the cyberspace ecosystem and manage critical infrastructure of the United States, but represents just one sector of many that are molding and evolving the future of cybersecurity globally.

## Day 1

With speakers and participants from multiple countries and many industries, including \~ but not limited to \~ government, healthcare, software development, and supply-chain security. The agenda for the day was strategically set to maximize presentations while permitting time for questions and discussion. As the ballroom fills, the excitement is palpable as people connect with long-distance coworkers and colleagues, some of whom they communicate with weekly but are just now meeting in the flesh. Participants take their seats and at 9am sharp the convention begins. Across technical and legal divides, there is a unitary, glimmering goal of industry wide collaboration. Specifically, there is a call to action from many for global data normalization, standardization of naming conventions and component identification. The working goal is to reach a single SBOM approach that is compatible with distinct and extensible use cases. 

This is where the solidarity fractures. Specifically, to what extent is disclosure necessary in order to secure vulnerabilities and enhance technological trust and transparency? Documentation outlining the minimum requirements for a Software Bill of Materials (SBOM) exists, but as experts from across the globe exchange views on the current problems in cybersecurity, it is evident that these regulations require further deliberation. There is a consensus from many that sharing data is the way forward. But this solution presents complications in data ownership, legal sovereignty, and the real world implications of a global data lake, from storage to privacy and protection. 

As the discussion progresses it is apparent that there must be a proprietary distinction between internally shared SBOM data and readily available SBOM data. Interconnectivity between security and development teams is a must, so how do we foster communication flow inside and outside of an organization? 





### Heading 3

