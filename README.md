# Mohamed Ahmed Abdo

**Junior DevOps / Cloud Engineer | Giza, Egypt**

I build and document practical Linux, Docker, networking, and automation labs. My projects focus on reproducible setup, service health, safe operations, and clear verification steps. These are learning projects, not claims of production experience.

[Email](mailto:ahmedmohamed05147@gmail.com) · [LinkedIn](https://www.linkedin.com/in/mohamed-ahmed-6705b3303/) · [All repositories](https://github.com/mhmdhmdbdh2050?tab=repositories)

## Project architectures

Each diagram links to its repository. The diagrams summarize the checked-in project files; cloud resources provisioned outside these repositories are labeled as external where relevant.

### DevOps Automation Stack

<a href="https://github.com/mhmdhmdbdh2050/devops-automation-stack/tree/codex/reliable-operations-scripts"><img src="assets/architecture/devops-automation-stack.svg" alt="DevOps Automation Stack architecture: client, Nginx, Flask API, PostgreSQL, and Redis" width="100%"></a>

### Kubernetes Multi-App Ingress Lab

<a href="https://github.com/mhmdhmdbdh2050/k8s-multi-app-ingress-lab"><img src="assets/architecture/kubernetes-multi-app-ingress.svg" alt="Kubernetes Ingress routes three URL paths to three application services and deployments" width="100%"></a>

### WordPress Compose Stack

<a href="https://github.com/mhmdhmdbdh2050/docker-compose-wordpress-stack/tree/codex/secure-phpmyadmin-default"><img src="assets/architecture/wordpress-compose-stack.svg" alt="WordPress Compose architecture with Nginx, WordPress, MariaDB, and persistent storage" width="100%"></a>

### Docker Networking Lab

<a href="https://github.com/mhmdhmdbdh2050/Docker-networking-lab/tree/codex/reproducible-networking-lab"><img src="assets/architecture/docker-networking-lab.svg" alt="Four containers connected across two isolated Docker bridge networks, with one dual-homed container" width="100%"></a>

### Docker Custom Image Project

<a href="https://github.com/mhmdhmdbdh2050/Docker-custom-image-project"><img src="assets/architecture/docker-custom-image.svg" alt="Custom Nginx image serves a copied HTML page through host port 8082" width="100%"></a>

### Docker Volume Project

<a href="https://github.com/mhmdhmdbdh2050/Docker-volume-project"><img src="assets/architecture/docker-volume-project.svg" alt="Two separate containers exchange a file through a shared Docker volume" width="100%"></a>

### Simple Docker Project

<a href="https://github.com/mhmdhmdbdh2050/Simple_docker_project"><img src="assets/architecture/simple-docker-project.svg" alt="Browser reaches an Nginx container serving static files from the mounted html directory" width="100%"></a>

### Rock Paper Scissors Game

<a href="https://github.com/mhmdhmdbdh2050/Rock-paper-and-scissors-game"><img src="assets/architecture/rock-paper-scissors.svg" alt="Command-line game flow from player input through random computer choice to result" width="100%"></a>

## Selected projects

### [DevOps Automation Stack](https://github.com/mhmdhmdbdh2050/devops-automation-stack/tree/codex/reliable-operations-scripts)

A Docker Compose task API using Flask, PostgreSQL, Redis, and Nginx.

- Separates the frontend and backend networks; Nginx cannot connect directly to PostgreSQL or Redis.
- Provides liveness and dependency readiness endpoints, input validation, and database fallback when Redis is unavailable.
- Includes backup and restore scripts, API unit tests, and GitHub Actions validation.
- [Run instructions and checks](https://github.com/mhmdhmdbdh2050/devops-automation-stack/blob/codex/reliable-operations-scripts/README.md)

### [Docker Networking Lab](https://github.com/mhmdhmdbdh2050/Docker-networking-lab/tree/codex/reproducible-networking-lab)

A reproducible four-container lab with two isolated bridge networks and one multi-homed container.

- Checks expected connectivity and an isolated cross-network path.
- Provides Compose setup, verification, and teardown instructions.
- [Architecture and commands](https://github.com/mhmdhmdbdh2050/Docker-networking-lab/blob/codex/reproducible-networking-lab/README.md)

### [WordPress Compose Stack](https://github.com/mhmdhmdbdh2050/docker-compose-wordpress-stack/tree/codex/secure-phpmyadmin-default)

A learning stack using WordPress, MariaDB, Nginx, and persistent volumes.

- Keeps phpMyAdmin optional and bound to localhost when enabled.
- Documents environment setup and the need to rotate credentials that appeared in earlier Git history.
- [Setup and security notes](https://github.com/mhmdhmdbdh2050/docker-compose-wordpress-stack/blob/codex/secure-phpmyadmin-default/README.md)

## Skills demonstrated

Linux · Bash · Python · Git · Docker · Docker Compose · container networking · PostgreSQL · Redis · Nginx · GitHub Actions

## Learning roadmap

I am building further hands-on evidence in Kubernetes, infrastructure as code, AWS deployment, observability, and reliability engineering. I will add these areas to the featured projects when the implementations and verification steps are ready.

## Certifications

- AWS Certified AI Practitioner
- AWS Certified Cloud Practitioner

Credential details can be verified through the [AWS Certification Verification](https://aws.amazon.com/verification/) service.

## Education

**Cairo University — Faculty of Commerce**, graduated 2026.
