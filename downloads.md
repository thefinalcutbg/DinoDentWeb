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
     <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/2.6.1/DinoDentSetup.exe"><img src="/assets/images/win.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/2.6.0/dinodent-macos.dmg"><img src="/assets/images/mac.png"></a>
  </div>

</div>

- [Инструкции за инсталация под Windows](#инструкции-за-инсталация-под-windows)

## Най-последна стабилна версия: 2.6.1 (03.08.2025)
- HOTFIX: Оправен е бъгът при който понякога при първия изпратен към НЗИС амбулаторен лист не се включва подписа на пациента (докладван от <b>Борислав Первазов</b>)
- Добавена възможност за изпращане на генерирания с пен таблет подпис на пациента към НЗИС
- В пациентското досие се визуализират разликите между параметрите на текущото спрямо предходното пародонтално измерване (по идея на <b>д-р Иван Желязков</b>)
- Коригиран е форматът на месечния отчет към НЗОК при подаване на чуждестранни граждани с идентификатор от тип 4 (благодарение на <b>д-р Боян Ненчев</b>)
- В раздела за НЗОК месечните известия и подадените файлове се зареждат автоматично, ако има включен КЕП

[история на версиите](/changelog/)

## Инструкции за инсталация под Windows

- Тъй като нито инсталаторът, нито самата програма са подписани с валиден сертификат за дистрибуция
  под Windows (който струва <b>$400 годишно</b>), при сваляне и инсталиране на програмата ще получите няколко предупредителни съобщения. Следвайте стъпките описани по-долу:

![image-center](/assets/images/wininstr0.png){: .align-center}<br>

- При отваряне на инсталатора с <b>Microsoft Edge</b> ще ви излезе още едно съобщение:

![image-center](/assets/images/wininstr1.png){: .align-center}<br>

- При стартиране на инсталатора или програмата e възможно отново да получите съобщение от <b>Microsoft Defender SmartScreen</b>:

![image-center](/assets/images/wininstr2.png){: .align-center}<br>
