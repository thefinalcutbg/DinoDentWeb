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

.row {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.column {
  width: 25%;
  padding: 20px;
  text-align: center;
}

.column img {
  max-width: 100%;
  height: auto;
}
</style>


## Изберете операционна система:

<div class="row">

  <div class="column">
     <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/2.15.0/DinoDentSetup.exe"><img src="/assets/images/win.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/2.15.0/dinodent-macos.dmg"><img src="/assets/images/mac.png"></a>
  </div>
  <div class="column">
    <a href="https://github.com/thefinalcutbg/DinoDent/releases/download/2.15.0/DinoDent-x86_64.AppImage"><img src="/assets/images/linux.png"></a>
  </div>

</div>

- [Инструкции за инсталация под Windows](#инструкции-за-инсталация-под-windows)

## Най-последна стабилна версия: 2.15.0 (10.10.2026)

- Обновени са заглавията на декларациите за НЗОК съгласно НРД 2026-2028
- Добавена е възможност за създаване на персонализирани шаблони за декларации в които автоматично се попълват данните на пациента и тези на лекаря (по предложение на <b>д-р Благой Николов</b>)
- Добавена е AppImage дистрибуция за Linux с минимална версия на glibc 2.38 (по молба на <b>д-р Камен Доков</b>)
- Добавена е интеграция на пен таблети Evolis Sig100Lite, Sig100 и Sig200 под macOS и Linux
- При месечните А.Л. е въведено автоматично синхронизиране между дата на започване, дата на приключване на лечението и датата на отчетените процедури
- Коригирано е динамичното изчисляване на пакета от дейности по НЗОК, при което не се вземаха предвид дейностите отчетени в НЗИС от текущия месец

[история на версиите](/changelog/)

## Инструкции за инсталация под Windows

- Тъй като нито инсталаторът, нито самата програма са подписани с валиден сертификат за дистрибуция
  под Windows (който струва <b>$400 годишно</b>), при сваляне и инсталиране на програмата ще получите няколко предупредителни съобщения. Следвайте стъпките описани по-долу:

![image-center](/assets/images/wininstr0.png){: .align-center}<br>

- При отваряне на инсталатора с <b>Microsoft Edge</b> ще ви излезе още едно съобщение:

![image-center](/assets/images/wininstr1.png){: .align-center}<br>

- При стартиране на инсталатора или програмата e възможно отново да получите съобщение от <b>Microsoft Defender SmartScreen</b>:

![image-center](/assets/images/wininstr2.png){: .align-center}<br>
