# GitTutorial

## Список корисних команд для роботи з git

1. git clone - копіює репозиторій(папку з файлами) на компютер
2. git branch "branchName" - створює гілку з назвою "branchName"
3. git checkout "branchName" - переходить на гілку з назвою "branchName"
4. git checkout -b "branchName" - створюємо гілку з назвою "branchName" і переходимо на неї
5. git add . - зберігаємо зміни в файлах
6. git commit -m "commit message" - підписуємо збереженні зміни в файлах
7. git push - відправляємо зміни на сайт github
8. git pull - отримуємо останні зміни з сайту github
9. git status - показуємо статус проекту
10. git branch - показуємо список гілок в проекті
11. git branch -r - показуємо список гілок на сайті github
12. git branch -a - показуємо список гілок на компютері та на сайті github
13. git fetch - отримуємо зміни з сайту github
14. git stash - зберігаємо не збережені зміни в файлах і кладемо їх в буфер обміну
15. git stash apply - вставляємо збережені зміни з буфера обміну
16. git merge "banchName" - зливаємо гілку з назвою "branchName" в поточну гілку
17. git merge --abort - відміняємо зливання гілок
18. git branch -d branchName - видаляє гілку локально з проекту
19. git push origin --delete name - видаляє гілку з сайту github
20. git diff - показує відрізки рядків між двома версіями файлу (між двома комітами)
21. git log - показує історію комітів
22. cd gitTutorial - переходимо в папку gitTutorial

Для того щоб вийти з режиму перегляду комітів використовуйте клавішу q (стосується команди №20 і №21)

LMS

Користні команди

git clone - Клонує репозиторій
git pull - Стягує оновлення з репозиторію
git push - Записує оновлення коду на віддалений репозиторій
git status - показує статус в локальному репозитрії
git add . - гіт починає відслідковувати зміни що внесені в файл
git commit -m “commit text” - зберігає поточний стан файла
git commit -am “text commit ” - короткий запис команда git add . та git commit -m “” (Працює лише для вже відстежуваних файлів)
git log - показує історію комітів
git branch - показує список локальних гілок
git branch name - створює гілку з ім’ям name
git branch -a - показує список віддалених гілок
git checkout -b name - створює нову гілку з ім’ям “name” і переходить в неї
git checkout name - перехід до потрібної гілки
git merge name - злятя гілки “name” в поточну
git merge --abort - відміна злиття гілок
git push -u origin name - перший пуш нової локальної гілки на гітхаб
git branch -d name - видалення локальної гілки (потрібно з неї вийти)
git push origin --delete name - видалення віддаленої гілки на гітхабі
git stash - ховає внесені зміни в “карман”. (Використовується тоді коли потрібно перейти в іншу гілку але не хочеться робити коміт)
git stash apply - відновлює код з “кармана” (Повертає схований код)

Для першого запуску gulp збірки

$ npm install

$ gulp

Для наступних запусків збірки

$ gulp

Щоб закінчити роботу gulp

Ctrl + C
