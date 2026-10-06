# Filip Gutica

I like writing dev tools that make coding and working with agents easier.

## Terminal tools

| Tool | What it does | Links | Latest |
| --- | --- | --- | --- |
| **annoterm** | Review and edit Markdown in the terminal. Attach comments and copy them as structured feedback for a coding agent. | [Website](https://filipgutica.github.io/annoterm/) · [Source](https://github.com/filipgutica/annoterm) | ![annoterm release](https://img.shields.io/github/v/release/filipgutica/annoterm?style=flat-square&label=&color=555555) |
| **wtree** | See Git worktrees with their age and pull request state, then review a cleanup plan before removing anything. | [Website](https://filipgutica.github.io/wtree/) · [Source](https://github.com/filipgutica/wtree) | ![wtree release](https://img.shields.io/github/v/release/filipgutica/wtree?style=flat-square&label=&color=555555) |
| **devps** | Manage local dev servers on macOS. See what started each one, jump back to its terminal or app, or stop the whole job. | [Website](https://filipgutica.github.io/devps/) · [Source](https://github.com/filipgutica/devps) | ![devps release](https://img.shields.io/github/v/release/filipgutica/devps?style=flat-square&label=&color=555555) |

## Working with agents

- **[T3 Code Workbench](https://filipgutica.github.io/t3code/)** is my fork of T3 Code for planning across repositories, organizing tickets, and starting agent threads in worktrees. [Source](https://github.com/filipgutica/t3code) · [Downloads](https://github.com/filipgutica/t3code/releases)
- **[filip-stack](https://github.com/filipgutica/filip-stack)** holds the coding-agent skills and workflows I use for planning, implementation, review, and technical writing. It installs as a plugin marketplace for Claude and Codex.

## Vue components

- **[Vue UI](https://filipgutica.github.io/ui/)** is my Vue 3 component library for shared controls, dialogs, and code blocks. [Source](https://github.com/filipgutica/ui)

## Install

The three terminal tools install from [filipgutica/homebrew-tap](https://github.com/filipgutica/homebrew-tap):

```sh
brew install filipgutica/tap/annoterm
brew install filipgutica/tap/wtree
brew install filipgutica/tap/devps
```

annoterm and wtree run on macOS and Linux. devps runs on macOS only.
