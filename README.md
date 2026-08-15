# hook-e2e-s95-middle

hook-e2e-s95-middle service

## Stack
- Langage : ${{ values.language }}
- CI/CD : Tekton → Harbor → ArgoCD
- Plateforme : DxP

## Démarrage rapide
```bash
# Cloner le repo
git clone <repo-url>
cd hook-e2e-s95-middle

# Lancer en local
docker build -t hook-e2e-s95-middle .
docker run -p 8080:8080 hook-e2e-s95-middle
```
