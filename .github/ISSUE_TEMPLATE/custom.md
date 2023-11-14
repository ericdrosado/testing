---
name: Custom issue template
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

name: 🐞 Bug
description: File a bug/issue
title: "[BUG] <title>"
labels: ["Bug", "Needs Triage"]
body:
- type: textarea
  attributes:
    label: Anything else?
    description: |
      Links? References? Anything that will give us more context about the issue you are encountering!

      Tip: You can attach images or log files by clicking this area to highlight it and then dragging files in.
  validations:
    required: false
