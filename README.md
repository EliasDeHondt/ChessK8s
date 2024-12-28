![logo](https://eliasdh.com/assets/media/images/logo-github.png)
# 💙🤍README🤍💙

## 📘Table of Contents

1. [📘Table of Contents](#📘table-of-contents)
2. [🖖Introduction](#🖖introduction)
3. [📚How to deploy](#📚how-to-deploy)
4. [🔗Links](#🔗links)

---

## 🖖Introduction

I kindly request your thorough examination and absorption of the comprehensive documentation incorporated within the confines of this repository. Your diligent review of the diverse materials provided herein will undoubtedly enhance your understanding of the intricacies and nuances associated with the contents therein.

Please also see following documents:
- [LICENSE](LICENSE.md)
- [SECURITY](SECURITY.md)
- [CONTRIBUTING](CONTRIBUTING.md)
- [CODE OF CONDUCT](CODE-OF-CONDUCT.md)

## 📚How to deploy

### 🚀Kubernetes

- Step 1: Deploy the application:
```bash
kubectl apply -f https://raw.githubusercontent.com/EliasDeHondt/ChessK8s/refs/heads/main/Kubernetes/kubernetes.yaml
```

- Step 2: Get the ingress:
```bash
kubectl get ingress
```

- If you want to delete the deployment:
```bash
kubectl delete -f https://raw.githubusercontent.com/EliasDeHondt/ChessK8s/refs/heads/main/Kubernetes/kubernetes.yaml
```

### 🚀Docker

- Step 1: Deploy the application:
```bash
curl -s https://raw.githubusercontent.com/EliasDeHondt/ChessK8s/refs/heads/main/Docker/compose.yaml | sudo docker compose -f - up -d
```

- If you want to delete the deployment:
```bash
curl -s https://raw.githubusercontent.com/EliasDeHondt/ChessK8s/refs/heads/main/Docker/compose.yaml | sudo docker compose -f - down
```

## 🔗Links
- 👯 Web hosting company [EliasDH.com](https://eliasdh.com).
- 📫 How to reach us elias.dehondt@outlook.com