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
     <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v1.16.0/DinoDentSetup.exe"><img src="/assets/images/win.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v1.15.2/dinodent-macos.dmg"><img src="/assets/images/mac.png"></a>
  </div>

</div>

- [Инструкции за инсталация под Windows](#инструкции-за-инсталация-под-windows)

## Най-последна стабилна версия: 1.16.0 (27.10.2024)
- Добавен график за посещенията (необходим е профил в Google и достъп до интернет)
- Добавени опции ПОС терминал и комбинирано плащане към реквизит Начин на плащане във формата за фактурата (по предложение на <b>Златина Бегова</b>)
- Добавена възможност за търсене от списък с всички пациенти при създаване на нов медицински документ (функционалността се активира от Настройки)
- Оправен е бъгът при който при промяна на датата на нова манипулация излиза грешка, че последната не е избрана от списъка
- При изчисляване на очакваната сума спрямо месечния отчет към НЗОК вече се взимат под внимание населените места с неблагоприятни условия
- Село Ракита, общ. Червен бряг, обл. Плевен е добавено към списъка на населени места с неблагоприятни условия (благодарение на <b>д-р Петър Първанов</b>)
- Премахнато е предупредителното съобщение, че адресът по дейност не е в списъка с неблагоприятни условия
- Настройките за автоматично извличане на данни от ПИС и НАП са преместени в секция Договор с НЗОК
- Оправен е бъгът при който понякога програмата забива когато потребителят затвори таб който не е на фокус

[история на версиите](/changelog/)

## Инструкции за инсталация под Windows

- Тъй като нито инсталаторът, нито самата програма са подписани с валиден сертификат за дистрибуция
под Windows (който струва <b>$400 годишно</b>), при сваляне и инсталиране на програмата ще получите няколко предупредителни съобщения. Следвайте стъпките описани по-долу:

![image-center](/assets/images/wininstr0.png){: .align-center}<br>

- При отваряне на инсталатора с <b>Microsoft Edge</b> ще ви излезе още едно съобщение:

![image-center](/assets/images/wininstr1.png){: .align-center}<br>

- При стартиране на инсталатора или програмата e възможно отново да получите съобщение от <b>Microsoft Defender SmartScreen</b>:

![image-center](/assets/images/wininstr2.png){: .align-center}<br>
