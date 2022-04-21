name: Bug Report
description: Report a bug on Minehut
labels: ["bug"]

body:
  - type: checkboxes
    id: terms
    attributes:
      label: Checklist
      description: Confirm all of these are checked and valid.
      options:
        - label: I have read and agree to the README (found on https://github.com/Minehut/Meta)
          required: true
        - label: I am NOT reporting a security vulnerability
          required: true
        - label: I have searched the Issue Tracker to make sure this is not a duplicate issue
          required: true
        - label: This issue does not contain any sensitive information
          required: true
  - type: dropdown
    id: platform
    attributes:
      label: What platform does this issue occur on?
      multiple: true
      options:
        - Java
        - Bedrock
        - Website
        - Discord
        - Other
    validations:
      required: true
  - type: textarea
    id: bug
    attributes:
      label: Current Behavior?
      description: A clear and concise description of what the bug is.
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: What should happen?
      description: What is the expected behavior of the action?
    validations:
      required: true
  - type: textarea
    id: reproduce
    attributes:
      label: Reproduction Steps
      description: Steps to reproduce the behavior.
    validations:
      required: true
  - type: textarea
    id: device
    attributes:
      label: Client Information?
      description: |
        Provide the following applicable information
        - Minecraft client (and version): 
        - Web browser (and version): 
        - Operating system (and version): 
        - Minehut server name
    validations:
      required: true
  - type: textarea
    id: image
    attributes:
      label: Images?
      description: If applicable, add screenshots, short videos/GIFs to help explain your problem
  
