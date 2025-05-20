# Terraform on Azure

A collection of practical, ready-to-use Terraform examples for provisioning and managing Azure infrastructure and services.

## ✨ What You'll Find

This repository contains small, self-contained Terraform projects that provision common Azure services. Each example is focused on one specific use case or service.

## 📁 Structure

Each example lives in its own folder (e.g., `/<example>`), and includes:

- `main.tf` – the core Terraform configuration
- `variables.tf` – input variables
- `outputs.tf` – output definitions
- `README.md` – scenario description and usage instructions

## ✅ Prerequisites

Before you start, make sure you have:

- [Terraform CLI](https://developer.hashicorp.com/terraform/downloads) installed
- An active [Azure subscription](https://azure.microsoft.com/free/)
- Logged in via the [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)  
  ```bash
  az login
  ````

## 🚀 Getting Started

1. Navigate into an example folder

2. Initialize Terraform:

```bash
terraform init
```

3. Preview the execution plan:

```bash
terraform plan
```

4. Apply the configuration:

```bash
terraform apply
```

> 💡 Don't forget to run terraform destroy when you're done to avoid unnecessary charges.

## 🤝 Contributing

Want to share your own example or improve an existing one? Contributions are welcome!

* Fork the repo

* Add your example under `/<your-example>`

* Include a README.md with a description

* Open a pull request

## 📜 License

This project is licensed under the [MIT License](./LICENSE).

👨🏻‍💻 Author

Created by [Andreas Gwosdz](https://www.linkedin.com/in/andreasgwosdz/) – I help developers build faster, ship more often, and run securely on Microsoft Azure.