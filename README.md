# DRAGONFLY — скиллы Claude Code

Набор [Taste Skill](https://github.com/Leonxlnx/taste-skill) (MIT). Скиллы лежат в `.claude/skills/`, поэтому Claude Code подхватывает их сам в любой сессии с этим репозиторием.

| Скилл | Когда применять |
|---|---|
| `design-taste-frontend` | Основной. Новый сайт или страница с нуля: арт-дирекшн, реальные изображения, проверка в браузере |
| `redesign-existing-projects` | Улучшить существующую страницу без переписывания |
| `full-output-enforcement` | Запрет на сокращения и заглушки в коде |
| `high-end-visual-design` | Мягкий, дорогой визуал |
| `minimalist-ui` | Редакционный минимализм, монохром |
| `industrial-brutalist-ui` | Брутализм, швейцарская типографика (beta) |
| `brandkit` | Изображение бренд-кита: логотип, палитра, шрифты, мокапы |
| `imagegen-frontend-web` / `imagegen-frontend-mobile` | Макеты-изображения сайта или экранов приложения |
| `image-to-code` | Вёрстка по сгенерированному референсу |
| `stitch-design-taste` | Правила для Google Stitch |
| `gpt-taste` | Вариант с упором на GSAP-анимацию |
| `design-taste-frontend-v1`, `design-taste-frontend-v2-experimental` | Прежние версии основного скилла |

Вызов: `/design-taste-frontend` или просто описать задачу. Скриптам основного скилла нужны Node 22+ и Chrome.

Лицензия: `.claude/skills/TASTE-SKILL-LICENSE`.
