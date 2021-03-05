# Bot
This is our first project, don't judge
# Проект по созданию бота вконтакте для автоматизации приёма заявлений в общежитии, напоминании о дежурстве #
## Cостав команды ##
***
* Алексеева Ксения Романовна
* Кобелева Татьяна Дмитриевна
* Полукаров Иван Сергеевич

## Функциональные требования ##
1.  Необходима регистрация для всех пользователей в боте, привязка определённой фамилии к ID вконтакте, подтверждение достоверности с имеющейся базой данных от администрации.
2.  Боту необходимо принимать заявки на создание заявлений от пользователей в сообщениях группы вконтакте, создавать документ в формате .docs, заполнять его по шаблону, вставлять личные данные проживающего, его подпись, отправлять сформированный файл на почту в администрации.
3.  Напоминание о дежурствах: староста раз в месяц будет загружать в бота файл в формате .xlsx с таблицей дежурств, бот вычленяет оттуда фамилии дежурящих и связывает их с определённым днём. В нужный день по ID бот в списке участников группы ищет нужного человека, отправляет сообщение с напоминанием о дежурстве, предлагает отметиться о прочтении.

