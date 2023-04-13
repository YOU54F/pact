# pact-cli

Pact CLI Tools

## Scoop

### Supported Platforms

| OS           | Architecture | Supported |
| ------- | ------------ | --------- |
| Windows| | x86_64       | ✅        |
| Windows | aarch64 (via x86 emulation) |  ✅        |


[![Tests](https://github.com/you54f/pact/actions/workflows/ci.yml/badge.svg)](https://github.com/you54f/pact/actions/workflows/ci.yml) [![Excavator](https://github.com/you54f/pact/actions/workflows/excavator.yml/badge.svg)](https://github.com/you54f/pact/actions/workflows/excavator.yml)

bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

How do I install these manifests?
---------------------------------

To add this bucket, run:

`scoop bucket add pact https://github.com/you54f/scoop`

Search the bucket for available pact cli tools

`scoop search pact`

|Name                 |Version| Source|
| -------| -------  | --------- |
|pact                 |0.0.1  | pact|
|pact_cli             |0.0.1  | pact|
|pact_mock_server_cli |1.92.0  | pact|
|pact_plugin_cli      |0.1.0  | pact|
|pact_verifier_cli    |0.10.5 | pact|

Install all the tools, do `scoop install pact`.

Contains a bundle with

- Pact-Ruby-Standalone
  - pact.bat ()
  - pact-broker.bat
  - pact-message.bat
  - pact-mock-service.bat
  - pact-provider-verifier.bat
  - pact-stub-service.bat
  - pactflow.bat

You can also install the following tools separately

- pact-plugin-cli.exe
- pact_verifier_cli.exe
- pact_mock_server_cli.exe

How do I contribute new manifests?
----------------------------------

To make a new manifest contribution, please read the [Contributing Guide](https://github.com/you54f/.github/blob/main/.github/CONTRIBUTING.md).

----

