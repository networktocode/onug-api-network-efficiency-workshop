# onug-api-network-efficiency-workshop

# ONUG 2025 - API-Driven Network Efficiency Workshop

Welcome to the official repository for the **ONUG 2025 Workshop on API-Driven Network Efficiency**. This hands-on workshop is designed to introduce network and infrastructure engineers to the power of APIs and automation in managing modern enterprise networks.

## Workshop Overview

This workshop will demonstrate how to:

- Leverage APIs to gain visibility into your infrastructure
- Automate network operations using Python and API calls
- Build and interact with a sample API server using `FastAPI`
- Perform basic observability and remediation through scripting

The session includes guided labs where participants interact with tools and code in a controlled environment. The goal is to empower attendees to walk away with practical skills they can apply immediately in their environments.

## Prerequisites

Before the workshop, ensure you have the following:

- A modern web browser (Chrome, Firefox, Edge)
- Access to the workshop portal (credentials provided during the session)
- Familiarity with basic Python and HTTP APIs (helpful but not required)

## Repository Structure

``bash
.
├── README.md              # You're here!
├── scripts/               # Python scripts for API interaction and automation
├── lab-guides/            # Step-by-step guides for each lab exercise
├── assets/                # Workshop slides and presenter materials
└── api-server/            # FastAPI-based simulated API server (optional local deployment)
 Lab Instructions
The workshop consists of multiple self-contained labs:

Introduction to REST APIs

Using Python to Call APIs

Working with a Simulated API Server (FastAPI)

Automating Network Observability

Triggering Remediation Actions via API

Each lab contains:

A lab guide (PDF/Markdown)

Python scripts or Jupyter notebooks

Sample JSON responses and curl examples

To get started with a lab:

cd lab-guides
open Lab1-REST-API-Intro.md

Then follow along with the script or use the browser-based environment provided at the workshop.

 Workshop Tools Access
All tools are accessible via the Workshop Portal, available at:

 https://onug2025-labportal.example.com
Use the credentials provided during the event. If you're following this on your own:

Clone this repository

Optionally, run the simulated API server locally:

cd api-server
uvicorn main:app --reload

 Presentation & Scripts
assets/ONUG 2025 - API-Driven Network Efficiency Workshop (Presentation).pdf
The official workshop slides.

assets/ONUG 2025 - API-Driven Network Efficiency Workshop (Presenter Script).docx
Full presenter notes and lab walkthroughs.

 Key Technologies
Python 3.10+

FastAPI

requests library

JSON & HTTP

RESTful API principles

 Acknowledgements
This workshop is part of ONUG 2025 and developed in collaboration with leading experts in network automation and cloud infrastructure.

 Questions or issues?
Please open an issue or discussion in this repo.
