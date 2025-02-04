---
name: Request Access
about: Request Access
title: ''
labels: ''
assignees: ''

---

name: Request Access
description: Request access to the private repository
title: "Access Request for [Your GitHub Username]"
labels: ["access request"]
body:
  - type: input
    id: github_username
    attributes:
      label: "GitHub Username"
      description: "Enter your GitHub username"
      placeholder: "your-github-username"
    validations:
      required: true
  - type: textarea
    id: reason
    attributes:
      label: "Reason for Request"
      description: "Briefly explain why you need access"
      placeholder: "I am working on a related project..."
    validations:
      required: true
