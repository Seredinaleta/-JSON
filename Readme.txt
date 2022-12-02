JSON
 1. Создать внешний репозиторий c названием JSON.
 Create repository JSON

 2. Клонировать репозиторий JSON на локальный компьютер.
 git clone https://github.com/Seredinaleta/JSON

 3. Внутри локального JSON создать файл “new.json”.
 cd JSON
 touch new.json

 4. Добавить файл под гит.
 git add new.json

 5. Закоммитить файл.
 commit -m "Create new.json'

 6. Отправить файл на внешний GitHub репозиторий.
 git push

 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 cat>>new.json
 {
	"Name":"Yuliia Trubina",
	"age":44,
	"animals":1,
	"salary":2000
 }

 8. Отправить изменения на внешний репозиторий.
 git commit -m "Modified new.json"
 git push

 9. Создать файл preferences.json
 touch preferences.json

 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
 vim preferences.json insert
 {
	"favorite film":"Prada",
	"favorite serial":"Stargate Atlantis",
	"favorite dish":"Meat",
	"favorite season":"spring",
	"next desired country":"Crete"
 }

 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
 cat>>skills.json
 {"Skills":["Theory of testing","JavaScript"],
 "Tools":["Terminal","Postman","Git","DevTools"]
 }

 12. Отправить сразу 2 файла на внешний репозиторий.
 git add .
 git commit -m "Adding preferences and skills files"
 git push

 13. На веб интерфейсе создать файл bug_report.json.
 Add file-Create new file bug_report.json 

 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 commit changes

 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
{Bug_report":
 {"Main": 
  {"ID":"number",
   "Summary":"Short text description jf the bug",
   "STR":"Steps to reproduce the bug",
   "ER":"Estimated result of the test",
   "AR":"Actual result of the test",
   "Severity":"The degree of influence a defect has on the product's operation blocker/crititical/major/minor/trivial"
  },
 "Additional":{
   "Priority":"The order in which the defect should be fixed ASAP/high/medium/low",
   "Environment":"Conditions Device Type/OS/Browser/Software version/Connection Strength/Screen size/Zoom level/Pixel ratio etc",
   "Visual Proof":"Screenshots, videos, text, logs of Bug",
   "Reporter name": "Your own",
   "Status": "SDLS status Opened/In Progress/Fixed or Ready for check/Reopened/Closed/Deffered/Rejected"
  }
 }
}


 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 Commit changes "Modified Bug_report"

 17. Синхронизировать внешний и локальный репозиторий JSON
git fetch-->git pull
