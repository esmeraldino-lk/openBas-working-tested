# OpenBAS Docker Deployment

Welcome to the OpenBAS Docker deployment guide! This guide provides resources and information to help you deploy and
manage OpenBAS using Docker.

---

## 📚 Documentation

For detailed instructions on installing OpenBAS using Docker, refer to
the [OpenBAS documentation space](https://docs.openbas.io/latest/deployment/installation/#using-docker).


## 🔧 Deployment Overview

### Quick Start with Docker Compose

The OpenBAS stack is modular and uses multiple Docker Compose files for easier configuration:

> [!IMPORTANT]
> Remember to create a .env file from .env.sample and customize the configuration as needed.

To start OpenBAS with the essential services, run:
```bash
   docker compose up -d
```

To start OpenBAS with the Caldera executor (Caldera used as an agent), run:
```bash
   docker-compose -f docker-compose.atomic-red-team.yml up -d
```

