# devops-pipeline-gitflow-bamboo-docker
A straightforward and Simple DevOps pipeline showing how I manage code with Git Flow, automate builds with Bamboo, and package apps with Docker. It’s a real-life example of how I deliver and track software from development to deployment.
What it does:

Uses Git Flow to organize and manage code changes.

Automates build and deployment processes with Bamboo.

Packages applications into Docker containers for easy deployment.

Tracks everything from code commits to running environments for full traceability.

Why it matters:

This pipeline helps me deliver software faster, with fewer errors, and makes it easy to track what’s running where.

Technologies:

Git + Bitbucket

Bamboo CI/CD

Docker + Docker Hub

AWS

How to use:

Check the branches and Bamboo plans to see how code moves from development to production, and how Docker images are built and deployed.

Feel free to explore and adapt this pipeline for your own projects!# DevOps Pipeline Project: Git Flow, Bamboo CI, and Docker Traceability

🧭 Project Overview

This project demonstrates a complete DevOps pipeline that integrates Git Flow for version control, Bamboo for continuous integration, and Docker for containerized deployment. It ensures full traceability from source code to runtime environments.

🎯 Objectives

Implement structured branching using Git Flow

Automate builds and tagging with Bamboo CI

Package and deploy applications using Docker

Maintain traceability between commits, builds, and environments

🛠️ Technologies Used

Git + Bitbucket: Version control and collaboration

Bamboo CI/CD: Automated build and deployment

Docker + Docker Hub: Containerization and image registry

AWS: Target deployment environments

🔁 Git Flow Branching Strategy

Branch Type

Purpose

Notes

develop

Main line of development

Docker images built here

feature/

Isolated feature development

Named after JIRA issue, branched from develop

release/

Release preparation

Auto-created on successful build from develop

hotfix/

Urgent fixes

Branched from release, merged to release + develop

⚙️ CI/CD with Bamboo

Bamboo builds Docker images from the develop branch

Each build is tagged with ${bamboo_buildnumber}

Git commit hash is tagged with the same build number

Example:

Build #42 → Docker image: mycompany/leap-ui:42

Git commit 1d7bb1f tagged as 42

📦 Docker Image Management

Docker images are pushed to Docker Hub

Tagged with build number and environment name

Environment tags are floating (point to current version)

Example:

mycompany/leap-ui:42 → deployed to Dev

Tagged as mycompany/leap-ui:DEV

Git commit 1d7bb1f also tagged DEV

🚀 Deployment Pipeline

Bamboo identifies Docker image using build number

Image is deployed to target environment (Dev, QA, Prod)

Environment tag applied to Docker image and Git commit

🔍 Traceability Model

Identifier

Purpose

Build Number (42)

Immutable tag for traceability

Git Commit (1d7bb1f)

Source of the build

Docker Image (mycompany/leap-ui:42)

Built artifact

Environment Tag (DEV)

Floating tag for current deployment

📈 Benefits

Clear separation of development and release workflows

Automated, repeatable builds and deployments

Full traceability from source to runtime

Simplified rollback and auditability

📚 Artifacts and Visuals

Pipeline diagram

Git Flow branch chart

Docker tagging examples

Bamboo build metadata screenshot

📝 Conclusion

This DevOps pipeline provides a robust, traceable, and scalable foundation for managing software delivery. It aligns development workflows with deployment processes and ensures operational transparency across environments.

README

DevOps Pipeline Project

This repository contains a simple, real-life example of a DevOps pipeline that I use to manage software delivery.

What it does:

Uses Git Flow to organize and manage code changes.

Automates build and deployment processes with Bamboo.

Packages applications into Docker containers for easy deployment.

Tracks everything from code commits to running environments for full traceability.

Why it matters:

This pipeline helps me deliver software faster, with fewer errors, and makes it easy to track what’s running where.

Technologies:

Git + Bitbucket

Bamboo CI/CD

Docker + Docker Hub

AWS

How to use:

Check the branches and Bamboo plans to see how code moves from development to production, and how Docker images are built and deployed.

