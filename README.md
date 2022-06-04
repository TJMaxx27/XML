# XML
1. Создать внешний репозиторий c названием XML.
```bash
New --> Repository name "XML" --> Public --> add README file --> Create repository 
```
2. Клонировать репозиторий XML на локальный компьютер.
```bash 
git clone + link repository && cd XML
```
3. Внутри локального XML создать файл “new.xml”.
```bash 
touch new.xml 
```
4. Добавить файл под гит.
```bash 
git add new.xml
```
5. Закоммитить файл.
```bash 
git commit -m "Version 1.0"
```
6. Отправить файл на внешний GitHub репозиторий.
```bash 
git push
```
7. Отредактировать содержание файла “new.XML” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```bash 
vim new.xml --> i --> text --> ESC + :wq
```
8. Отправить изменения на внешний репозиторий.
```bash 
git add new.xml && git commit -m 'v.2' && git push
```
9. Создать файл preferences.xml
```bash 
touch preferences.xml
```
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```bash 
vim touch preferences.xml --> i --> text --> :wq
```
11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```bash 
touch skills.xml && vim skills.XML
```
12. Сделать коммит в одну строку.
```bash 
git add . && git commit -m "added file: preferences and skills" 
```
13. Отправить сразу 2 файла на внешний репозиторий.
```bash 
git push	
```
14. На веб интерфейсе создать файл bug_report.XML.
```bash 
add file --> create new file --> Name your file "bug_report.XML"
```
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash 
Click the button "Commit directly to the main branch"
```
16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```bash 
Choose bug_report.xml --> Edit this file --> Text 
```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash 
Click the button "Commit changes"
```
18. Синхронизировать внешний и локальный репозиторий XML
```bash 
git pull
```
