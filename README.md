# The result of learning GIT is displayed in this repository
_ Contains two homework assignments + bug report and checklist._
***
## GIT Homework 1:
* Клонировать репозиторий JSON на локальный компьютер:
``` 
git clone https://github.com/Saijentor/JSON.git
```
* Добавить файл под гит:
```
git add new.json
```
* Закоммитить файл:
```
git commit -m "add new.json"
```
* Отправить файл на внешний GitHub репозиторий:
```
git push
```
* Синхронизировать внешний и локальный репозиторий JSON:
```
git pull
```
#### Continued in this file -> [Homework 1](https://github.com/Saijentor/GIT/blob/main/HWGIT.TXT)

***

## GIT Homework 2:
* На локальном репозитории сделать ветки:
````
git branch Postman Jmeter Checklists Bug_Reports SQL Charles Mobile_testing
````
* Запушить все ветки на внешний репозиторий:
```
git push origin --all
```
* В ветке Bag Reports сделать текстовый документ со структурой баг репорта:
```
git checkout Bug_reports
vim bug_report.txt
```
* Вмержить ветку Bag Reports в Main:
```
git checkout main
git merge bug_reports
```
* Синхронизировать Внешнюю и Локальную ветки MainOne line command. Find all lines with "sec" in all text files, copy and paste these lines into one new created text file:
```
git checkout main
git pull
```
#### Continued in this file -> [Homework 2](https://github.com/Saijentor/GIT/blob/main/HWGIT2.TXT)
<div align="center">
<img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/git/git-original.svg" width="70px"/>
</div>
