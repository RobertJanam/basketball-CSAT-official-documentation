# BASKETBALL COURTSIDE ANALYTICS AND TRACKER

[![Django](https://img.shields.io/badge/Django-6.0.2-092E20?style=for-the-badge&logo=django)](https://www.djangoproject.com/)
[![Django REST Framework](https://img.shields.io/badge/DRF-3.16.1-red?style=for-the-badge&logo=django)](https://www.django-rest-framework.org/)
[![Python](https://img.shields.io/badge/Python-3.12.12-3776AB?style=for-the-badge&logo=python)](https://www.python.org/)
[![JWT](https://img.shields.io/badge/JWT-Auth-000000?style=for-the-badge&logo=json-web-tokens)](https://jwt.io/)

## 📋 Table of Contents

- [Purpose](#documentation)
- [Project Description](#project-description)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
    - [Environment Setup](#environment-setup)
    - [CI/CD Pipeline](#cicd-pipeline)

---

## Purpose

This repository documents my entire journey of building this application, focusing on what I did and the reasoning behind my decisions.

I firmly believe that everyone should have access to knowledge. While it may seem ironic to talk about openness while keeping the source code in a private repository, this project is proprietary software. However, you don't need my exact code to build something similar. 

Ultimately, this documentation serves two purposes:
**1. Showcase capability** 
- It allows visitors to explore the architecture and understand my technical capabilities.

**2. Developer guide:** 
- It provides a comprehensive blueprint for any developer interested in building a similar project from scratch.

---

## Project Description

The **Kenyan Basketball Federation Premiere League's**, especially at the lower divisions, individual teams struggle with game data tracking and analysis, often relying on physical paper records or basic spreadsheet tools that don't provide meaningful insights. In some cases, coaches have access to technologies that attempt to solve this problem, but they normally exclude players from direct participation. Coaches need better tools to track player performance, analyze game trends, and make data-driven decisions. Players have a right to view their individual performance and that of the team anytime.

**Basketball Courtside Analytics & Tracker** is a full stack web application built on `Progressive Web Application` (PWA) and `IndexedDB` to solve this problem. It provides a platform for coaches to record game statistics, manage teams, and receive automated performance analytics. CsAT (the name) goes further to provide intelligent decision support using concepts from `data mining`, `Business Intelligence` and `Retrieval-Augmented Generation` (RAG) to help coaches improve team performance.

The application focuses on making data entry simple while delivering powerful insights through calculated metrics like player averages, team leaderboards, and quarter-by-quarter performance trends.

---

## Technology Stack

| Category | Technology |
| :--- | :--- |
| **Framework** | Django >=5.2,<6.1 & Django REST Framework 3.18.3 |
| **Database** | PostgreSQL 16 (connected via pgAdmin 4) |
| **Authentication**| JWT (via djangorestframework-simplejwt) |
| **Frontend & Storage**| PWA & IndexedDB API |
| **DevOps / Environment**| Python 3.12, venv, pip, Docker, & CI/CD Pipelines (github actions, render) |
| **CORS** | django-cors-headers |
| **Other Tools** | python-dotenv for environment variables, Git for version control. |

---

## Getting Started
These instructions are meant to get the project up and running on your local machine for development and testing purposes.

---

### Environment Setup

Documentation for setting up your local environment using `venv` and [Docker](https://www.docker.com/).

- [Environment Setup Guide](docs/env_setup.md)

---

### CI/CD Pipeline

Documentation for the CI/CD pipeline built with [GitHub Actions](https://github.com), [Render](https://render.com/), and [Infisical](https://infisical.com/) for secrets integration.

- [CI/CD Deployment Guide](docs/cicd_pipeline.md)

---