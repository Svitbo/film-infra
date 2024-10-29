# 🐋 Svitbo Infrastructure

The infrastructure part of the Svitbo project.

Is used to provision basic infrastructure for the [Core](https://github.com/Svitbo/film-core) and [Frontend](https://github.com/Svitbo/film-frontend) parts on the base of GCP compute engine instances.

Currenly, consists of the `ce_startup.sh` script that is injected as the executable startup instructions when deploying new Svitbo environment. Follow the [GCP documentation](https://cloud.google.com/compute/docs/instances/startup-scripts/linux) to learn more.

This repository contains only **some pieces** of the Svitbo project automatization and deployment configuration.
Other project-specific configs are located in:

- `compose.d/` - multi-layer Docker Compose stacks
- `.github/workflow/` - GitHub Actions pipelines
- `nginx.d/` - Nginx configurations (only in frontend)

## Requirements

- Any Debian-based Linux machine (Debian, Ubuntu, Ubuntu Pro)
