# ROSA CloudFormation Template

This repository contains a CloudFormation template to deploy a **Red Hat OpenShift Service on AWS (ROSA)** cluster.

## Template Overview

This CloudFormation template provisions the following resources:

- A **VPC** (Virtual Private Cloud) with two subnets.
- IAM **Roles** required for the OpenShift cluster.
- **ROSA cluster** with the desired OpenShift version.

## Parameters

- **ClusterName**: The name of the OpenShift cluster. Default is `my-rosa-cluster`.
- **ClusterVersion**: The OpenShift version to deploy (e.g., `4.12.0`).
- **VpcCidr**: CIDR block for the VPC.
- **Subnet1Cidr**: CIDR block for Subnet 1.
- **Subnet2Cidr**: CIDR block for Subnet 2.

## Prerequisites

- An **AWS account**.
- **IAM permissions** to create AWS resources, such as VPCs, subnets, IAM roles, and OpenShift clusters.
- **AWS CLI** installed and configured.
- **AWS CloudFormation** knowledge to deploy the template.

## Usage

To use this CloudFormation template, follow these steps:

1. Clone this repository to your local machine:
   ```bash
https://github.com/joshuaombasa/rosa-cloudformation-template/tree/main
