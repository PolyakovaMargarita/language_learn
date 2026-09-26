# public/ — GitHub Pages + скриншоты для сторов

## Юридические страницы (выложить на GitHub Pages)

| Файл | URL после публикации |
|------|----------------------|
| `index.html` | https://polyakovamargarita.github.io/languageLearn/ |
| `privacy.html` | https://polyakovamargarita.github.io/languageLearn/privacy.html |
| `support.html` | https://polyakovamargarita.github.io/languageLearn/support.html |

Эти же URL уже прописаны в `src/constants/legal.ts` и открываются из **Настройки → О приложении** (Политика и Поддержка).

> Репозиторий на GitHub лучше оставить `languageLearn`, чтобы URL Pages совпал.

### Как включить GitHub Pages

1. Закоммитьте папку `public/` в репозиторий.
2. GitHub → **Settings → Pages**.
3. Source: **Deploy from a branch**.
4. Branch: `main` (или `master`), folder: **/public** (если доступно)  
   либо скопируйте содержимое `public/` в корень ветки `gh-pages`.
5. Подождите 1–2 минуты и откройте ссылки выше.
6. В App Store Connect / Play Console вставьте Privacy и Support URL.
7. Замените email `bip.support@example.com` на свой в:
   - `public/support.html`
   - `src/constants/legal.ts`

## Скриншоты

Исходники → готовые размеры:

| Папка | Размер | Куда грузить |
|-------|--------|--------------|
| `screenshots/iphone-6.7/` | 1290×2796 | App Store — iPhone 6.7" |
| `screenshots/iphone-6.5/` | 1284×2778 | App Store — iPhone 6.5" |
| `screenshots/ipad-12.9/` | 2048×2732 | App Store — iPad 12.9" |
| `screenshots/android-phone/` | 1080×1920 | Google Play — телефон |
| `screenshots/android-tablet-7/` | 1200×1920 | Google Play — 7" |
| `screenshots/android-tablet-10/` | 1600×2560 | Google Play — 10" |
| `screenshots/play/feature-graphic.png` | 1024×500 | Google Play Feature Graphic |

Файлы названы по смыслу экрана: `01-route`, `02-games`, `03-match3`, …

> Исходные скрины были ~470×1024 (симулятор). Для максимального качества Apple/Google лучше переснять на реальном устройстве в полном разрешении и снова прогнать ресайз. Текущие файлы уже в **нужных форматах** для загрузки.

## Рекомендуемый набор для витрины (5 кадров)

1. `01-route` — маршрут  
2. `02-games` или `09-games-list` — список игр  
3. `03-match3` — Сад слов  
4. `05-solitaire` или `06-runner` — геймплей  
5. `07-words` — словарь  
