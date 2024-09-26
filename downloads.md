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
     <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v1.15.2/DinoDentSetup.exe"><img src="/assets/images/win.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/v1.15.2/dinodent-macos.dmg"><img src="/assets/images/mac.png"></a>
  </div>

</div>

- [Инструкции за инсталация под Windows](#инструкции-за-инсталация-под-windows)

## Най-последна стабилна версия: 1.15.2 (12.09.2024)
- Подобрен е алгоритъмът за търсене по имена на пациента в раздел Документация
- При фактурирането към ПИС са добавени XML атрибути VAT rate и VAT value, когато фирмата е регистрирана по ДДС
- Автоматичното изпращане на изходен статус към НЗИС е направено опционално и е изключено по подразбиране (активира се от Настройки)
- Премахването на статус Временен зъб вече премахва и всички други негови статуси с изключение на Мост и Шина
- Оправен е бъгът при който програмата позволява въвеждане на пациент без адрес по ЕКАТТЕ
- Оправен е бъгът при който проверката на амбулаторния лист по НЗОК понякога не засича като грешка отчитането на дейност, извършена върху вече екстрахиран зъб

[история на версиите](/changelog/)

## Инструкции за инсталация под Windows

- Тъй като нито инсталаторът, нито самата програма са подписани с валиден сертификат за дистрибуция
под Windows (който струва <b>$400 годишно</b>), при сваляне и инсталиране на програмата ще получите няколко предупредителни съобщения. Следвайте стъпките описани по-долу:

![image-center](/assets/images/wininstr0.png){: .align-center}<br>

- При отваряне на инсталатора с <b>Microsoft Edge</b> ще ви излезе още едно съобщение:

![image-center](/assets/images/wininstr1.png){: .align-center}<br>

- При стартиране на инсталатора или програмата e възможно отново да получите съобщение от <b>Microsoft Defender SmartScreen</b>:

![image-center](/assets/images/wininstr2.png){: .align-center}<br>
