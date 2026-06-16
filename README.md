# ATELIER FROM IMAGE TO CLUSTER

## Description
Industrialisation du cycle de vie d'une application Nginx personnalisée avec **Packer**, déployée sur un cluster **Kubernetes K3d** via **Ansible**, dans un environnement **GitHub Codespaces**.

---

## Prérequis
- GitHub Codespaces
- Docker
- kubectl

---

## Installation des outils

```bash
make install
```

Installe automatiquement : K3d, Packer, Ansible

---

## Utilisation

### 1. Créer le cluster K3d
```bash
make cluster
```

### 2. Builder l'image Nginx avec Packer
```bash
make build
```

### 3. Importer l'image dans K3d
```bash
make import
```

### 4. Déployer via Ansible
```bash
make deploy
```

### 5. Tout en une seule commande
```bash
make all
```

---

## Architecture
---

## Auteur
Paul Yvan VOUNDI ABESSOLO - EPSI Paris M1 EISI 2026
