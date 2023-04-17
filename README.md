# test1

1. git clone - копіює репозиторій на комп'ютер
2. git branch "branchName" - створює гілку з назвою "branchName" без кавичек
3. git checkout "branchName" - переходить на гілку з назвою "branchName"
4. git checkout -b "branchName" - створює гілку з назвою "branchName" і переходить на неї
5. git add - зберігає зміни в файлах
6. git commit -m "commit messege" - підписуємо збережені зміни
   5+6. git commit -am "commit messege" - підписуємо і зберігаємо зміни
7. git push -відправляємо зміни на сайт github
   7a. git push --set upstream origin "branchName" - запушить з гілкою всі файли (тільки перший раз потрібен)
8. git pull - отримуємо останні зміни з сайту github (т.б. щоб побачити в себе на компі іншу гілку, зробити правки і знову зберегти і за рушити)
9. git status - показуємо статус проекту (т.б. підказка, що треба зробити далі в terminal)
10. git branch - показуємо список гілок в проекті
11. git branch -r - показуємо список гілок на github
12. git branch -a - показуємо список гілок на комп'ютері і сайті github
13. git fetch - отримуємо зміни з сайту github
14. git stash - зберігаємо незбережені зміни в файлах і кладемо їх в буфер обміну
15. git stash apply - вставляємо збережені зміни з буферу обміну
16. git merge "branchName" - зливаємо (об'єднуємо) гілку з назвою "branchName" в поточну гілку (main)
17. git merge --about - відміняємо зливання гілок
18. git branch -d "branchName" - видаляємо гілку з комп'ютера (локально)
19. git push origin --delete "branchName" - видаляє гілку на сервері (origin) github
20. git diff - показує відрізки рядків між двома версями сайту (між двома комітами)
