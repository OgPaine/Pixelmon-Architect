name: Bug Report
description: Create a bug report to help us improve Better Minecraft
labels: [ "bug" ]
body:
    -   type: textarea
        attributes:
            label: Describe the Bug
            description: A clear and concise description of what the bug is
        validations:
            required: true
    -   type: textarea
        attributes:
            label: Reproduction Steps
            description: Tell us about the steps to reproduce the bug
            value: |
                1.
                2.
                3.
                ...
        validations:
            required: false
    -   type: textarea
        attributes:
            label: Screenshots and Videos
            description: If applicable, add screenshots or videos to help explain your problem
        validations:
            required: false
    -   type: input
        attributes:
            label: Operating System
            description: The operating system you were using when the bug occured
            placeholder: Windows 11
        validations:
            required: true
    -   type: input
        attributes:
            label: Modpack Version
            description: The modpack version you were using when the bug occured (such as v26, v3, etc)
        validations:
            required: true
    -   type: textarea
        attributes:
            label: Other Mods
            description: Any additional mods you added to the modpack
        validations:
            required: false
