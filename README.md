# Репозиторий для Sileo — Nulls Brawl Tweak

Как добавить в Sileo и устанавливать через него.

## Быстрый способ — GitHub Pages

### 1. Создай репозиторий на GitHub
- Зайди на github.com
- **New repository** → например `nullsbrawl-tweak-repo`
- **Public**

### 2. Залей файлы
В репо должны лежать в корне:
- `com.nulls.brawltweak_1.0.0-4+debug_iphoneos-arm64.deb`
- `Packages`
- `Packages.gz`

### 3. Включи GitHub Pages
- В репо: **Settings** → **Pages**
- **Source:** Deploy from a branch
- **Branch:** main, папка / (root)
- Сохрани

### 4. Добавь репо в Sileo
- Подожди 1–2 минуты
- В Sileo: **Sources** → **+** (Add Source)
- Вставь URL:
  ```
  https://ТВОЙ_ЮЗЕРНАМЕ.github.io/nullsbrawl-tweak-repo/
  ```
- Нажми **Add Source**
- Обнови источники (Pull to refresh)
- Установи **Nulls Brawl Tweak**

### Альтернатива — Raw GitHub
Если Pages не настроился, можно попробовать:
```
https://raw.githubusercontent.com/ТВОЙ_ЮЗЕРНАМЕ/nullsbrawl-tweak-repo/main/
```
