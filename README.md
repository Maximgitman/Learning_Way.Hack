## Learning_Way
<img src="https://media.giphy.com/media/5BouvpJA911xS/giphy.gif" width="512" height="256" />

Добро пожаловать в репозиторий команды PowerRangers!
Хакатон: Moscow_City_Hack
Кейс: "Разработка моделей оценки студентов на основании открытых данных с рекомендацией применения в освоении профессий/курсов".

В репозитории представлены 2 ветки main и app.
В ветке main находится Jupyter Notebook, описание проекта и то как и где с ним можно познакомиться. 
В ветке app вы можете ознакомиться с кодом для сборки web-приложения, которое уже можно протестировать на себе. P.S. Подробности далее. 

Все функции парисанга и обработки данных разрабатывались в google colab notebook. Поэтому начнем знакомство с него. 
# 1. Запуск ноутбука.
Для того, чтобы посмотреть как работают функции и запустить код, перейдите по ссылке: 
https://colab.research.google.com/drive/1V54ori-qyT74uNEBdwYMRdfKIzYgexO8?usp=sharing

После чего последовательно запускайте ячейки. Дополнительно устанавливать ничего не нужно. В ноутбуке есть текстовые ячейки помощники. 

# 2. Тест web-приложения. 
Мы разработали приложение, которое вы уже можете протестировать на себе. 
Для этого перейдите по ссылке: 
http://90.188.227.45:8000/

Демонстрация работы web-приложения на gif.
![demo_medium](https://user-images.githubusercontent.com/74874309/121821854-62d8a480-cca4-11eb-8aa3-8f8d6cc5a7fc.gif)

Текстовое описание работы:  
На главной странице вы увидите форму для заполнения. 
Вводим ФИО и затем интересующую Вас область. 
В данный момент приложение настроено на одну область. 
Поэтому для корректной отработки скрипта, пожалуйста, введите область Data Science. 


![image](https://user-images.githubusercontent.com/74874309/121821174-fcea1e00-cc9f-11eb-9a7c-62952da65533.png)

После чего вы увидите сообщение "Проводим аналитику по Вашей вакансии". Обычно это занимает всего пару секунд.
Далее скрипт собирает все необходимые навыки для данной специальности. Затем вам необходимо оценить уровень своих знаний по каждому из них. 
Если у вас есть какие-либо еще навыки, которые не вошли в основные навыки, вы можете добавить их ниже. 

![image](https://user-images.githubusercontent.com/74874309/121821302-e1334780-cca0-11eb-8ab3-ec82d1b97b01.png)

Когда будуте готовы, нажмите внизу на зеленую копку "далее".
Готово! 
В первом блоке результатов вы получаете список рекомендуемых вакансий для вас, в зависимости от ваших навыков и уровня владения ими. 

![image](https://user-images.githubusercontent.com/74874309/121821391-4129ee00-cca1-11eb-9d6c-6ea51c47f450.png)

Во втором блоке вы получаете список курсов отдельно по каждому топовому навыку в спецаильности вместе со ссылками в зависимости от вашего уровня. 
Так, например, если у вас базовый уровень в SQL, приложение порекомендует пройти курс по повышению квалификации среднего уровня. 

![image](https://user-images.githubusercontent.com/74874309/121821441-abdb2980-cca1-11eb-838e-0dafff9c278e.png)





