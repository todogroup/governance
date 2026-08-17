name: "TODO OSPO Ambassador Contribution"
description: "Submit a contribution to TODO Group resources and community"
title: "[Ambassador Contribution]: "

body:
  - type: markdown
    attributes:
      value: |
        ## TODO Ambassador Contribution

        Use this form to report contributions to TODO Group resources, initiatives, and community activities.

  - type: input
    id: github-handle
    attributes:
      label: GitHub handle
      placeholder: "@username"
    validations:
      required: true

  - type: dropdown
    id: todo-area
    attributes:
      label: TODO resource or community initiative
      options:
        - "OSPO Book or TODO Guides"
        - "Research studies or whitepapers"
        - "TODO Blog or Newsletter"
        - "OSPO Maturity Model, Mind Map or Glossary"
        - "Awesome OSS Management repo"
        - "TODO Working Groups"
        - "OSPOlogy or TODO meetups and events in your region"
        - "TODO website or other TODO repositories"
        - "TODO community support"
        - "Other TODO resource or initiative"
    validations:
      required: true

  - type: textarea
    id: contribution
    attributes:
      label: What did you contribute?
      description: Briefly describe what you contributed to the selected TODO resource or initiative.
      placeholder: "I contributed..."
    validations:
      required: false

  - type: input
    id: contribution-url
    attributes:
      label: Contribution URL
      description: Link to the PR, issue, TODO resource, event, meeting notes, publication, or other evidence.
      placeholder: "https://..."
    validations:
      required: true

  - type: input
    id: social-handle
    attributes:
      label: LinkedIn or X profile
      description: Optional. If you'd like TODO to consider promoting your contribution on our social media channels, share your LinkedIn or X profile so we can tag you.
      placeholder: "LinkedIn profile URL or @Xhandle"
    validations:
      required: false
