name: 🐞 Bug Report
description: Help us squash bugs by reporting issues clearly!
title: "[Bug] <short description>"
labels: [bug]
body:
  - type: markdown
    attributes:
      value: |
        ### 👋 Thanks for helping improve our project!
        Please fill out the following details to help us understand and fix the issue faster.

  - type: textarea
    id: what-happened
    attributes:
      label: 💥 What went wrong?
      description: Describe the issue in detail. What did you expect to happen, and what actually happened?
      placeholder: When I tap the save button, the app crashes with an error...
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: 🧪 Steps to Reproduce
      description: Help us reproduce the issue by listing clear steps.
      placeholder: |
        1. Open the app
        2. Go to the "Settings" screen
        3. Tap on "Save" without entering anything
        4. App crashes
    validations:
      required: true

  - type: input
    id: version
    attributes:
      label: 📱 App Version and OS
      placeholder: e.g., FlatFund v1.2.1 on Android 14

  - type: textarea
    id: logs
    attributes:
      label: 📄 Logs or Screenshots (Optional)
      description: If possible, include error logs or screenshots that show the problem.
      placeholder: Drag and drop images or paste logs here.
