---
name: Question
description: Ask a question about the project.
title: "[Question]: "
labels: ["question"]
body:
  - type: markdown
    attributes:
      value: |
        **Please use this template to ask a question.**

        Before you ask, please make sure you have:
        - Searched the existing issues.
        - Checked the documentation.

  - type: textarea
    id: question
    attributes:
      label: Your Question
      description: "Please provide as much detail as possible."
    validations:
      required: true
--- 