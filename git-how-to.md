# GitHub Setup Instructions

## 1. Как создать SSH ключ
ssh-keygen -t ed25519 -C "your_email@example.com"

## 2. Как добавить ключ в аккаунт на GitHub
cat ~/.ssh/id_ed25519.pub
# скопировать и вставить на GitHub → Settings → SSH and GPG keys → New SSH key

## 3. Как склонировать репозиторий
git clone git@github.com:username/Fafurin.git


