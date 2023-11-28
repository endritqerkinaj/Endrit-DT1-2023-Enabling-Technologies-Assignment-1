# DT1 2023 : Enabling Technologies, Assignment 1

AI Text Completion Service Deployment on GCP
Executive Summary

This README provides the protocol for deploying an AI text completion service that complies with the DT1 2023: Enabling Technologies, Assignment 1. It integrates a Docker-contained Flask proxy application with the Hugging Face API and employs a no-code Bubble interface for user interactions.

Deployment Strategy
------
This deployment adheres to the assignment's learning cycles, encompassing Software Architecture, Bubble, API Design, and Cloud Computing. The strategy unfolds across several phases, each fulfilling a component of the learning cycle.

Account Initialization and Environment Configuration
------
• GitHub Account Creation: Established for version control of the proxy's source code, aligning with the API Design and Software Architecture cycles.
• Docker Hub Registration: Set up for managing the Docker image of the Flask proxy, relevant to the Cloud Computing and Software Architecture cycles.
• Hugging Face Account Setup: For accessing the large language model APIs, touching on API Design and Cloud Computing.
• Google Cloud Account Activation: To deploy the proxy and interface, catering to the Cloud Computing cycle.

Local Environment Preparation
------
• Local Terminal Configuration: The native Mac Terminal was used, ensuring a consistent development environment across operations.
• Docker Desktop Installation: To manage the lifecycle of Docker containers, important for the Software Architecture and Cloud Computing cycles.

Codebase Integration and Containerization
------
• Repository Cloning: The Flask application's source code was cloned, encapsulating all necessary dependencies for the proxy.
• Docker Image Construction and Distribution: The Docker image was constructed and distributed via Docker Hub, demonstrating practical skills in Software Architecture and Cloud Computing.

Cloud Infrastructure Deployment and Service Provisioning
------
• Virtual Machine Setup on GCP: The Flask proxy was deployed on a GCP VM, with the chosen OS being Ubuntu as per the assignment note.
• Security Protocols Establishment: Firewalls were meticulously configured, illustrating the application of Cloud Computing knowledge.



Frontend Development and API Integration
------
• Bubble Frontend Architecture: Developed the service frontend on Bubble, showcasing the ability to create a user interface without code, as highlighted in the Bubble learning cycle.

Backend-Frontend Synthesis and Script Implementation
------
• API Communication Scripting: Authored and embedded JavaScript within the Bubble platform, tying in API Design and Cloud Computing.

Service Validation and Documentation
------
• System Testing: The full-stack service's seamless operation was confirmed using curl as suggested in the supplementary materials, reinforcing API Design and Cloud Computing skills.

• Documentation Finalization: The README was detailed to reflect the system architecture and deployment process.
