# AI Guiders — handbook

Публичный справочник организации: миссия, ценности, границы, как работаем в среде.

**Читать:** **[wiki → Home](https://github.com/AI-Guiders/handbook/wiki)** — канонический текст живёт там, не в этом README.

| Контур | Где |
|--------|-----|
| **Handbook (wiki)** | https://github.com/AI-Guiders/handbook/wiki |
| **KB для агентов** | [kb-public](https://github.com/AI-Guiders/kb-public) · [wiki](https://github.com/AI-Guiders/kb-public/wiki/Home) |
| **Open stack** | [AI-Guiders](https://github.com/AI-Guiders) |
| **Тексты и карточки проектов** | [karataevdmitry.github.io](https://karataevdmitry.github.io/) |

## Как править handbook

**Через GitHub:** [Wiki](https://github.com/AI-Guiders/handbook/wiki) → страница → Edit.

**В этом репо (удобно в IDE):** каталог **`wiki/`** — те же `.md`, что на GitHub Wiki. После правок синхронизируй в wiki-репозиторий:

```powershell
git clone https://github.com/AI-Guiders/handbook.wiki.git
Copy-Item -Recurse -Force wiki\* handbook.wiki\
cd handbook.wiki
git add -A
git status
git commit -m "docs(handbook): …"
git push origin master
```

`_Sidebar.md` в **`wiki/`** — боковое меню wiki. Альтернатива: правки только в `handbook.wiki` без каталога `wiki/` в этом репо.

## Структура wiki (оглавление)

- [Миссия и цели](https://github.com/AI-Guiders/handbook/wiki/Миссия-и-цели)
- [Ценности, правила и границы команды](https://github.com/AI-Guiders/handbook/wiki/Ценности,-правила-и-границы-команды)
- [С кем мы не работаем](https://github.com/AI-Guiders/handbook/wiki/С-кем-мы-не-работаем)
- [Первые принципы среды](https://github.com/AI-Guiders/handbook/wiki/Первые-принципы-среды)
- [Как работать в среде каждый день](https://github.com/AI-Guiders/handbook/wiki/Как-работать-в-среде-каждый-день)
- [Протокол режимов WORK и HUMAN](https://github.com/AI-Guiders/handbook/wiki/Протокол-режимов-WORK-и-HUMAN)
- [Чеклист первой недели](https://github.com/AI-Guiders/handbook/wiki/Чеклист-первой-недели)
- [Карта wiki и навигация](https://github.com/AI-Guiders/handbook/wiki/Карта-wiki-и-навигация)
- [Встречи](https://github.com/AI-Guiders/handbook/wiki/Встречи)

Полный список страниц — в боковой панели на [wiki Home](https://github.com/AI-Guiders/handbook/wiki).
