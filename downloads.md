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
     <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v2.4.1/DinoDentSetup.exe"><img src="/assets/images/win.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v2.4.1/dinodent-macos.dmg"><img src="/assets/images/mac.png"></a>
  </div>

</div>

- [Инструкции за инсталация под Windows](#инструкции-за-инсталация-под-windows)

## Най-последна стабилна версия: 2.4.1 (06.03.2025)
- Възстановено е изпращането на описанието на МКБ кодовете в месечния отчет към НЗОК
- Коригирани са координатите на отбелязването на типа идентификатор при принтиране на амбулаторен лист извън НЗОК (докладвано от <b>д-р Георги Славчев</b>)
- При наличие на амбулаторен лист, който обхваща няколко страници, полетата за подпис се принтират на последната, вместо на всяка поредна (по предложение на д-р <b>Божидар Сойтариев</b>)
- Амбулаторните листове по НЗОК и извън НЗОК се запазват като отделни PDF файлове
- При зареждането на амбулаторен лист по НРН от НЗИС, полето Дата и час на започване на лечението вече се зарежда правилно, ако е било подадено от предходния софтуер във формат различен от очаквания (благодарение на <b>д-р Дора Аргирова</b>)

[история на версиите](/changelog/)

## Инструкции за инсталация под Windows

- Тъй като нито инсталаторът, нито самата програма са подписани с валиден сертификат за дистрибуция
под Windows (който струва <b>$400 годишно</b>), при сваляне и инсталиране на програмата ще получите няколко предупредителни съобщения. Следвайте стъпките описани по-долу:

![image-center](/assets/images/wininstr0.png){: .align-center}<br>

- При отваряне на инсталатора с <b>Microsoft Edge</b> ще ви излезе още едно съобщение:

![image-center](/assets/images/wininstr1.png){: .align-center}<br>

- При стартиране на инсталатора или програмата e възможно отново да получите съобщение от <b>Microsoft Defender SmartScreen</b>:

![image-center](/assets/images/wininstr2.png){: .align-center}<br>
