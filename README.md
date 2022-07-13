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

Список производителей:
- датчики: [BALLUFF](https://www.balluff.com/ru-ru), [OMRON](https://industrial.omron.ru/ru/home), [ОВЕН](https://owen.ru/)
- элементы автоматики: [SCHNEIDER ELECTRIC](https://www.se.com/ru/ru/)
- ПЛК, модули ввода/вывода, периферийные и интерфейсные модули, частотные преобразователи, регулирующие клапаны: [SIEMENS](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru)
- частотные преобразователи, регулирующие клапаны: [DANFOSS](https://www.danfoss.com/ru-ru/), [SIEMENS](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru)
2. Изучите описание обозначений приборов и средств автоматизации в схемах согласно [ГОСТу 21.208-2013](https://mvif.ru/uslovnyie-oboznacheniya-priborov-i-sredstv-avtomatizaczii-v-sxemax-gost-21.404-85)
3. Зарегистрируйтесь на [портале Siemens](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru) и получите персональный логин и пароль для входа в систему. Процесс регистрации описан в [соответствующей инструкции](https://docs.google.com/presentation/d/1RPHvCE2OxBbHRMWSAV2E-HxscZvR2nRIZVHCy8hvjJE/edit?usp=sharing).
4. Загрузите и установите программное обеспечение для создания проекта PLC Siemens, входящее в состав пакета TIA Portal с [официального ресурса Siemens](https://support.industry.siemens.com/cs/document/78793685/simatic-step-7-(tia-portal)-v13-trial-download?dti=0&lc=en-DE).
**Обратите внимание!** Если вы планируете выполнять необязательное задание (_*_), то используйте подсказку по установки для версии TIA Portal v16, если же не планируете - то можно воспользоваться подсказкой по установке для версии TIA Portal V13.
<details>
  <summary> Подсказка по установке TIA Portal V13 (доступна по клику)</summary>
  
  
1. Скачайте все файлы по [ссылке](https://support.industry.siemens.com/cs/document/109745155/simatic-step-7-including-plcsim-v13-sp2-trial-download?dti=0&lc=en-DE) в две отдельные папки:
  - STEP 7 Professional V13 SP2 (DVD 1, DVD 2, SHA-256 checksum)
  ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.6/Step7_1.png)
  - SIMATIC STEP 7 PLCSIM V13 SP2 for STEP 7 Basic and STEP 7 Professional (включая SHA-256 checksum)
    ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.6/Step7_2.png)
2. Запустите установочный файл SIMATIC_STEP_7_Professional_V13_SP2_Upd4.exe, пройдите стандартную процедуру установки.
3. Запустите установочный файл SIMATIC_S7_PLCSIM_V13_SP2.exe, пройдите стандартную процедуру установки.

    ---
  
</details>

<details>
  <summary> Подсказка по установке TIA Portal V16 (доступна по клику) </summary>

1. Скачайте все файлы по [ссылке](https://support.industry.siemens.com/cs/document/109772803/simatic-step-7-incl-safety-and-wincc-v16-trial-download?dti=0&lc=en-KW) в две отдельные папки:
  - STEP 7 Professional V16 SP2 (DVD 1, DVD 2, SHA-256 checksum)
  ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.10/Step7v16_1.png)
  - SIMATIC STEP 7 PLCSIM V16 SP2 for STEP 7 Basic and STEP 7 Professional (включая SHA-256 checksum)
    ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.10/Step7v16_2.png)
2. Запустите установочный файл TIA_Portal_Step7_Prof_Safety_WINCC_Adv_Unified_V16.exe, пройдите стандартную процедуру установки.
3. Запустите установочный файл SIMATIC_S7PLCSIM_V16.exe, пройдите стандартную процедуру установки.

  -----
  
</details>
  
*ОБРАТИТЕ ВНИМАНИЕ! В независимости от используемой версии программы устанавливается ее демо-версия. Функционал будет ограничен спустя 21 день после установки. Рекомендуется установка софта на виртуальной машине. Как это сделать, описано в [инструкции](https://docs.google.com/presentation/d/1psnSlotXT7cr8ECnaZaTCDLnIyYOGUzCArLeydeRztY/edit?usp=sharing).*

------

### Инструменты/ дополнительные материалы, которые пригодятся для выполнения задания

1. [Google.Диск](https://drive.google.com/drive/u/0/my-drive)
2. Сайты производителей автоматики:
- датчики: [BALLUFF](https://www.balluff.com/ru-ru), [OMRON](https://industrial.omron.ru/ru/home), [ОВЕН](https://owen.ru/)
- элементы автоматики: [SCHNEIDER ELECTRIC](https://www.se.com/ru/ru/)
- ПЛК, модули ввода/вывода, периферийные и интерфейсные модули, частотные преобразователи, регулирующие клапаны: [SIEMENS](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru)
3. [TIA Portal v13](https://support.industry.siemens.com/cs/document/78793685/simatic-step-7-(tia-portal)-v13-trial-download?dti=0&lc=en-DE)
4. [Инструкция по созданию виртуальной машины](https://docs.google.com/presentation/d/1psnSlotXT7cr8ECnaZaTCDLnIyYOGUzCArLeydeRztY/edit?usp=sharing)
5. [ГОСТ 21.208-2013](https://mvif.ru/uslovnyie-oboznacheniya-priborov-i-sredstv-avtomatizaczii-v-sxemax-gost-21.404-85)
6. [Техническое задание](https://docs.google.com/document/d/1Q0ODET9wv9G1nzHl13mzmrpZ0cfT2YczUlS8IE5zFis/edit?usp=sharing)
7. [Шаблон спецификации](https://docs.google.com/spreadsheets/d/1aTwbcsF_Wrfi-dd64A1or906VzEMH9smy5EqbGPL0Jg/edit?usp=sharing)
8. [Шаблон для курсового проекта](https://docs.google.com/document/d/1Xz9LoDJ5GSJd0NKZgSEUXIXm_1DkrAzvoSbFq15mWaU/edit?usp=sharing)

-----

### Инструкция к выполнению курсовой работы

1. Выполните установку необходимых программных инструментов из **Чеклиста готовности к курсовой работе**.
2. Сделайте копию [Шаблона для курсового проекта](https://docs.google.com/document/d/1Xz9LoDJ5GSJd0NKZgSEUXIXm_1DkrAzvoSbFq15mWaU/edit?usp=sharing) себе на Google Disk.
3. Зайдите в «Настройки доступа» скопированного вами шаблона и выберите доступ «Просматривать могут все в Интернете, у кого есть ссылка». Ссылка на инструкцию [Как предоставить доступ к файлам и папкам на Google Диске](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop).
4. В названии файла введите вашу фамилию и имя.
5. Скопируйте текст задания в свой документ.
6. В соответствии с [техническим заданием](https://docs.google.com/document/d/1Q0ODET9wv9G1nzHl13mzmrpZ0cfT2YczUlS8IE5zFis/edit?usp=sharing) подберите датчики на сайтах производителей, указанных в чеклисте готовности к курсовой работе.
7. Создайте копию спецификации на своём диске и заполните её в разделе [«Датчики»](https://docs.google.com/spreadsheets/d/1aTwbcsF_Wrfi-dd64A1or906VzEMH9smy5EqbGPL0Jg/edit#gid=340646123&range=A1) в соответствии с подобранными вами датчиками.
8. Аналогичным образом подберите регуляторы и исполнительные механизмы (при необходимости).
9. Заполните спецификацию в разделах [«Регуляторы»](https://docs.google.com/spreadsheets/d/1aTwbcsF_Wrfi-dd64A1or906VzEMH9smy5EqbGPL0Jg/edit#gid=930614803&range=A1) и [«Исполнительные механизмы»](https://docs.google.com/spreadsheets/d/1aTwbcsF_Wrfi-dd64A1or906VzEMH9smy5EqbGPL0Jg/edit#gid=934707263&range=A1) в соответствии с подобранными вами компонентами.
10. Подберите компоненты электрического шкафа для данной АСУ ТП и заполните спецификацию в разделе [«Автоматика»](https://docs.google.com/spreadsheets/d/1aTwbcsF_Wrfi-dd64A1or906VzEMH9smy5EqbGPL0Jg/edit#gid=581303739&range=A1).
11. Сконфигурируйте аппаратную конфигурацию проекта, добавив в нее все подобранные элементы автоматики. 
12. * 
13. Разработайте HMI-проект для АСУ ТП в программе WinCC и проверьте его работу в симуляторе.
14. Сохраните проект и разместите его на своём Google диске.
15. Вставьте в соответствующие абзацы вашего «Шаблона для курсового проекта» ссылки на выполненные задания.
16. Для проверки курсового проекта преподавателем отправьте ссылку на ваш документ в личном кабинете.
17. Любые вопросы по решению заданий задавайте в чате учебной группы.


-----

### Критерии оценки

Зачёт по курсовой работе может быть получен, если работа соответствует следующим критериям:

1. Оборудование подобрано корректно по необходимым параметрам, все подобранное оборудование логично сочетается между собой.
2. HMI-проект размечен в соответствии с составом системы.
