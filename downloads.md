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
     <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/2.13.0/DinoDentSetup.exe"><img src="/assets/images/win.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/2.13.0/dinodent-macos.dmg"><img src="/assets/images/mac.png"></a>
  </div>

</div>

- [Инструкции за инсталация под Windows](#инструкции-за-инсталация-под-windows)

## Най-последна стабилна версия: 2.13.0 (01.04.2026)

- При добавяне на нова процедура с въведена цена, като източник на финансиране по подразбиране се маркира „Пациент“ (по предложение на <b>д-р Камен Коцилков</b>)
- Добавена възможност за възходящо и низходящо сортиране по колони на редовете в таблиците (по предложение на <b>д-р Божидар Сойтариев</b>)
- Автоматичното попълване на предварително зададени шаблони в бележките към НЗИС е направено по-ненатрапчиво (по молба на <b>д-р Божидар Сойтариев</b>)
- Статус Шиниа/Адхезивен мост вече не се подава към НЗОК като Обтурация (по предложение на <b>д-р Боян Ненчев</b>)
- Процедурите фигуриращи в НРД, но добавени в А.Л. с друг източник на финансиране, вече могат да бъдат отчетени към НЗОК на по-късен етап, като това става от диалоговия прозорец за редакция
- Отстранен е бъгът при който след редактиране на процедура в А.Л., заредена от лечебен план, тя губи асоциацията си с него

[история на версиите](/changelog/)

## Инструкции за инсталация под Windows

- Тъй като нито инсталаторът, нито самата програма са подписани с валиден сертификат за дистрибуция
  под Windows (който струва <b>$400 годишно</b>), при сваляне и инсталиране на програмата ще получите няколко предупредителни съобщения. Следвайте стъпките описани по-долу:

![image-center](/assets/images/wininstr0.png){: .align-center}<br>

- При отваряне на инсталатора с <b>Microsoft Edge</b> ще ви излезе още едно съобщение:

![image-center](/assets/images/wininstr1.png){: .align-center}<br>

- При стартиране на инсталатора или програмата e възможно отново да получите съобщение от <b>Microsoft Defender SmartScreen</b>:

![image-center](/assets/images/wininstr2.png){: .align-center}<br>
