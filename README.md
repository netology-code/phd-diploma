# Курсовая работа курса «Аппаратное обеспечение (Hardware)»

### Цель курсовой работы

Целью проекта является создание аппаратной конфигурации проекта АСУ ТП линии хранения углекислоты. 

В результате выполнения этого задания вы:
1. Научитесь подбирать устройства для АСУ ТП на сайтах ведущих производителей.
2. Разработайте полноценную спецификацию на закупку по основным видам оборудования, необходимым при проектировании АСУ ТП (датчики, регуляторы, исполнительные механизмы).
3. Создадите проект аппаратной конфигурации для АСУ ТП.

### Чек-лист готовности к курсовой работе

1. Ознакомьтесь с сайтами ведущих производителей, на которых необходимо будет подобрать оборудование для новой АСУ ТП. 
*Список производителей:*
- датчики: [IFM](https://www.ifm.com/ru/ru), [BALLUFF](https://www.balluff.com/ru-ru), [OMRON](https://industrial.omron.ru/ru/home), [ОВЕН](https://owen.ru/)
- элементы автоматики: [SCHNEIDER ELECTRIC](https://www.se.com/ru/ru/)
- ПЛК, модули ввода/вывода, периферийные и интерфейсные модули, частотные преобразователи, регулирующие клапаны: [SIEMENS](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru)
- частотные преобразователи, регулирующие клапаны: [DANFOSS](https://www.danfoss.com/ru-ru/)

2. Зарегистрируйтесь на [портале Siemens](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru) и получите персональный логин и пароль для входа в систему.
3. Загрузите и установите программное обеспечение для создания HMI WinCC, входящее в состав пакета TIA Portal с [официального сайта Siemens](https://support.industry.siemens.com/cs/document/109761045/simatic-step-7-and-wincc-v15-1-trial-download?dti=0&lc=en-US). После установки вы получите бесплатную полнофункциональную версию trial-версию на 21 день.

### Инструменты/ дополнительные материалы, которые пригодятся для выполнения задания

1. Google Диск
2. Google документы
3. Сайты производителей автоматики, указанные в разделе "Чек-лист готовности к курсовой работе"
4. [TIA Portal v17 + WinCC v17](https://support.industry.siemens.com/cs/document/109784440/simatic-step-7-incl-safety-s7-plcsim-and-wincc-v17-trial-download?dti=0&lc=en-WW).

### Инструкция к выполнению курсовой работы

1. Выполните установку необходимых программных инструментов из **Чеклиста готовности к курсовой работе**.
2. Сделайте копию [Шаблона для домашнего задания](https://docs.google.com/document/d/17NMApsPhhf4vsnDDtFg3SyEir1uqEVdPAWIn3KVicIk/edit?usp=sharing) себе на Google Disk.
3. Зайдите в «Настройки доступа» скопированного вами шаблона и выберите доступ «Просматривать могут все в Интернете, у кого есть ссылка». Ссылка на инструкцию [Как предоставить доступ к файлам и папкам на Google Диске](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop).
4. В названии файла введите вашу фамилию и имя.
5. Скопируйте текст задания в свой документ.
6. В соответствии со [структурной схемой](https://drive.google.com/file/d/1WoeViaMVX3dybgziYoZ4ra8B0kYRulMM/view?usp=sharing) и техническим заданием подберите датчики на сайтах производителей, указанных в "Чек-листе готовности к курсовой работе".
7. Заполните [спецификацию](https://docs.google.com/spreadsheets/d/17tOAmPo7Z6z4lXXrhkL3ghtr7bF6W0NTV-cz05664s8/edit?usp=sharing) в разделе "Датчики" в соответствии с подобранными вами датчиками.
8. Аналогичным образом подберите регуляторы и исполнительные механизмы (при необходимости).
9. Заполните [спецификацию](https://docs.google.com/spreadsheets/d/17tOAmPo7Z6z4lXXrhkL3ghtr7bF6W0NTV-cz05664s8/edit?usp=sharing) в разделах "Регуляторы" и "Исполнительные механизмы" в соответствии с подобранными вами компонентами.
10. Разработайте HMI-проект для АСУ ТП в программе WinCC.
11. Вставьте в соответствующие абзацы вашего "Шаблона для выполнения домашнего задания" ссылки на выполненные задания.
12. Для проверки домашнего задания преподавателем отправьте ссылку на ваш документ в личном кабинете.
13. Любые вопросы по решению задач задавайте в чате учебной группы.

Изучите [техническое задание](https://docs.google.com/document/d/1T5WKqEH-44hEJefy5iq_yIxquGd0RcvOSUxEsNzlBr0/edit?usp=sharing) для понимание структуры и объема работы.

### Критерии оценки

Зачёт по курсовой работе может быть получен, если работа соответствует следующим критериям:

1. Оборудование подобрано корректно по необходимым параметрам, все подобранное оборудование логично сочетается между собой.
2. HMI-проект размечен в соответствии с составом системы.
