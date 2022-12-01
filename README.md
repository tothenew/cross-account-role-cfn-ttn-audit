# cross-account-role-cfn-stack

## Introduction
A basic cloudformation template to create a cross account read only role. 

## How to use it?
1. Replace the `SOURCE AWS ACCOUNT NUMBER` with the actual account number from where you want to switch role to the actual account (in which this cloudformation stack will be created)

2. By default, it attaches readonly policy. This can be modified and extended as required.
