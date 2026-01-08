# devops-pipeline-gitflow-bamboo-docker
A straightforward and Simple DevOps pipeline showing how I manage code with Git Flow, automate builds with Bamboo, and package apps with Docker. It’s a real-life example of how I deliver and track software from development to deployment.
🧭 Project Overview

This project shows a real-life DevOps pipeline that I use to manage software delivery from start to finish.

🎯 Objectives

Organize code changes using Git Flow branching.

Automate builds and deployments with Bamboo.

Package applications into Docker containers.

Keep track of code, builds, and deployments for easy traceability.

🛠️ Technologies Used

Git + Bitbucket for version control.

Bamboo CI/CD for automation.

Docker + Docker Hub for containerization.

AWS for deployment environments.

🔁 Git Flow Branching Strategy

Branch Type

Purpose

Notes

develop

Main development branch

Docker images are built here

feature/

Work on new features

Branched from develop

release/

Prepare releases

Created automatically from develop

hotfix/

Quick fixes

Branched from release, merged back to release and develop

⚙️ CI/CD with Bamboo

Bamboo builds Docker images from the develop branch.

Each build gets a unique build number tag.

The Git commit is tagged with the same build number.

Example:

Build #42 creates Docker image mycompany/leap-ui:42.

Git commit 1d7bb1f is tagged as 42.

📦 Docker Image Management

Docker images are pushed to Docker Hub.

Images are tagged with build numbers and environment names.

Environment tags point to the current deployed version.

Example:

Image mycompany/leap-ui:42 deployed to Dev environment.

Tagged as mycompany/leap-ui:DEV.

Git commit 1d7bb1f also tagged DEV.

🚀 Deployment Pipeline

Bamboo identifies the Docker image by build number.

The image is deployed to the target environment (Dev, QA, Prod).

Environment tags are applied to Docker images and Git commits.

🔍 Traceability Model

Identifier

Purpose

Build Number (42)

Unique tag for traceability

Git Commit (1d7bb1f)

Source code reference

Docker Image (mycompany/leap-ui:42)

Built artifact

Environment Tag (DEV)

Points to current deployment

📈 Benefits

Clear separation of development and release workflows.

Automated and repeatable builds and deployments.

Full traceability from code to runtime.

Easy rollback and auditing.

README

DevOps Pipeline Project

This repository contains a simple, real-life example of a DevOps pipeline I use to manage software delivery.

What it does:

Organizes code changes with Git Flow.

Automates build and deployment with Bamboo.

Packages applications into Docker containers.

Tracks code commits, builds, and deployments for full traceability.

Why it matters:

This pipeline helps deliver software faster, with fewer errors, and makes it easy to see what’s running where.

Technologies:

Git + Bitbucket

Bamboo CI/CD

Docker + Docker Hub

AWS

How to use:

Check the branches and Bamboo plans to see how code moves from development to production, and how Docker images are built and deployed.

Feel free to explore and adapt this pipeline for your own projects!# DevOps Pipeline Project: Git Flow, Bamboo CI, and Docker Traceability

🧭 Project Overview

This project shows a real-life DevOps pipeline that I use to manage software delivery from start to finish.

🎯 Objectives

Organize code changes using Git Flow branching.

Automate builds and deployments with Bamboo.

Package applications into Docker containers.

Keep track of code, builds, and deployments for easy traceability.

🛠️ Technologies Used

Git + Bitbucket for version control.

Bamboo CI/CD for automation.

Docker + Docker Hub for containerization.

AWS for deployment environments.

🔁 Git Flow Branching Strategy

Branch Type

Purpose

Notes

develop

Main development branch

Docker images are built here

feature/

Work on new features

Branched from develop

release/

Prepare releases

Created automatically from develop

hotfix/

Quick fixes

Branched from release, merged back to release and develop

⚙️ CI/CD with Bamboo

Bamboo builds Docker images from the develop branch.

Each build gets a unique build number tag.

The Git commit is tagged with the same build number.

Example:

Build #42 creates Docker image mycompany/leap-ui:42.

Git commit 1d7bb1f is tagged as 42.

📦 Docker Image Management

Docker images are pushed to Docker Hub.

Images are tagged with build numbers and environment names.

Environment tags point to the current deployed version.

Example:

Image mycompany/leap-ui:42 deployed to Dev environment.

Tagged as mycompany/leap-ui:DEV.

Git commit 1d7bb1f also tagged DEV.

🚀 Deployment Pipeline

Bamboo identifies the Docker image by build number.

The image is deployed to the target environment (Dev, QA, Prod).

Environment tags are applied to Docker images and Git commits.

🔍 Traceability Model

Identifier

Purpose

Build Number (42)

Unique tag for traceability

Git Commit (1d7bb1f)

Source code reference

Docker Image (mycompany/leap-ui:42)

Built artifact

Environment Tag (DEV)

Points to current deployment

📈 Benefits

Clear separation of development and release workflows.

Automated and repeatable builds and deployments.

Full traceability from code to runtime.

Easy rollback and auditing.

README

DevOps Pipeline Project

This repository contains a simple, real-life example of a DevOps pipeline I use to manage software delivery.

What it does:

Organizes code changes with Git Flow.

Automates build and deployment with Bamboo.

Packages applications into Docker containers.

Tracks code commits, builds, and deployments for full traceability.

Why it matters:

This pipeline helps deliver software faster, with fewer errors, and makes it easy to see what’s running where.

Technologies:

Git + Bitbucket

Bamboo CI/CD

Docker + Docker Hub

AWS

How to use:

Check the branches and Bamboo plans to see how code moves from development to production, and how Docker images are built and deployed.

Feel free to explore and adapt this pipeline for your own projects!# DevOps Pipeline Project: Git Flow, Bamboo CI, and Docker Traceability

🧭 Project Overview

This project shows a real-life DevOps pipeline that I use to manage software delivery from start to finish.

🎯 Objectives

Organize code changes using Git Flow branching.

Automate builds and deployments with Bamboo.

Package applications into Docker containers.

Keep track of code, builds, and deployments for easy traceability.

🛠️ Technologies Used

Git + Bitbucket for version control.

Bamboo CI/CD for automation.

Docker + Docker Hub for containerization.

AWS for deployment environments.

🔁 Git Flow Branching Strategy

Branch Type

Purpose

Notes

develop

Main development branch

Docker images are built here

feature/

Work on new features

Branched from develop

release/

Prepare releases

Created automatically from develop

hotfix/

Quick fixes

Branched from release, merged back to release and develop

⚙️ CI/CD with Bamboo

Bamboo builds Docker images from the develop branch.

Each build gets a unique build number tag.

The Git commit is tagged with the same build number.

Example:

Build #42 creates Docker image mycompany/leap-ui:42.

Git commit 1d7bb1f is tagged as 42.

📦 Docker Image Management

Docker images are pushed to Docker Hub.

Images are tagged with build numbers and environment names.

Environment tags point to the current deployed version.

Example:

Image mycompany/leap-ui:42 deployed to Dev environment.

Tagged as mycompany/leap-ui:DEV.

Git commit 1d7bb1f also tagged DEV.

🚀 Deployment Pipeline

Bamboo identifies the Docker image by build number.

The image is deployed to the target environment (Dev, QA, Prod).

Environment tags are applied to Docker images and Git commits.

🔍 Traceability Model

Identifier

Purpose

Build Number (42)

Unique tag for traceability

Git Commit (1d7bb1f)

Source code reference

Docker Image (mycompany/leap-ui:42)

Built artifact

Environment Tag (DEV)

Points to current deployment

📈 Benefits

Clear separation of development and release workflows.

Automated and repeatable builds and deployments.

Full traceability from code to runtime.

Easy rollback and auditing.

README

DevOps Pipeline Project

This repository contains a simple, real-life example of a DevOps pipeline I use to manage software delivery.

What it does:

Organizes code changes with Git Flow.

Automates build and deployment with Bamboo.

Packages applications into Docker containers.

Tracks code commits, builds, and deployments for full traceability.

Why it matters:

This pipeline helps deliver software faster, with fewer errors, and makes it easy to see what’s running where.

Technologies:

Git + Bitbucket

Bamboo CI/CD

Docker + Docker Hub

AWS

How to use:

Check the branches and Bamboo plans to see how code moves from development to production, and how Docker images are built and deployed.
