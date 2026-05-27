# NOTA — Записная книжка

> Приложение для заметок, целей, идей и задач. Тёмный editorial-дизайн.

## Скачать

Перейди в раздел [**Releases**](../../releases) и скачай установщик для своей платформы.

## Разработка

```bash
# Установить зависимости
npm install

# Запустить в режиме разработки
npm start

# Собрать установщик
npm run build        # все платформы (только на macOS)
npm run build:win    # Windows .exe
npm run build:mac    # macOS .dmg
npm run build:linux  # Linux .AppImage
```

## Релиз

Просто создай тег — GitHub Actions сам соберёт всё и выложит в Releases:

```bash
git tag v1.0.0
git push origin v1.0.0
```

## Технологии

- [Electron](https://www.electronjs.org/) — десктоп-обёртка
- [electron-builder](https://www.electron.build/) — сборка установщиков
- [GitHub Actions](https://github.com/features/actions) — CI/CD
- Чистый HTML/CSS/JS + `localStorage` для хранения данных
