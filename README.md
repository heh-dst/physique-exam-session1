# Examen de physique
[![CI](https://github.com/heh-dst/physique-exam-session1/actions/workflows/make.yml/badge.svg)](https://github.com/heh-dst/physique-exam-session1/actions/workflows/make.yml)

Projet Auto-Multiple-Choice.

## Prerequisites:
- Docker
- VSCode
- VSCode Dev Containers extension

## Usage
The files to modify are~:
- [questionbank.tex](questionbank.tex)
- [questions.tex](questions.tex)

Then, to start the GUI, open a terminal and type `auto-multiple-choice`.

If the AMC window doesn't open, navigate to http://localhost:6900/vnc.html in your browser.
The noVNC default password is `vscode`.

## Documentation
Documentation of auto-multiple-choice is available at http://auto-multiple-choice.net.

## Related work
This template works along with the public Docker image [froland/devcontainer-amc](https://hub.docker.com/r/froland/devcontainer-amc) (sources available on [GitHub froland/devcontainers](https://github.com/froland/devcontainers)).
