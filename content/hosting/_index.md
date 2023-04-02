+++
archetype = "chapter"
title = "Hosting"
weight = 5
+++

This chapter provides an introduction to popular hosting providers.

## [Binder](binder)

Binder is a cloud-based platform that allows users to share and 
execute Jupyter Notebooks as interactive environments. 
It utilizes Docker containers to create custom environments 
for notebooks and provides public and private hosting options. 
Binder runs on a public infrastructure and is provided as a free 
service by the Binder team.

## [BinderHub](binderhub)

BinderLab is a development environment for JupyterLab that runs on top of Binder. 
It allows users to create and run custom JupyterLab environments 
and provides a collaborative workspace for multiple users. 
Unlike Binder, BinderLab is designed for development purposes 
rather than just sharing and executing notebooks.

## [BitBucket](bitbucket)

BitBucket is a popular hosting provider for Git repositories. 
It provides users with a cloud-based platform to store and manage 
their Git projects, and includes features such as code collaboration 
and continuous integration.

## [DockerHub](dockerhub)

DockerHub is a cloud-based repository for Docker images and containers. It provides users with a centralized location to store, manage and share their Docker images, and allows for easy distribution and deployment of containerized applications. DockerHub also provides features such as automated builds, which allows users to automatically build Docker images from source code repositories.

## [GitHub](github)

GitHub is a widely used platform for hosting Git repositories, 
collaborating on code, and managing projects. 
In addition to hosting Git repositories, GitHub provides 
users with a variety of tools for project management, 
such as issue tracking, code reviews, and continuous integration.

## [GitHub Pages](github-pages)

GitHub Pages is a free service for hosting static websites 
directly from a GitHub repository. 
Users can create websites using static site generators or 
by manually writing HTML, CSS, and JavaScript. 
GitHub Pages also provides custom domain support, 
SSL encryption, and GitHub Actions for automating website builds and deployments.

## [JupyterHub](jupyterhub)

JupyterHub is a multi-user server for Jupyter Notebooks that allows multiple users to access and use the same Jupyter Notebook environment simultaneously.

## Choosing Hosting for Jupyter Notebooks

The choice of platform to share a Jupyter Notebook depends on the 
intended use case, audience, and level of collaboration required. 

Here are some guidelines for when to use each platform.

### GitHub

Use GitHub to share Jupyter Notebooks that are part of a larger project, 
and to collaborate on code with others. 
GitHub provides version control, code reviews, and issue tracking, 
making it an ideal platform for collaborating on code. 
However, GitHub is not optimized for executing Jupyter Notebooks 
in the cloud, and 
users may need to download and run the notebooks locally to interact with them.

### Binder

Use Binder to share Jupyter Notebooks that require 
specific software dependencies, 
or to share a single notebook with a small group of users. 
Binder provides a cloud-based environment 
that allows users to interact with Jupyter Notebooks 
directly in their web browser, 
without having to install any software. 
However, Binder is not intended for large-scale collaboration, 
and may not be suitable for running notebooks with 
high computational requirements.

### BinderHub

Use BinderHub to create a custom, scalable cloud-based environment 
for running Jupyter Notebooks. 
BinderHub is built on top of Kubernetes and Docker, 
providing automatic scaling and load balancing 
for your Jupyter Notebook environments. 
BinderHub is suitable for sharing Jupyter Notebooks with a large audience, 
and provides customizable environments and version control integration. 
However, setting up and managing a BinderHub instance 
requires technical expertise and resources.

### JupyterHub 

Use JupyterHub to provide a shared computing environment 
for a group of users. 
JupyterHub allows multiple users to access and use the same 
Jupyter Notebook environment simultaneously, 
making it suitable for classroom settings or collaborative research projects. 
JupyterHub provides user authentication and access control, 
and can be customized to provide specific software dependencies
 and resources for different groups of users. 
 However, setting up and managing a JupyterHub instance 
 requires technical expertise and resources.
