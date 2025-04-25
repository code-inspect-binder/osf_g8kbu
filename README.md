# Executable Environment for OSF Project [g8kbu](https://osf.io/g8kbu/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** Social Smartphone Apps Do Not Capture Attention Despite Their Perceived High Reward Value

**Project Description:**
> Smartphones have been shown to distract people from their main tasks (e.g., studying, working), but the psychological mechanisms underlying these distractions are not clear yet. In a  preregistered experiment, we tested whether the distracting nature of smartphones stems from their high associated (social) reward value. Participants (N = 117) performed a visual search task while they were distracted by (a) high social reward apps (e.g., Facebook app icon + notification sign), (b) low social reward apps (e.g., Facebook app icon), and (c) no social reward apps (e.g., Weather app icon). We expected that high social reward app icons would slow down search, especially when people were deprived of their smartphones. Surprisingly, high social reward (vs. low or no social reward) apps did not impair visual search performance, yet in a survey (N = 158) participants indicated to perceive these icons as more rewarding. Our results demonstrate that even if people perceive social smartphone apps as more rewarding than nonsocial apps, this may not manifest in behavior.

**Original OSF Page:** [https://osf.io/g8kbu/](https://osf.io/g8kbu/)

---

**Important Note:** The contents of the `g8kbu_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_g8kbu/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_g8kbu/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `g8kbu_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

**Pull the Docker Image**

```bash
docker pull meet261/repo2docker-g8kbu:latest
```

**Launch RStudio Server**

```bash
docker run -e PASSWORD=yourpassword -p 8787:8787 meet261/repo2docker-g8kbu
```
Replace `yourpassword` with a secure password of your choice. You will use this to log in to the RStudio web interface.

**Once the container is running, visit `http://localhost:8787` in your browser.**
Use username: `rstudio` and the password you set with `-e PASSWORD=...`.
