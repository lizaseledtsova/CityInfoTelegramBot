<h1>TASK points:</h1>

Необходимо создать web приложение по управлению собственным туристическим телеграм ботом.
1) Телеграм бот выдает пользователю справочную информацию о введенном городе. Например, пользователь вводит: «Москва», чат-бот отвечает: «Не забудьте посетить Красную Площадь. Ну а в ЦУМ можно и не заходить)))».
2) Данные о городах должны храниться в базе данных.
3) Управлять данными о городах (добавлять новые города и информацию о них, изменять и удалять любую информацию) необходимо через REST WebService.


<h1>Technologies:</h1>
<ul>
<li>SpringBoot</li>
<li>SpringMVC</li>
<li>SpringData</li>
<li>Hibernate</li>
<li>Lombook</li>
</ul>

<h1>Install:</h1>
<ul>
<li>Download zip archive with the files/ commit.</li>
<li>Installed on your PC:</li>
<ul>
<li>WebBrowser</li>
<li>MySQL</li>
<li>Postman</li>
<li>JDK 1.8+</li>
</ul>
<li>Create database:city_db</li>
<li>Change properties file ( 
spring.datasource.username="you_username"
spring.datasource.password="you_password")</li>
<li>Start project</li>
</ul>

<h1>Telegram bot properties:</h1>

<p>Bot name: @CityInfo_v_1_1_Bot</p>
<p>Token to access the HTTP API: 835846523:AAEEgrFfS6faqmLNP6WFO1iFpbFurHYafi8 </p>
