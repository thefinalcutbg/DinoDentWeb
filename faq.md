---
permalink: /faq/
title: "Често задавани въпроси"
layout: splash
---
<br>

## Какво е DinoDent?
DinoDent е безплатен дентален софтуер с отворен код. Замислен е да бъде от полза на всички лекари по дентална медицина. Всеки е свободен да го ползва за своите нужди, декомпилира или построява използвайки кода от GitHub.

## За кого е предвиден DinoDent?
DinoDent е насочен основно към индивидуални дентални практики. Може да се използва и в клиники, но това би било компромис, тъй като софтуерът не е разработен с тази цел.

## Лицензиран ли е DinoDent за работа с ПИС и НЗИС?
Лиценз за комуникация с [ПИС](https://pis.nhif.bg/){:target="_blank"} и [НЗИС](https://www.his.bg/){:target="_blank"} не съществува. Ако сте вписани в регистъра на БЗС единственото изискване е да имате електронен подпис (личен или фирмен) с който удостоверявате самоличността си пред съответните институции. Няма никакво значение дали обменът на данни с ПИС и НЗИС се осъществява посредством софтуер, браузър или конзола.

## Какви са системните изисквания?
Като стандартно десктоп приложение, DinoDent би трябвало да тръгне на всеки компютър закупен в последните 10 години. Единствените изисквания са <b>64-битов процесор</b> и операционна система
<b>Windows 10</b> (обновен поне до версия 1809) или <b>Windows 11</b> (препоръчително обновени до най-последна версия). Поддръжката на Windows XP, Windows 7 и Windows 8 е официално прекратена от Microsoft и тези операционни системи не се поддържат от DinoDent. 
<b>Минималната версия за macOS е Big Sur (МacOS 11)</b>. 

## Защо при сваляне на инсталатора браузърът и операционната система дават предупреждение за съмнителен файл?
Инсталаторът е с файлово разширение ".exe" което му позволява да прави промени по Вашия компютър (в случая - да инсталира програмата). От съображения за сигурност браузърът и операционната Ви система предупреждават за това. Можете спокойно да неглижирате тези предупреждения, тъй като DinoDent е софтуер с отворен код и това удостоверява че е безопасен за вашия компютър. 

<b>ВАЖНО:</b> Винаги сваляйте инсталатора от официалния сайт на DinoDent - [www.dinodent.bg](https://dinodent.bg/downloads/). Това гарантира, че към него не са прибавени файлове със зловредно съдържание от някой друг.

## Къде се съхранява базата данни на софтуера?
По подразбиране локацията на базата данни е: 

- при Windows:
<b>C:\Users\\(името на акаунта Ви)\AppData\Roaming\DinoDent\database.db</b>

- при macOS:
<b>/Users/(името на акаунта Ви)/Library/Application Support/DinoDent/database.db</b>

При всяка актуализация там се съхраняват и бекъп файловете на базата данни. По желание можете да преместите файла на друго място и да зададете новата локация посредством "Общи настройки" от прозореца за вход в програмата. Ако в директорията на акаунта Ви няма поддиректория "AppData", уверете се че сте позволили показването на скритите директории от настройките на операционната Ви система.

## Може ли да бъде споделена базата данни между няколко компютъра свръзани в мрежа?
Не. Базата данни е вградена (embedded) и не е подходяща за използване в сървърен режим. Ако във Вашата дентална практика имате няколко компютъра свръзани в мрежа, вариантите са два: 

- На всеки от компютрите инсталирате програмата и така всеки един ползва отделна база данни
- Използвате някой от другите дентални софтуери на пазара, които поддържат сървърна функционалност

## Мога ли да съхранявам базата данни в Google Drive, Dropbox, OneDrive или друг доставчик на облачно хранилище, за да я достъпвам от няколко компютъра?
Да, можете, стига да гарантирате, че тя няма да се използва от два различни компютъра едновременно. В противен случай това ще доведе до десинхронизация и загуба на информация. Също така имайте предвид, че като медицинско лице имате отговорност към личните данни на пациентите. Ако нямате базови познания за това как действат облачните хранилища, по-добре не пробвайте.

## Може ли да бъде прехвърлена базата данни от предишния ми софтуер?
Поради големия брой дентални софтуери на пазара и фактът, че всеки от тях има база данни с различна структура, написването и поддръжката на индивидуални скриптове за миграция би била невероятно времеотнемащ процес (т.е. краткият отговор е НЕ). Като алтернативен вариант DinoDent предоставя следните две възможности: 

- <b>Автоматично сваляне на данни от ПИС</b> позволява импортиране на всички пациенти и амбулаторни листове, които сте подавали към НЗОК с месечните отчети през годините. Функционалността се намира в раздел <b>"Месечни отчети и известия" -> "Импортиране на данни"</b>.
- <b>Зареждане на амбулаторен лист от НЗИС</b> чрез въвеждане на неговия НРН идентификатор. Функционалността се намира в раздел "Настройки".

## Програмата ми изписва, че не е намерен КЕП, а електронният ми подпис е включен в компютъра.
Първо се уверете, че сте инсталирали драйвърите за Вашия електронен подпис.

- Драйвъри за <b>StampIT</b> - [изтегли от тук](https://www.stampit.org/bg/page/795){:target="_blank"}
- Драйвъри за <b>B-Trust</b> - [изтегли от тук](https://www.b-trust.bg/client-center/signature-installation){:target="_blank"}
- Драйвъри за <b>InfoNotary</b> - [изтегли от тук](https://www.infonotary.com/?p=technical-support){:target="_blank"}

Ако електронният подпис все още не работи или програмата се загася:
- За карти модел <b>eIDAS 8.1</b> инсталирайте допълнително <b>AWP Identity Manager</b> от [тук](https://installer.id.ee/media/win/installer/AWP-5.3.5-SR1.x64.en-US.msi)
- За карти модел <b>IDPrime940B</b> инсталирайте допълнително <b>OpenSC</b> от [тук](https://github.com/OpenSC/OpenSC/releases/download/0.23.0/OpenSC-0.23.0_win64.msi)

Ако програмата все още не може да се свърже с Вашия КЕП, моля пишете на [dinodentbg@gmail.com](mailto:dinodentbg@gmail.com)

## Мога ли по някакъв начин да помогна за разработването на софтуера?
Дори и да нямате познания по програмиране, ако установите грешки в програмата, моля да ги докладвате на [dinodentbg@gmail.com](mailto:dinodentbg@gmail.com). Всякакви предложения относно нови функционалности също са добре дошли. Можете да подкрепите разработването на софтуера финансово чрез някоя от платформите за дарения посочени [тук](https://dinodent.bg/donate/).
