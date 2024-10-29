# 🐋 Svitbo Infrastructure

The infrastructure part of the Svitbo project.

Is used to provision basic infrastructure for the [Core](https://github.com/Svitbo/film-core) and [Frontend](https://github.com/Svitbo/film-frontend) parts on the base of the GCP compute engine instances.

Currenly, consists of the `ce_startup.sh` script that is injected as set of the executable startup instructions when deploying new Svitbo environment. Follow the [GCP documentation](https://cloud.google.com/compute/docs/instances/startup-scripts/linux) to learn more.

This repository contains only **some pieces** of the Svitbo project automatization and deployment configurations.
Other project-specific configs are located in the:

- `compose.d/` - multi-layer Docker Compose stacks
- `.github/workflow/` - GitHub Actions pipelines
- `nginx.d/` - Nginx configurations (only in frontend)

## Requirements

- Access to the GCP project environment
  - Using user account (preferable)
  - Using service account
- Any Debian-based Linux machine (Debian, Ubuntu, Ubuntu Pro)
