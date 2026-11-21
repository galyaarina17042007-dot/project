# Типографика проекта ПрезиДЕНТ

В проекте используются две гарнитуры:
1. **Cormorant Garamond** (400, 500, 600, italic) — акцентная редакционная антиква для заголовков.
2. **Plus Jakarta Sans** (400, 500, 600, 700) — современный гротеск для основного текста и интерфейса.

Шрифты подключены через Google Fonts с `display=swap` и системными fallback-стеками (`Georgia, serif` и `-apple-system, BlinkMacSystemFont, sans-serif`) в `index.html` и `src/index.css`.
При необходимости полностью автономного офлайн-режима поместите `.woff2` файлы в эту директорию (`public/fonts/`) и раскомментируйте правила `@font-face` в `src/index.css`.
