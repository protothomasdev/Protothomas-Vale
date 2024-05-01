# Appmotion Vale style

This repository contains a Vale-compatible vocabulary for appmotion documentation.
It provides guides on spelling and spellcheck exceptions for common terms and abbreviations in technical documents like READMEs and automatically generated code documentation.

# Setup

Just add this to your Vale configuration:

```
StylesPath = .styles

MinAlertLevel = suggestion
Vocab = Base, Project

Packages = Google, https://gitlab.com/appmotion/team-swift/appmotion-vale-style/-/archive/v<VERSION>/appmotion-vale-style-v<VERSION>.zip

[*.md]
BasedOnStyles = Vale, Google
```

# Contribution

If you find terms and spellings that are missing, please feel free to add it here.
Just create a new branch, edit the files, create a merge request and merge it. It triggers a pipeline, that creates a new release.

Please read the documentation about the syntax first:
https://vale.sh/docs/topics/vocab/

If you want to add styling rules, please prepare a merge request with the proposed style and contact your Team-Lead for review.