# 🚀 kubectl_configs

A curated collection of `kubectl` configurations, usage examples, and quick-start guides to help you master Kubernetes CLI like a pro. Ideal for DevOps engineers, SREs, and Kubernetes learners.

---

## 📘 Table of Contents

- [🧰 Useful `kubectl` Commands](#-useful-kubectl-commands)
- [📌 Examples](#-examples)


---



## 🧠 Tips & Best Practices
- Always use namespaces to isolate environments.

- Use kubectl config set-context to switch between clusters easily.

- Use kubectl get all -n <namespace> to quickly see everything running in a namespace.

- Use -o yaml or -o json to inspect resources in detail.

---

## 📦 Requirements

- Kubernetes cluster (e.g., Minikube, GKE, EKS, etc.)
- `kubectl` installed on your local machine.
- Optional: Helm, Kustomize, and context switch tools like `kubectx`.

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/viktor134/k8s_config.git
   cd kubectl_configs
