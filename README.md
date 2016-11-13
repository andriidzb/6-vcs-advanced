# 6-vcs-advanced
1. git clone https://github.com/andriydzb/vcs-task1.git - клонував репозиторій. 
 git checkout -b architecture - зробив вітку і перейшов на неї. 
 mkdir assets, mkdir uploads, touch index.html - створив потрібні папки і файл.
 git add . , git commit -m "added 2 folders and index.html" - закомітив. 
 cd assets, touch all.js, touch css.js - додав файли у папку assets.
 git add . , git commit - m "add js files" - закомітив.
 git push origin architecture - пушнув всі файли в репозиторій.
 Папка upldoads не додалася, оскільки вона пуста. Щоб додати і цю папку я зробив наступне: 
 cd uploads, touch .keep - додав пустий файл у папку. Закомітив і запушив. 
 echo "uploads/" > .gitignore - додав вміст папки в ігнор. Запушив.
 git branch master, git merge architecture, git push origin master - змерджив дві вітки.
 git push origin :architecture - видалив вітку architecture.
 Репозиторій - https://github.com/andriydzb/vcs-task1.
2. Створив новий репозиторій https://github.com/andriydzb/vcs-task2. Клонував його. Створив нову бренчу homework. Додав 2 файли у 
 master,  закомітив їх. Перейшов у вітку homework та зробив rebase. Зробив коміт в homework. Переключився на master, зробив 
 merge. Пушнув в gihtub. Видалив бренчу homework за допомогою команди: git branch -d homework. (остання команда не помістилася
 на скріні, тому написав).
 ![](http://i.piccy.info/i9/5fc38e3d4a31078769eaabcde58447c1/1478960047/52820/1086149/Bez_men_.png) 
 ![](http://i.piccy.info/i9/37b9982784d41a711ce53876d1b9452f/1478960155/44120/1086149/Bez_men1_.png)
3. Створив репозиторій https://github.com/andriydzb/vcs-task3. Зробив 2 коміти. Створив мітку git tag -a v1.3 -m "tag version 1.3", 
 git tag - вивів всі мітки. git show (тому що вітка тільки одна) - деталі мітки v1.3
 ![](http://i.piccy.info/i9/4a660f37c46e911d6475aa45aa5197fa/1478961204/47645/1086149/Bez_men_2.png)
 ![](http://i.piccy.info/i9/86125736a9b800a757415f454d9ce8b3/1478961236/16094/1086149/Bez_men_3.png)
4. Створив репозиторій https://github.com/andriydzb/vcs-task4/. Додав підмодуль git submodule add https://github.com/andriydzb/hello-world-git.git Hello. Закомітив як свій перший підмодуль і запушив.
 ![](http://i.piccy.info/i9/f3af5439947fdbef999915f8c193d0a5/1478962042/45636/1086149/Bez_men241214_.png)
5. Створий новий репозиторій https://github.com/andriydzb/vcs-task5. git add gh-pages. Додав файл
 index.html, де додав мінімальний html код. Закомітив і запушив. Після цього зробив деякі зміни в файлі, знову закомітив і запушив.
 Результат - https://andriydzb.github.io/vcs-task5/.
 ![](http://i.piccy.info/i9/ab20deb7cfdfb6977a4025f4a4e489fd/1478962706/37143/1086149/Bez_men_123.png)
 ![](http://i.piccy.info/i9/17a26c9dd55831a86fa39278689be88d/1478962775/34646/1086149/Bez_men_1234.png)
6. Створив новий репозиторій https://github.com/andriydzb/vcs-task6. Створив файл в бренчі master, додав нову бренчу 
 test, перейшов на неї, зробив зміни в файлі та закомітив їх. Повернувся на бренчу master, додав несумісні зміни та попробував   змерджити. Виник конфлікт, який я пофіксив та знову змерджив. Мердж пройшов успішно.
 ![](http://i.piccy.info/i9/d1eaeeba6d79628fe051f93e8ead1684/1478966643/48647/1086149/1.png)
 ![](http://i.piccy.info/i9/fbdd19ea8512711438dc877deee2d092/1478966777/41411/1086149/2.png)
 ![](http://i.piccy.info/i9/64e39b90350c9cb66fd767f714dae5c1/1478966858/53219/1086149/3.png)
 
 Ось сам конфлікт: 
 ![](http://i.piccy.info/i9/4b5f4238fb6c6a00813f33e147723a89/1478966891/12646/1086149/Bez_men_124124.png)
