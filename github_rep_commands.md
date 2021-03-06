## JSON  
__4. Создать внешний репозиторий c названием JSON.__  
`curl -u Pavel-Pristupa:YOUR_KEY https://api.github.com/user/repos -d '{"name":"JSON"}'`  
__5. Клонировать репозиторий JSON на локальный компьютер.__    
`git clone https://github.com/Pavel-Pristupa/JSON`    
__6. Внутри локального JSON создать файл “new.json”.__    
`cd JSON`    
`touch new.json`    
__7. Добавить файл под гит.__    
`git add new.json`    
__8. Закоммитить файл.__  
`git commit -m "Adding new.json"`  
__9. Отправить файл на внешний GitHub репозиторий.__  
`git push`  
__10. Отредактировать содержание файла “new.json” - написать информацию о себе   
(ФИО, возраст, количество домашних животных, будущая желаемая зарплата).  
Всё написать в формате JSON.__  
`vim new.json`  
:arrow_right: __i__  
```json
{
	"name":"Pavel",
	"age":32,
	"pets":1,
	"salary":1000
}
```
:arrow_right: __Esc__  
:arrow_right: `:wq`  
__11. Отправить изменения на внешний репозиторий.__  
`git commit -am "new.json changes"`  
`git push`  
__12. Создать файл preferences.json__  
`touch preferences.json`  
__13. В файл preferences.json добавить информацию о своих предпочтениях  
(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.__  
`vim preferences.json`  
:arrow_right: __i__  
```json
{
	"movie":"Green mile",
	"sit-com":"Black mirror",
	"food":"Draniki",
	"season":"Summer",
	"country":"Australia"
}
```
:arrow_right: __Esc___  
:arrow_right: `:wq`  
__14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON__  
`touch sklls.json`  
`vim sklls.json`  
:arrow_right: __i__  
```json
{
	"hard_skills":{
		"API":"Postman",
		"sniffers":["Charles", "Fiddler"],
		"mobile": ["AS", "Xcode"]
	},
	"soft_skills":["Communication", "Problem-solving", "Working under stress"]
}
```
:arrow_right: __Esc__  
:arrow_right: `:wq`  
__15. Отправить сразу 2 файла на внешний репозиторий.__  
`git add .`  
`git commit -m "adding 2 files"`  
`git push`  
__16. На веб интерфейсе создать файл bug_report.json.__  
:arrow_right: https://github.com/Pavel-Pristupa/JSON  
:arrow_right: Add file :arrow_right: Create new file  
:arrow_right: bug_report.json  
__17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__  
:arrow_right: Commit new file  
__18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.__  
:arrow_right: https://github.com/Pavel-Pristupa/JSON/blob/main/bug_report.json  
:arrow_right: Edit this file  *(Значок карандаша справа)*  
```json
{
	 "id":1,
	"project":"Homework",
	"issue_type":"bug",
	"summary":"User doesn't know what to enter into the summary of the bug report",
	"priority":"high",
	"description":"The user doing this particular homework doesn't have and idead what to enter into the bugreport according to GitHub Home_work in point 18",
	"STR":"No steprs provided, contents clear from 'description'",
	"AR":"321",
	"ER":"123",
	"environment":"Windows 10 Pro v ..., Google Chrome v ..."
	"reporter":"Pavel Pristupa",
	"assignee":"to be assigned"
}
```  
__19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__  
:arrow_right: Commit changes  
__20. Синхронизировать внешний и локальный репозиторий JSON__  
`git fetch`  
`git pull`  
____
## XML  
__21. Создать внешний репозиторий c названием XML.__  
`curl -u Pavel-Pristupa:YOUR_KEY https://api.github.com/user/repos -d '{"name":"XML"}'`  
__22. Клонировать репозиторий XML на локальный компьютер.__  
`git clone https://github.com/Pavel-Pristupa/XML`  
__23. Внутри локального XML создать файл “new.xml”.__  
`cd XML`  
`touch new.xml`  
__24. Добавить файл под гит.__  
`git add new.xml`  
__25. Закоммитить файл.__  
`git commit -m "Adding new.xml"`  
__26. Отправить файл на внешний GitHub репозиторий.__  
`git push`  
__27. Отредактировать содержание файла “new.xml” - написать информацию о себе  
(ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.__  
`vim new.xml`  
:arrow_right: __i__  
```xml
<?xml version="1.0" encoding="utf-8"?>
<about>
	<name>Pavel</name>
	<age>32</age>
	<pet>1</pet>
	<salary>1000</salary>
</about>
```  
:arrow_right: __Esc__  
:arrow_right: `:wq`  
__28. Отправить изменения на внешний репозиторий.__  
`git commit -am "new.xml changes"`  
`git push`  
__29. Создать файл preferences.xml__  
`touch preferences.xml`  
__30. В файл preferences.xml добавить информацию о своих предпочтениях  
(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.__  
`vim preferences.xml`  
:arrow_right: __i__  
```xml
<?xml version="1.0" encoding="utf-8"?>
<preferences>
	<movie>Green mile</movie>
	<sit-com>Black mirror</sit-com>
	<food>Draniki</food>
	<season>Summer</season>
	<country>Australia</country>
</preferences>
```  
:arrow_right: __Esc__  
:arrow_right: `:wq`  
__31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML.__  
`touch sklls.xml`  
`vim sklls.xml`  
:arrow_right: __i__  
```xml
<?xml version="1.0" encoding="utf-8"?>
<skills>
	<hard_skills>
		<API>Postman</API>
		<sniffers>Charles, Fiddler</sniffers>
		<mobile>AS, Xcode</mobile>
	</hard_skills>
	<soft_skills>Communication, Problem-solving, Working under stress</soft_skills>
</skills>
```  
:arrow_right: __Esc__  
:arrow_right: `:wq`  
__32. Сделать коммит в одну строку.__  
`git add . && git commit -m "adding two files"`  
__33. Отправить сразу 2 файла на внешний репозиторий.__  
`git push`  
__34. На веб интерфейсе создать файл bug_report.xml.__  
:arrow_right: https://github.com/Pavel-Pristupa/XML  
:arrow_right: Add file :arrow_right: Create new file  
:arrow_right: bug_report.xml  
__35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__  
:arrow_right: Commit new file  
__36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.__  
:arrow_right: https://github.com/Pavel-Pristupa/XML/blob/main/bug_report.xml  
:arrow_right: Edit this file *(Значок карандаша справа)*  
```xml
<?xml version="1.0" encoding="utf-8"?>
<bugreport>
	<id>1</id>
	<project>Homework</project>
	<issue_type>bug</issue_type>
	<summary>User doesn't know what to enter into the summary of the bug report</summary>
	<priority>high</priority>
	<description>The user doing this particular homework doesn't have and idea what to enter into the bugreport according to GitHub Home_work in point 36</description>
	<STR>No steps provided, contents clear from 'description'</STR>
	<AR>321</AR>
	<ER>123</ER>
	<environment>Windows 10 Pro v ..., Google Chrome v ...</environment>
	<reporter>Pavel Pristupa</reporter>
	<assignee>to be assigned</assignee>
</bugreport>
```  
__37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__  
:arrow_right: Commit changes  
__38. Синхронизировать внешний и локальный репозиторий XML__  
`git fetch`  
`git pull`  
____
## TXT  
__39. Создать внешний репозиторий c названием TXT.__  
`curl -u Pavel-Pristupa:YOUR_KEY https://api.github.com/user/repos -d '{"name":"TXT"}'`  
__40. Клонировать репозиторий TXT на локальный компьютер.__  
`git clone https://github.com/Pavel-Pristupa/TXT`  
__41. Внутри локального TXT создать файл “new.txt”.__  
`cd TXT`  
`touch new.txt`  
__42. Добавить файл под гит.__  
`git add new.txt`  
__43. Закоммитить файл.__  
`git commit -m "Initial commit"`  
__44. Отправить файл на внешний GitHub репозиторий.__  
`git push`  
__45. Отредактировать содержание файла “new.txt” - написать информацию о себе  
(ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.__  
`vim new.txt`  
:arrow_right: __i__
```
Name - Pavel
Age - 32
Pets - 1
Sallary - 1000
```  
:arrow_right: __Esc__  
:arrow_right: `:wq`  
__46. Отправить изменения на внешний репозиторий.__  
`git add .`  
`git commit -m "Changes in new.txt"`  
`git push`  
__47. Создать файл preferences.txt__  
`touch preferences.txt`  
__48. В файл preferences.txt” добавить информацию о своих предпочтениях  
(Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.__  
`vim preferences.txt`  
:arrow_right: __i__  
```
Movie - Green mile
Sit-com - Black mirror
Food - Draniki
Season - Summer
Country - Australia
```  
:arrow_right: __Esc__  
:arrow_right: `:wq`  
__49. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT.__  
`vim sklls.txt`  
:arrow_right: __i__  
```
Hard_skills:
	API: Postman;
	sniffers: Charles, Fiddler;
	mobile: AS, Xcode;				
Soft_skills: Communication, Problem-solving, Working under stress.
```  
:arrow_right: __Esc__  
:arrow_right: `:wq`  
__50. Сделать коммит в одну строку.__  
`git add . && git commit -m "Adding preferences and skills"`  
__51. Отправить сразу 2 файла на внешний репозиторий.__  
`git push`  
__52. На веб интерфейсе создать файл bug_report.txt.__  
:arrow_right: https://github.com/Pavel-Pristupa/TXT  
:arrow_right: Add file :arrow_right: Create new file  
:arrow_right: bug_report.txt  
__53. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__  
:arrow_right: Commit new file  
__54. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.__  
:arrow_right: https://github.com/Pavel-Pristupa/TXT/blob/main/bug_report.txt  
:arrow_right: Edit this file *Значок карандаша справа*  
```
ID -1
Project - Homework
Issue_type - bug
Summary - User doesn't know what to enter into the summary of the bug report
Priority - high
Description - The user doing this particular homework doesn't have and idead what to enter into the bugreport according to GitHub Home_work in point 54
STR - No steps provided, contents clear from 'description'
AR - 321
ER - 123
Environment - Windows 10 Pro v ..., Google Chrome v ...
Reporter - Pavel Pristupa
Assignee - to be assigned
Attachments - ...	
```  
__55. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__  
:arrow_right: Commit changes  
__56. Синхронизировать внешний и локальный репозиторий TXT__  
`git fetch`  
`git pull`  
