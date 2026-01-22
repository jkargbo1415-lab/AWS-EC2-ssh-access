# AWS EC2 SSH Access and  IAM Role Setup

## Overview
This project documents hands-on work with Amazon EC2, including secure SSH access
using key pairs and preparing the instance for IAM role-based access

## EC2 SSH Access
-Successfully connected to an Amazon EC2 instance using SSH from powershell
-Authentication was performed using a PEM key file
-Instance login was confirmed without using passwords

**Key File Used**
-EC2-IAM-labkey.pem

**EC2 Public IPv4**
-18.220.64.24

## IAM Role
-IAM role created for EC2 service
-Role name 'EC2-S3-Access-Role
-Role will be attached to the EC2 instance to allow secure access to S3
without hard-coded credentials

## S3 Access Testing (Planned)
-AWS CLI will be used from inside the EC2 instance
-Planned command:
'''bash
aws s3 ls
