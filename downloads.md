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
     <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v2.1.0/DinoDentSetup.exe"><img src="/assets/images/win.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v2.1.0/dinodent-macos.dmg"><img src="/assets/images/mac.png"></a>
  </div>

</div>

- [Инструкции за инсталация под Windows](#инструкции-за-инсталация-под-windows)

## Най-последна стабилна версия: 2.1.0 (15.12.2024)
- Възобновено е изпращането на диагнозите към НЗИС
- Автоматичното попълване на диагнозата при добавяне на нова процедура е направено опционално (изключва се от Настройки)
- Настоящите и миналите заболявания в медицинския статус вече се кодират по МКБ-10 и се изпращат към НЗИС като допълнителни бележки към общия медицински статус
- Добавена е опция "Няма специалност" в номенклатурата за специалността на лекаря по НЗИС. Да се използва вместо специалност "Обща дентална медицина".
- Изключено е подаването към НЗИС на процедури с НЗОК кодове 834, 835, 901, 902 и 903, поради дублирането или липсата им в новата номенклатура за КСМП
- Премахната е старата 6-цифрена номерация на амбулаторните листове по НЗОК
- Подобрено е изобразяването на посещенията в графика (по предложение на <b>д-р Мариян Нейчев</b>)
- Други промени по графичния интерфейс

[история на версиите](/changelog/)

## Инструкции за инсталация под Windows

- Тъй като нито инсталаторът, нито самата програма са подписани с валиден сертификат за дистрибуция
под Windows (който струва <b>$400 годишно</b>), при сваляне и инсталиране на програмата ще получите няколко предупредителни съобщения. Следвайте стъпките описани по-долу:

![image-center](/assets/images/wininstr0.png){: .align-center}<br>

- При отваряне на инсталатора с <b>Microsoft Edge</b> ще ви излезе още едно съобщение:

![image-center](/assets/images/wininstr1.png){: .align-center}<br>

- При стартиране на инсталатора или програмата e възможно отново да получите съобщение от <b>Microsoft Defender SmartScreen</b>:

![image-center](/assets/images/wininstr2.png){: .align-center}<br>
