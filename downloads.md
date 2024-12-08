---
permalink: /downloads/
title: "Изтегляне"
layout: splash
#date: 2016-08-26
#last_modified_at: 2018-03-22T10:19:56-04:00
#excerpt: "TEST"
#image:
 # path: &image /assets/images/about-michael-collage-2016.jpg
 # width: 1600
 # height: 640
 # feature: *image
#toc: true
---

<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 25%;
  padding: 20px;
  text-align: center;
}

/* Clearfix (clear floats) */
.row::after {
  float: center;
  content: "";
  clear: both;
  display: table;
}
</style>

## Изберете операционна система:

<div class="row">

  <div class="column">
     <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v2.0.0/DinoDentSetup.exe"><img src="/assets/images/win.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v2.0.0/dinodent-macos.dmg"><img src="/assets/images/mac.png"></a>
  </div>

</div>

- [Инструкции за инсталация под Windows](#инструкции-за-инсталация-под-windows)

## Най-последна стабилна версия: 2.0.0 (01.12.2024)
- Обновени са кодовете на процедурите(КСМП) съгласно измененията в Приложение 1а на Наредба 42
- Диагнозите на денталните процедури се вписват по МКБ-10 съгласно Наредба 42 (временно е изключено подаването им към НЗИС)
- Добавянето на нова процедура може да се извърши с двоен клик върху избраните от статуса зъби
- По подразбиране процедурите извън НЗОК се генерират без източник на финансиране
- Амбулаторните листове при лекарите, които не са договорни партньори на НЗОК, се генерират на дневна основа
- При белите рецепти е дoбавена функционалност за запазване на шаблони за често изписвани медикаменти
- При вход в програмата вече не се изисква ръчно въвеждане на УИН (по предложение на <b>д-р Николай Маринов</b>)
- При добавяне на бележки за пациент или конкретен зъб автоматично се попълва текущата дата (по предложение на <b>д-р Иван Желязков</b>)
- Добавена е възможност за избор на сертификат, когато са налични няколко електронни подписа ползващи един и същ драйвер

[история на версиите](/changelog/)

## Инструкции за инсталация под Windows

- Тъй като нито инсталаторът, нито самата програма са подписани с валиден сертификат за дистрибуция
под Windows (който струва <b>$400 годишно</b>), при сваляне и инсталиране на програмата ще получите няколко предупредителни съобщения. Следвайте стъпките описани по-долу:

![image-center](/assets/images/wininstr0.png){: .align-center}<br>

- При отваряне на инсталатора с <b>Microsoft Edge</b> ще ви излезе още едно съобщение:

![image-center](/assets/images/wininstr1.png){: .align-center}<br>

- При стартиране на инсталатора или програмата e възможно отново да получите съобщение от <b>Microsoft Defender SmartScreen</b>:

![image-center](/assets/images/wininstr2.png){: .align-center}<br>
