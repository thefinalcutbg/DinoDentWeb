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
     <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v2.4.0/DinoDentSetup.exe"><img src="/assets/images/win.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v2.4.0/dinodent-macos.dmg"><img src="/assets/images/mac.png"></a>
  </div>

</div>

- [Инструкции за инсталация под Windows](#инструкции-за-инсталация-под-windows)

## Най-последна стабилна версия: 2.4.0 (18.02.2025)
- Възможност за цветово кодиране на всеки пациент (по идея на <b>д-р Божидар Сойтариев</b>)
- Прозорецът за онлайн пациентско досие е изцяло пренаписан и включва възможност за справки за извършени дейности и издадени документи от локалната база данни (по предложение на <b>д-р Божидар Сойтариев</b>)
- Добавена възможност за избор между генериране на амбулаторните листове на месечна или на дневна основа за лекарите, които не са договорни партньори на НЗОК
- В потребителския интерфейс са премахнати всички функционалности свързани с ПИС, ако няма посочен договор по НЗОК
- Коригиран е форматът на декларацията за тотални протези по НЗОК
- Оправен е бъгът при който GDPR декларациите не могат да се запазват като PDF файлове (докладван от <b>д-р Томислав Стойков</b>)
- Възобновена е възможността за докладване на алергии в НЗИС
- Добавянето на шаблон към бележките за процедурите вече не изтрива съществуващия текст
- Добавено с. Храбърско, общ. Божурище, обл. София област към списъка на населени места с неблагоприятни условия (благодарение на <b>д-р Мая Марчева</b>)

[история на версиите](/changelog/)

## Инструкции за инсталация под Windows

- Тъй като нито инсталаторът, нито самата програма са подписани с валиден сертификат за дистрибуция
под Windows (който струва <b>$400 годишно</b>), при сваляне и инсталиране на програмата ще получите няколко предупредителни съобщения. Следвайте стъпките описани по-долу:

![image-center](/assets/images/wininstr0.png){: .align-center}<br>

- При отваряне на инсталатора с <b>Microsoft Edge</b> ще ви излезе още едно съобщение:

![image-center](/assets/images/wininstr1.png){: .align-center}<br>

- При стартиране на инсталатора или програмата e възможно отново да получите съобщение от <b>Microsoft Defender SmartScreen</b>:

![image-center](/assets/images/wininstr2.png){: .align-center}<br>
