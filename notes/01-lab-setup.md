# crAPI Lab Setup

## 1. Environment

The API security testing lab was configured on Kali Linux.

Tools used:

- Kali Linux
- Docker
- Docker Compose
- OWASP crAPI
- Burp Suite
- Postman

## 2. crAPI Setup

OWASP crAPI was used as the intentionally vulnerable API application for this security testing project.

The crAPI repository was cloned into the local testing environment.

## 3. Docker Deployment

The crAPI Docker directory was opened using:

`cd ~/API-Security-Project/crAPI/deploy/docker`

The application was started using:

`docker compose -f docker-compose.yml up -d`

## 4. Verify Containers

The following command was used to verify the running containers:

`docker ps`

The required crAPI containers were successfully running and reported as healthy.

## 5. Evidence

Screenshot:

`../screenshots/01-crapi-containers-running.png`

This confirms that the crAPI testing environment was successfully deployed and ready for API security testing.
