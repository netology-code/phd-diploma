# Курсовая работа «Аппаратные средства АСУ ТП» по курсу «Аппаратное обеспечение (Hardware)»

### Цель проекта

Целью курсового проекта является создание аппаратной конфигурации проекта АСУ ТП. 

Вам предстоит:

- создать проект аппаратной конфигурации для АСУ ТП
- подобрать устройства для АСУ ТП на сайтах ведущих производителей
- разработать спецификацию на закупку по основным видам оборудования для созданного проекта АСУ ТП (датчики, регуляторы, исполнительные механизмы).

-----

### Чеклист готовности к курсовой работе

1. Ознакомьтесь с сайтами ведущих производителей, на которых необходимо будет подобрать оборудование для новой АСУ ТП. 
*Список производителей:*
- датчики: [BALLUFF](https://www.balluff.com/ru-ru), [OMRON](https://industrial.omron.ru/ru/home), [ОВЕН](https://owen.ru/)
- элементы автоматики: [SCHNEIDER ELECTRIC](https://www.se.com/ru/ru/)
- ПЛК, модули ввода/вывода, периферийные и интерфейсные модули, частотные преобразователи, регулирующие клапаны: [SIEMENS](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru)
- частотные преобразователи, регулирующие клапаны: [DANFOSS](https://www.danfoss.com/ru-ru/)
2. Зарегистрируйтесь на [портале Siemens](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru) и получите персональный логин и пароль для входа в систему. Процесс регистрации описан в [соответствующей инструкции](https://docs.google.com/presentation/d/1RPHvCE2OxBbHRMWSAV2E-HxscZvR2nRIZVHCy8hvjJE/edit?usp=sharing).
3. Загрузите и установите программное обеспечение для создания HMI WinCC, входящее в состав пакета TIA Portal с [официального ресурса Siemens](https://support.industry.siemens.com/cs/document/78793685/simatic-step-7-(tia-portal)-v13-trial-download?dti=0&lc=en-DE).
**ОБРАТИТЕ ВНИМАНИЕ!** Устанавливается демо-версия программы. Её функционал будет ограничен спустя 21 день после установки. Рекомендуется установка данного ПО на виртуальной машине. В этом случае есть возможность откатить ПО к началу пробного периода. Как это сделать описано в [этой инструкции](https://docs.google.com/presentation/d/19cSsdcEucIE7oTKTbxEnkeRKdH7vw8_mneortgpkOF4/edit?usp=sharing).
4. Изучите [ГОСТ 21.208-2013](https://mvif.ru/uslovnyie-oboznacheniya-priborov-i-sredstv-avtomatizaczii-v-sxemax-gost-21.404-85). В нем дано описание расшифровки схем автоматизации.

2. Зарегистрируйтесь на [портале Siemens](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru) и получите персональный логин и пароль для входа в систему. Процесс регистрации описан в [соответствующей инструкции](https://docs.google.com/presentation/d/1RPHvCE2OxBbHRMWSAV2E-HxscZvR2nRIZVHCy8hvjJE/edit?usp=sharing).
3. Загрузите и установите программное обеспечение для создания проекта PLC Siemens, входящее в состав пакета TIA Portal с [официального ресурса Siemens](https://support.industry.siemens.com/cs/document/78793685/simatic-step-7-(tia-portal)-v13-trial-download?dti=0&lc=en-DE):
<details>
  <summary> Подсказка по установке (доступна по клику)</summary>
  
  
1. Скачайте все файлы по [ссылке](https://support.industry.siemens.com/cs/document/109745155/simatic-step-7-including-plcsim-v13-sp2-trial-download?dti=0&lc=en-DE) в две отдельные папки:
  - STEP 7 Professional V13 SP2 (DVD 1, DVD 2, SHA-256 checksum)
  ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.6/Step7_1.png)
  - SIMATIC STEP 7 PLCSIM V13 SP2 for STEP 7 Basic and STEP 7 Professional (включая SHA-256 checksum)
    ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.6/Step7_2.png)
2. Запустите установочный файл SIMATIC_STEP_7_Professional_V13_SP2_Upd4.exe, пройдите стандартную процедуру установки.
3. Запустите установочный файл SIMATIC_S7_PLCSIM_V13_SP2.exe, пройдите стандартную процедуру установки.

    ---
  
</details>
  
*ОБРАТИТЕ ВНИМАНИЕ! Устанавливается демо-версия программы. Её функционал будет ограничен спустя 21 день после установки. Рекомендуется установка софта на виртуальной машине. Как это сделать, описано в [инструкции](https://docs.google.com/presentation/d/1psnSlotXT7cr8ECnaZaTCDLnIyYOGUzCArLeydeRztY/edit?usp=sharing).*
-----

### Инструменты/ дополнительные материалы, которые пригодятся для выполнения задания

1. [Google.Диск](https://drive.google.com/drive/u/0/my-drive).
2. [Google.Документы](https://www.google.ru/intl/ru/docs/about/).
3. Сайты производителей автоматики, указанные в разделе "Чек-лист готовности к курсовой работе"
4. [TIA Portal v13](https://support.industry.siemens.com/cs/document/78793685/simatic-step-7-(tia-portal)-v13-trial-download?dti=0&lc=en-DE).
5. [ГОСТ 21.208-2013](https://mvif.ru/uslovnyie-oboznacheniya-priborov-i-sredstv-avtomatizaczii-v-sxemax-gost-21.404-85)
6. [Спецификация](https://docs.google.com/spreadsheets/d/17tOAmPo7Z6z4lXXrhkL3ghtr7bF6W0NTV-cz05664s8/edit?usp=sharing)

-----

### Инструкция к выполнению курсовой работы

1. Выполните установку необходимых программных инструментов из **Чеклиста готовности к курсовой работе**.
2. Сделайте копию [Шаблона для домашнего задания](https://docs.google.com/document/d/17NMApsPhhf4vsnDDtFg3SyEir1uqEVdPAWIn3KVicIk/edit?usp=sharing) себе на Google Disk.
3. Зайдите в «Настройки доступа» скопированного вами шаблона и выберите доступ «Просматривать могут все в Интернете, у кого есть ссылка». Ссылка на инструкцию [Как предоставить доступ к файлам и папкам на Google Диске](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop).
4. В названии файла введите вашу фамилию и имя.
5. Скопируйте текст задания в свой документ.
6. В соответствии с [техническим заданием](https://docs.google.com/document/d/1T5WKqEH-44hEJefy5iq_yIxquGd0RcvOSUxEsNzlBr0/edit?usp=sharing) подберите датчики на сайтах производителей, указанных в "Чек-листе готовности к курсовой работе".
7. Заполните [спецификацию](https://docs.google.com/spreadsheets/d/17tOAmPo7Z6z4lXXrhkL3ghtr7bF6W0NTV-cz05664s8/edit?usp=sharing) в разделе "Датчики" в соответствии с подобранными вами датчиками.
8. Аналогичным образом подберите регуляторы и исполнительные механизмы (при необходимости).
9. Заполните [спецификацию](https://docs.google.com/spreadsheets/d/17tOAmPo7Z6z4lXXrhkL3ghtr7bF6W0NTV-cz05664s8/edit?usp=sharing) в разделах "Регуляторы" и "Исполнительные механизмы" в соответствии с подобранными вами компонентами.
10. Подберите компоненты электрического шкафа для данной АСУ ТП и заполните [спецификацию](https://docs.google.com/spreadsheets/d/17tOAmPo7Z6z4lXXrhkL3ghtr7bF6W0NTV-cz05664s8/edit?usp=sharing) в разделе "Автоматика"
11. Разработайте HMI-проект для АСУ ТП в программе WinCC.
12. Вставьте в соответствующие абзацы вашего "Шаблона для выполнения домашнего задания" ссылки на выполненные задания.
13. Для проверки домашнего задания преподавателем отправьте ссылку на ваш документ в личном кабинете.
14. Любые вопросы по решению задач задавайте в чате учебной группы.


-----

### Критерии оценки

Зачёт по курсовой работе может быть получен, если работа соответствует следующим критериям:

1. Оборудование подобрано корректно по необходимым параметрам, все подобранное оборудование логично сочетается между собой.
2. HMI-проект размечен в соответствии с составом системы.
