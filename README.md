# Hello Developers

<p align="center">
  <a href="https://www.linkedin.com/in/pratikgond/">
    <img height="40" src="https://github.com/user-attachments/assets/93021f10-0082-4e89-9635-980f6d4ac1bb" alt="LinkedIn"/>
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://x.com/PratikGond69428">
    <img height="40" src="https://github.com/user-attachments/assets/09ead742-11c4-422b-af48-75e22af6f1f2" alt="Twitter"/>
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://www.pratikgond.vercel.app">
    <img height="40" src="https://github.com/user-attachments/assets/a91335a0-714c-4d63-86d2-6b97209a00ce" alt="Portfolio"/>
  </a>
</p>

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/platane/platane/main.yml?label=action&style=flat-square)](https://github.com/Platane/Platane/actions/workflows/main.yml)
[![GitHub release](https://img.shields.io/github/release/platane/snk.svg?style=flat-square)](https://github.com/platane/snk/releases/latest)
[![GitHub marketplace](https://img.shields.io/badge/marketplace-snake-blue?logo=github&style=flat-square)](https://github.com/marketplace/actions/generate-snake-game-from-github-contribution-grid)
![type definitions](https://img.shields.io/npm/types/typescript?style=flat-square)
![code style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)

Generates a snake game from a github user contributions graph

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>

Pull a github user's contribution graph.
Make it a snake Game, generate a snake path where the cells get eaten in an orderly fashion.

Generate a [gif](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.gif) or [svg](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg) image. Colors can [be](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-ocean.svg) [customized](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-grey.svg).

Available as github action. It can automatically generate a new image each day. Which makes for great [github profile readme](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme)


## Implementation

[solver algorithm](./packages/solver/README.md)

## Contribution Policy

This project does not accept pull request.

Reporting or fixing issues is appreciated, but change in the API or implementation should be discussed in issue first and is likely not going be greenlighted.
