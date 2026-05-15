# AI Guiders — handbook

Публичный справочник организации: миссия, ценности, границы, как работаем в среде.

| Контур | Где |
|--------|-----|
| **Handbook (эта org)** | Wiki: https://github.com/AI-Guiders/handbook/wiki *(после первого включения, см. ниже)* |
| **KB для агентов** | [kb-public wiki](https://github.com/AI-Guiders/kb-public/wiki/Home) |

## Включить wiki (один раз)

1. Открой https://github.com/AI-Guiders/handbook/wiki  
2. **Create the first page** → заголовок `Home` → Save (можно пустой текст).  
3. Локально выполни (из корня клона этого репо):

```powershell
git clone https://github.com/AI-Guiders/handbook.wiki.git
Copy-Item -Recurse wiki-staging\* handbook.wiki\
cd handbook.wiki
git add -A
git commit -m "Migrate handbook wiki from GitLab"
git push origin master
```

Содержимое страниц лежит в каталоге **`wiki-staging/`** (зеркало до push в wiki).

## Open stack

https://github.com/AI-Guiders
