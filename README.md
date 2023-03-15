# Курсовая работа «Аппаратные средства АСУ ТП» по курсу «Аппаратное обеспечение (Hardware)»

### Цель проекта

Создать аппаратные конфигурации проекта АСУ ТП. 

Вам предстоит:

- создать проект аппаратной конфигурации для АСУ ТП;
- подобрать устройства для АСУ ТП на сайтах ведущих производителей;
- разработать спецификацию на закупку по основным видам оборудования для созданного проекта АСУ ТП: датчики, регуляторы, исполнительные механизмы.

-----

### Чеклист готовности к курсовой работе

- Ознакомьтесь с сайтами ведущих производителей оборудования для новой АСУ ТП. 

Список производителей: датчики: [BALLUFF](https://www.balluff.com/ru-ru), [OMRON](https://industrial.omron.ru/ru/home), [ОВЕН](https://owen.ru/); элементы автоматики: [SCHNEIDER ELECTRIC](https://www.se.com/ru/ru/); ПЛК, модули ввода/вывода, периферийные и интерфейсные модули, частотные преобразователи, регулирующие клапаны: [SIEMENS](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru); частотные преобразователи, регулирующие клапаны: [DANFOSS](https://www.danfoss.com/ru-ru/), [SIEMENS](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru).

 - Изучите описание обозначений приборов и средств автоматизации в схемах согласно [ГОСТу 21.208-2013](https://mvif.ru/uslovnyie-oboznacheniya-priborov-i-sredstv-avtomatizaczii-v-sxemax-gost-21.404-85). 

- Зарегистрируйтесь на [портале Siemens](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru) и получите персональный логин и пароль для входа в систему. Процесс регистрации описан в [инструкции](https://docs.google.com/presentation/d/1RPHvCE2OxBbHRMWSAV2E-HxscZvR2nRIZVHCy8hvjJE/edit?usp=sharing).

- Загрузите и установите программное обеспечение для создания проекта PLC Siemens, входящее в пакет TIA Portal с [официального ресурса Siemens](https://support.industry.siemens.com/cs/document/78793685/simatic-step-7-(tia-portal)-v13-trial-download?dti=0&lc=en-DE).

**Примечание:** Для основного задания проекта можно воспользоваться любой версией TIA Portal. Если вы планируете выполнять дополнительный необязательный блок задания под звёздочкой (_*_), то используйте только TIA Portal v16.
<details>
  <summary> Подсказка по установке TIA Portal V13 (доступна по клику)</summary>
  
  
1. Скачайте все файлы по [ссылке](https://support.industry.siemens.com/cs/document/109745155/simatic-step-7-including-plcsim-v13-sp2-trial-download?dti=0&lc=en-DE) в две отдельные папки:
  - STEP 7 Professional V13 SP2 (DVD 1, DVD 2, SHA-256 checksum)
  ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.6/Step7_1.png);
  - SIMATIC STEP 7 PLCSIM V13 SP2 for STEP 7 Basic and STEP 7 Professional (включая SHA-256 checksum)
    ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.6/Step7_2.png).
2. Запустите установочный файл SIMATIC_STEP_7_Professional_V13_SP2_Upd4.exe, пройдите стандартную процедуру установки.
3. Запустите установочный файл SIMATIC_S7_PLCSIM_V13_SP2.exe, пройдите стандартную процедуру установки.

    ---
  
</details>

<details>
  <summary> Подсказка по установке TIA Portal V16 (доступна по клику) </summary>

1. Скачайте все файлы по [ссылке](https://support.industry.siemens.com/cs/document/109772803/simatic-step-7-incl-safety-and-wincc-v16-trial-download?dti=0&lc=en-KW) в две отдельные папки:
  - STEP 7 Professional V16 SP2 (DVD 1, DVD 2, SHA-256 checksum)
  ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.10/Step7v16_1.png);
  - SIMATIC STEP 7 PLCSIM V16 SP2 for STEP 7 Basic and STEP 7 Professional (включая SHA-256 checksum)
    ![image](https://github.com/netology-code/phd-homeworks/blob/main/6.10/Step7v16_2.png).
2. Запустите установочный файл TIA_Portal_Step7_Prof_Safety_WINCC_Adv_Unified_V16.exe, пройдите стандартную процедуру установки.
3. Запустите установочный файл SIMATIC_S7PLCSIM_V16.exe, пройдите стандартную процедуру установки.

  -----
  
</details>

<details>
  <summary> Подсказка по распаковке архиватором WinRAR (доступна по клику) </summary>

Если скачанный дистрибутив TIA Portal содержит некоторые файлы с расширением 001, это вызовет проблему при распаковке данных.

Это происходит, потому что некоторые версии архиватора WinRAR, установленные на ПК, ассоциируют файлы с именем 001, как файлы с расширением .rar.

Для решения проблемы можно убрать ассоциацию:

1. Найдите архиватор WinRAR, имеющий окончание 001.
2. Откройте его двойным кликом, далее выбирайте Установка ⇒ Интеграция.
3. В окне слева будет перечень форматов, которые по умолчанию ассоциируются с WinRAR.
4. Уберите галочку с формата 001, нажмите ОК и перезагрузите ПК.

Скрин с действиями дан ниже:
 ![image](https://github.com/netology-code/scada-4-homeworks/blob/scada-7/WinRAR.png)

-----
  
</details>
  
*Обратите внимание. Вне зависимости от используемой версии программы устанавливается её демо-версия. Функционал будет ограничен через 21 день после установки. Рекомендуется установка софта на виртуальной машине. Как это сделать, описано в [инструкции](https://docs.google.com/presentation/d/1psnSlotXT7cr8ECnaZaTCDLnIyYOGUzCArLeydeRztY/edit?usp=sharing).*

------

### Инструменты и дополнительные материалы, которые пригодятся для выполнения задания

1. [Google Диск](https://drive.google.com/drive/u/0/my-drive).
2. Сайты производителей автоматики: датчики: [BALLUFF](https://www.balluff.com/ru-ru), [OMRON](https://industrial.omron.ru/ru/home), [ОВЕН](https://owen.ru/); элементы автоматики: [SCHNEIDER ELECTRIC](https://www.se.com/ru/ru/); ПЛК, модули ввода/вывода, периферийные и интерфейсные модули, частотные преобразователи, регулирующие клапаны: [SIEMENS](https://mall.industry.siemens.com/goos/WelcomePage.aspx?regionUrl=/ru&language=ru).
3. [TIA Portal v13](https://support.industry.siemens.com/cs/document/78793685/simatic-step-7-(tia-portal)-v13-trial-download?dti=0&lc=en-DE).
4. [TIA Portal v16](https://support.industry.siemens.com/cs/document/109772803/simatic-step-7-incl-safety-and-wincc-v16-trial-download?dti=0&lc=en-KW).
5. [Инструкция по созданию виртуальной машины](https://docs.google.com/presentation/d/1psnSlotXT7cr8ECnaZaTCDLnIyYOGUzCArLeydeRztY/edit?usp=sharing).
6. [ГОСТ 21.208-2013](https://mvif.ru/uslovnyie-oboznacheniya-priborov-i-sredstv-avtomatizaczii-v-sxemax-gost-21.404-85).
7. [Техническое задание](https://docs.google.com/document/d/1Q0ODET9wv9G1nzHl13mzmrpZ0cfT2YczUlS8IE5zFis/edit?usp=sharing).
8. [Шаблон спецификации](https://docs.google.com/spreadsheets/d/1aTwbcsF_Wrfi-dd64A1or906VzEMH9smy5EqbGPL0Jg/edit?usp=sharing).
9. [Шаблон для курсового проекта](https://docs.google.com/document/d/1Xz9LoDJ5GSJd0NKZgSEUXIXm_1DkrAzvoSbFq15mWaU/edit?usp=sharing).

-----

### Инструкция к выполнению курсовой работы

1. Выполните установку необходимых программных инструментов из **чеклиста готовности к курсовой работе**.
2. Сделайте копию [шаблона для курсового проекта](https://docs.google.com/document/d/1Xz9LoDJ5GSJd0NKZgSEUXIXm_1DkrAzvoSbFq15mWaU/edit?usp=sharing) себе на Google Диск.
3. Зайдите в «Настройки доступа» скопированного вами шаблона и выберите доступ «Просматривать могут все в Интернете, у кого есть ссылка». [Инструкция, как предоставить доступ к файлам и папкам на Google Диске](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop).
4. В названии файла напишите ваши фамилию и имя.
5. Скопируйте текст задания в свой документ.
6. В соответствии с [техническим заданием](https://docs.google.com/document/d/1Q0ODET9wv9G1nzHl13mzmrpZ0cfT2YczUlS8IE5zFis/edit?usp=sharing) подберите датчики на сайтах производителей, указанных в чеклисте готовности к курсовой работе.
7. Создайте копию спецификации на своём диске и заполните её в разделе [«Датчики»](https://docs.google.com/spreadsheets/d/1aTwbcsF_Wrfi-dd64A1or906VzEMH9smy5EqbGPL0Jg/edit#gid=340646123&range=A1) в соответствии с подобранными вами датчиками.
8. Аналогично подберите регуляторы и исполнительные механизмы при необходимости.
9. Заполните спецификацию в разделах [«Регуляторы»](https://docs.google.com/spreadsheets/d/1aTwbcsF_Wrfi-dd64A1or906VzEMH9smy5EqbGPL0Jg/edit#gid=930614803&range=A1) и [«Исполнительные механизмы»](https://docs.google.com/spreadsheets/d/1aTwbcsF_Wrfi-dd64A1or906VzEMH9smy5EqbGPL0Jg/edit#gid=934707263&range=A1) в соответствии с подобранными вами компонентами.
10. Подберите компоненты электрического шкафа для этой АСУ ТП и заполните спецификацию в разделе [«Автоматика»](https://docs.google.com/spreadsheets/d/1aTwbcsF_Wrfi-dd64A1or906VzEMH9smy5EqbGPL0Jg/edit#gid=581303739&range=A1).
11. Сконфигурируйте аппаратную конфигурацию проекта, добавив в неё все подобранные элементы автоматики. 
12. Разработайте HMI-проект для АСУ ТП в программе WinCC и проверьте его работу в симуляторе.
13. Сохраните проект и разместите его на своём Google диске.
14. Вставьте в соответствующие абзацы вашего «Шаблона для курсового проекта» ссылки на выполненные задания.
15. Чтобы работу проверил преподаватель, отправьте ссылку на ваш документ в личном кабинете.
16. Любые вопросы по решению заданий задавайте в чате учебной группы.

#### **Дополнительное задание к проекту (необязательное)** *

Настройте функцию резервирования на базе PLC S7-1515R/H. Для этого:

1. Добавьте этот PLC в аппаратную конфигурацию созданного проекта.
2. Создайте кольцевую топологию всех устройств в сети.
3. Проверьте работу резервного PLC.

**Примечание:** дополнительное необязательное задание (_*_) возможно только для TIA Portal v16.
Если вы не планируете его выполнять, можно использовать любую версию ПО.

-----

### Критерии оценки

Для зачёта работа должна соответствовать критериям:

1. Оборудование подобрано корректно в соответствии с техническим заданием.
2. Подобранное оборудование логично сочетается между собой.
3. HMI-проект размечен в соответствии с составом системы.

