# DevOps 101: Terraform, Ansible & OpenStack

This repository contains support files for a tutorial regarding Terraform, Ansible and OpenStack infrastructure automation. It demonstrates how to provision and configure cloud infrastructure using Infrastructure as Code (IaC) principles.

## Project Overview

This project showcases:
- **Terraform**: Infrastructure provisioning on OpenStack
- **Ansible**: Configuration management and application deployment
- **OpenStack**: Cloud infrastructure platform
- **Vagrant**: Local development environment

## Repository Structure

- `terraform-*.tf` - Terraform configuration files for OpenStack resources
- `playbook.yml` - Main Ansible playbook for system configuration
- `roles/` - Ansible roles for various system components
- `Vagrantfile` - Vagrant configuration for local testing
- `docs/` - Comprehensive Devin AI documentation and wiki pages

## Quick Start

1. **Prerequisites**: Ensure you have Terraform, Ansible, and Vagrant installed
2. **Configuration**: Update `terraform.tfvars` with your OpenStack credentials
3. **Provision**: Run `terraform apply` to create infrastructure
4. **Configure**: Execute `ansible-playbook -i hosts playbook.yml` to configure systems

## Devin AI Documentation

This repository includes comprehensive documentation for using Devin AI with DevOps workflows. Visit the [Devin Wiki Pages](./docs/) to learn:

- How to effectively use Devin for infrastructure automation
- Best practices for DevOps workflows with AI assistance
- Specific guidance for Terraform and Ansible projects
- Integration strategies for CI/CD pipelines

## Getting Started with Devin

If you're new to using Devin AI for DevOps tasks, start with:
1. [When to Use Devin](./docs/devin-essentials/when-to-use-devin.md)
2. [DevOps-Specific Setup](./docs/onboarding-devin/devops-specific-setup.md)
3. [Terraform Automation](./docs/devops-use-cases/terraform-automation.md)

## License

This project is licensed under the terms specified in the LICENSE file.

## Contributing

Contributions are welcome! Please read through the Devin documentation in the `docs/` folder to understand how AI-assisted development can enhance your contributions to this project.
