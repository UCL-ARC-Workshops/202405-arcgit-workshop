# ARC-travel repository

**DISCLAIMER**: This repository is used to learn how to use GitHub and markdown (quarto) to publish content. The holidays planned may never happen, but it's up to you if you want it to happen.

The steps seen in the workshop will be shared through a hackmd page.

## About how this repository works

The content of this repository gets build every time something is pushed to `main` and the github page will be updated accordingly. The build process is defined in the [publish github action file](.github/workflows/publish.yml).

The content of the website has been saved under the [`web_source` directory](./web_source). This directory was chosen as an example and it may differ in different repositories you may work with.

## Acknowledgements

Inspiration from [AffComLab
repository](https://github.com/jmgirard/affcomlab/tree/main) has been taken to list the travellers and cities automatically.

The `.devcontainer` has been adapted from [Zero-setup R workshops with GitHub Codespaces](https://github.com/revodavid/devcontainers-rstudio) repository presented at [rstudio::conf 2022](https://rstudioconf2022.sched.com/event/11iag/zero-setup-r-workshops-with-github-codespaces).

