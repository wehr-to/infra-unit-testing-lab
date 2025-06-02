# 🧪 infra-unit-testing-lab

This repository explores **unit testing in infrastructure and automation workflows** — ensuring that what we provision, configure, or secure behaves as expected *before* it hits production.

While often overlooked in DevOps or security engineering, unit testing is the gold standard in software — and this repo applies that mindset to Terraform, Ansible, Bash, Python, and CI/CD environments.

## 🎯 Why This Repo Exists

Most infrastructure teams validate through hope and rollback. This project proves you can:

- Write **unit tests** for your provisioning logic
- Use **mock inputs** to simulate various infra states
- Assert that security, tags, configs, and compliance rules are enforced
- Integrate these checks into pipelines and automated workflows

## 🧱 What’s Covered

| Area                  | Description |
|-----------------------|-------------|
| `terraform-tests/`     | Unit tests using `terratest` and `infracost` assertions |
| `ansible-tests/`       | Role and task-level tests using `molecule` and `testinfra` |
| `bash-tests/`          | Shell script testing with `bats-core` |
| `python-tests/`        | Infra automation logic tested with `pytest` |
| `ci-integration/`      | GitHub Actions and pre-commit test runners |
| `mock-data/`           | Sample inputs and fixture files for local testing |
| `docs/`                | Examples, reasoning, and test philosophy |

## 🔧 Tools & Frameworks Used
- Terratest (Go)
- Molecule + Testinfra (Python)
- Pytest
- BATS-core (Bash testing)
- Pre-commit hooks
- GitHub Actions CI

## 👥 Who Should Use This
- DevOps engineers writing reusable infrastructure code
- Security engineers validating control enforcement
- Cloud engineers provisioning Terraform in pipelines
- Blue teamers ensuring hardened defaults stay enforced



