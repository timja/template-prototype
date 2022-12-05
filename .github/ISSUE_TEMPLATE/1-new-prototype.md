name: '🏠 Hosting request'
labels: 'hosting-request'
description: I want to host a plugin or library in the Jenkins organization

body:
  - type: input
    attributes:
      label: Prototype name
      description: |
        URL of the repository to host in the jenkinsci organization
      placeholder: |
        https://github.com/your-org/your-repo-name
    validations:
      required: true
