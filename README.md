# Devops workshops feat. Inetum

## Description
Code in this repository was written during AKAI x Inetum DevOps workshops, which took place 27/04/22. The aim of it was to develop a simple Azure pipeline with Github Actions and Terraform

## Content
* a Github Actions workflow designed to do the following in order:
  * **validate** the Terraform files
  * **release** the Terraform
  * **deploy** Kubernetes cluster
  * **destroy** the deployed cluster 
* terraform files describing a Kubernetes cluster and some variables
* deployment1.yaml describing a "Hello world" Azure Kubernetes Service application