name: Resolver issue
description: File an issue specific for resolver
labels: ["bug", "triage"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!

  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Also tell us, what did you expect to happen?
    validations:
      required: true

  - type: input
    id: adviser_id
    attributes:
      label: Adviser identifier
      description: A unique adviser identifier specifying the request (optional).
      placeholder: adviser-211011103402-foo
    validations:
      required: false

  - type: textarea
    id: requirements
    attributes:
      label: Pipfile input
      description: Please copy and paste Pipfile with direct dependencies (optional).
      render: toml

  - type: textarea
    id: requirements_lock
    attributes:
      label: Pipfile.lock input
      description: Please copy and paste Pipfile.lock with all the dependencies (optional, if any provided).
      render: json

  - type: textarea
    id: thoth_yaml
    attributes:
      label: .thoth.yaml configuration file
      description: Please copy and paste .thoth.yaml configuration file with information about overlays used (optional).
      render: yaml

  - type: dropdown
    id: recommendation_type
    attributes:
      label: What recommendation type do you use?
      multiple: true
      options:
        - latest
        - performance
        - security
        - stable
        - testing

  - type: textarea
    id: logs
    attributes:
      label: Relevant resolver log output
      description: Please copy and paste resolver log output (optional).
      render: text
