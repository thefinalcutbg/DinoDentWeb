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
     <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v2.4.2/DinoDentSetup.exe"><img src="/assets/images/win.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v2.4.2/dinodent-macos.dmg"><img src="/assets/images/mac.png"></a>
  </div>

</div>

- [Инструкции за инсталация под Windows](#инструкции-за-инсталация-под-windows)

## Най-последна стабилна версия: 2.4.2 (02.04.2025)

- Промяната на датата на започване на лечението вече не променя датата на всички дейности при месечните амбулаторни листове, ако не е попълнен договор с НЗОК
- По изискване на РЗОК-Пловдив е добавено допълнително поле за въвеждане на адрес на практиката в свободен текст, в случай че лекарят се отчита към няколко РЗОК едновременно (благодарение на <b>д-р Диана Кунева</b>)
- Възможност за създаване на несъществуващ лекарски профил при добавяне на нова практика в общите настройки от прозореца за вход
- В първите 5 работни дни от текущия месец, отчетът към НЗОК се генерира по подразбиране за предишния месец
- Програмата вече отваря правилната директория при запазване на финансов документ като PDF

[история на версиите](/changelog/)

## Инструкции за инсталация под Windows

- Тъй като нито инсталаторът, нито самата програма са подписани с валиден сертификат за дистрибуция
  под Windows (който струва <b>$400 годишно</b>), при сваляне и инсталиране на програмата ще получите няколко предупредителни съобщения. Следвайте стъпките описани по-долу:

![image-center](/assets/images/wininstr0.png){: .align-center}<br>

- При отваряне на инсталатора с <b>Microsoft Edge</b> ще ви излезе още едно съобщение:

![image-center](/assets/images/wininstr1.png){: .align-center}<br>

- При стартиране на инсталатора или програмата e възможно отново да получите съобщение от <b>Microsoft Defender SmartScreen</b>:

![image-center](/assets/images/wininstr2.png){: .align-center}<br>
