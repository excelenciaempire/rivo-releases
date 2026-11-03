# Rivo by Riverz · Windows assistant

**Voice input, dictation and desktop-assistance workflows for Windows.**

[Latest release](https://github.com/excelenciaempire/rivo-releases/releases/latest) · [Engineering notes](ENGINEERING.md) · [Juan Rios](https://github.com/excelenciaempire)

This repository distributes Rivo installers and update metadata. It also explains the engineering work behind the product; application source and user configuration are not distributed here.

## How I build with AI

**All of my development work presented here was done with AI assistance.** I use AI throughout implementation, debugging and validation. I understand programming and software engineering fundamentals, and use them to define requirements, guide the tools, review changes and check how the software actually behaves. I take responsibility for technical decisions and results.

## Product scope

Rivo combines a compact desktop interface, voice or typed requests, dictation, local screen-context tools and optional external AI services. The implementation separates literal dictation from requests to act on the desktop. An ambiguous target, changed window or missing permission should stop an action rather than guess.

My work covers the application workflow, Windows interaction, speech/provider integration, settings, onboarding and packaging. This is a separate desktop-assistance product from the Riverz AI video editor.

**Python · Windows UI Automation · Speech integrations · Local and cloud-assisted workflows**

## Releases

The latest public release observed on 2026-11-03 is [v1.30.8](https://github.com/excelenciaempire/rivo-releases/releases/tag/v1.30.8), with `Rivo-Setup.exe` and `rivo-update.json`. Use the release page for the current version and files.

The implementation documentation targets Windows 10/11 x64. Optional cloud capabilities require the user's own provider configuration and may incur provider charges; local and cloud functionality have different requirements.

This portfolio review verified that the release assets exist. It did not independently verify installer signatures, install on a clean machine or exercise the current binary.

## Privacy boundaries

Screen regions, dictation and assistant context can contain private information. Local tools and optional provider requests must be distinguished; enabling an external provider does not make that request local-only. This repository contains no user captures, recordings, configuration files or provider credentials.

[Professional contact](https://github.com/excelenciaempire/riverz-showcase/issues/new?title=Professional%20inquiry)
