name: '🏠 New prototype'
labels: 'prototype'
description: I want to new prototype

body:
  - type: input
    attributes:
      label: New prototype name
      description: |
        Should start with team name, e.g. `idam-`
      placeholder: |
        idam-prototype
    validations:
      required: true
