# pm

> Вивести інформацію про застосунки на Android девайсі.
> More information: <https://developer.android.com/studio/command-line/adb#pm>.

- Вивести всі встановлені застосунки:

`pm list packages`

- Вивести всі встановлені системні застосунки:

`pm list packages -s`

- Вивести всі встановлені сторонні (3d-party) застосунки:

`pm list packages -3`

- Вивести застосунки, які підпадають під специфічні ключові слова:

`pm list packages {{ключове_слово1 ключове_слово2 ...}}`

- Вивести шлях до APK для специфічного застосунку:

`pm path {{app}}`
