name: Bug report
description: Template for bug reports
title: '[Bug]: '
body:
  - type: textarea
    attributes:
      label: Describe the bug
      description: A clear Description of what the bug is
    validations:
      required: true
  - type: textarea
    attributes:
      label: To Reproduce
      description: 'Steps to reproduce the behavior:'
      value: |-
        1.
        2.
        3.
        4.
  - type: textarea
    attributes:
      label: Expected behavior
      description: A clear description of what you expected to happen
  - type: dropdown
    attributes:
      label: Modpack version
      options:
        - 1.1.0
        - 1.2.1
        - 1.2.2
    validations:
      required: true
  - type: input
    attributes:
      label: Ram Allocated
  - type: textarea
    attributes:
      label: Additional contex
      description: Add any other context about the problem here.
