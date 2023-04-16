# agent.omp.json
Тема для oh-my-posh в формате *.json

Установка (для PowerShell):
1. Сохранить файл темы в %HOMEPATH%\AppData\Local\Programs\oh-my-posh\themes
2. Добавьте следующий фрагмент в конец файла профиля PowerShell (code $PROFILE)
(файл обычно нахотится тут: %HOMEPATH%\Documents\WindowsPowerShell)
oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH\agent.omp.json" | Invoke-Expression
3. Обновите конфигурацию PS, выполнив: . $PROFILE
