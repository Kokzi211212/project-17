# RUN_INSTRUCTIONS.md

## 1. Подготовка

- Убедитесь, что установлены:
    - Docker Desktop (Windows)
    - WSL-Ubuntu 22.04 (или выше) с установленным Ansible
    - VS Code с расширением “Remote – WSL” (для удобства)

---

## 2. Запуск в PowerShell (Windows)

1. Откройте **PowerShell** от имени пользователя (не обязательно администратора).
2. Перейдите в папку проекта:
   ```powershell
   cd C:\ansible-wordpress

## 3. Подготовить репозиторий

1. Инициализируйте Git (если ещё не):
   ```bash
   cd C:\ansible-wordpress
   git init
   git add .
   git commit -m "Домашка: Ansible + Docker-Compose WordPress"