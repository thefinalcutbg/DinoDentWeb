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
     <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/2.11.0/DinoDentSetup.exe"><img src="/assets/images/win.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/2.11.0/dinodent-macos.dmg"><img src="/assets/images/mac.png"></a>
  </div>

</div>

- [Инструкции за инсталация под Windows](#инструкции-за-инсталация-под-windows)

## Най-последна стабилна версия: 2.11.0 (06.02.2026)

- Добавена възможност за споделена база данни между няколко компютъра чрез локална мрежа. Конфигурацията и поддръжката на сървъра са отговорност на крайния потребител.
- Функционалност за изпращане на SMS в свободен текст към пациента (по предложение на <b>д-р Иван Желязков</b>)
- Добавено поле за ел. поща в данните на пациента и автоматично изпращане на E-mail календарна покана за записания час (по предложение на <b>д-р Сребрина Соклева</b>)
- Добавена възможност за избор на формат на разпечатване на амбулаторните листове - НЗОК/платен прием (по предложение на <b>д-р Божидар Сойтариев</b>)
- Форматът на разпечатания амбулаторен лист за платен прием вече включва пълната номенклатура за дентални статуси от НЗИС
- Възможност за показване на въведените цени в диалоговия прозорец за добавяне на нова процедура (активира се от Настройки->Ценоразпис)
- Подобрения по графичния интерфейс

[история на версиите](/changelog/)

## Инструкции за инсталация под Windows

- Тъй като нито инсталаторът, нито самата програма са подписани с валиден сертификат за дистрибуция
  под Windows (който струва <b>$400 годишно</b>), при сваляне и инсталиране на програмата ще получите няколко предупредителни съобщения. Следвайте стъпките описани по-долу:

![image-center](/assets/images/wininstr0.png){: .align-center}<br>

- При отваряне на инсталатора с <b>Microsoft Edge</b> ще ви излезе още едно съобщение:

![image-center](/assets/images/wininstr1.png){: .align-center}<br>

- При стартиране на инсталатора или програмата e възможно отново да получите съобщение от <b>Microsoft Defender SmartScreen</b>:

![image-center](/assets/images/wininstr2.png){: .align-center}<br>
