---
title: Обзор функций
sidebar_position: 1
---

## Что такое AdGuard VPN для Android?

VPN — это идеальный инструмент, который обеспечивает безопасность и анонимность каждого вашего выхода в Сеть. [Как это работает?](/general/how-vpn-works.md) Если не вдаваться в технические подробности, можно сказать, что VPN создаёт безопасный зашифрованный канал между компьютером или мобильным устройством и удалённым VPN-сервером. Таким образом, сохраняется конфиденциальность данных, а также анонимность пользователя, поскольку сторонний наблюдатель видит IP-адрес VPN-сервера, а не фактический пользовательский IP.

**VPN часто используется для:**

* Сохранения безопасности личных данных даже при использовании общественного Wi-Fi
* Предотвращения отслеживания онлайн-активности путём маскировки IP-адреса
* Сокрытия настоящего местоположения для сохранения анонимности

AdGuard VPN для Android может сделать всё это для вас — и даже предложить нечто уникальное. Чтобы узнать, почему AdGuard VPN лучше других VPN-сервисов, прочтите [эту статью](/general/why-adguard-vpn.md).

## Как начать пользоваться AdGuard VPN для Android

Для начала скачайте его из [Google Play](https://play.google.com/store/apps/details?id=com.adguard.vpn) и войдите в свой личный кабинет AdGuard. В случае, если у вас его нет, следует [его создать](https://auth.adguard.com/login.html). Вы можете авторизоваться непосредственно с помощью учётных данных аккаунта AdGuard. Или сделать это через Google или Facebook, но только в том случаае, если ваш аккаунт AdGuard был зарегистрирован с использованием того же адреса электронной почты.

## Главный экран

На главном экране есть две строки, отражающие статус приложения, — Подключено/Отключено — и выбранный режим работы списка исключений — ([Основной/Выборочный](#lists-of-exclusions)). На этом же экране находится кнопка *Подключить/Отключить* и список доступных серверов.

Каждый сервер имеет своё местоположение и показатель пинга, отображающий время отклика сервера. Чем ниже этот показатель, тем быстрее соединение. Самые быстрые серверы всегда находятся в верхней части списка, который состоит более чем из 50 локаций в десятках стран. Вы можете подключиться к наиболее быстрому серверу, нажав на кнопку *Подключить/Отключить*, или выбрав локацию.

## Исключения

Мы сделали всё, чтобы вам было удобно управлять списками исключений сайтов и приложений. AdGuard VPN будет работать только там, где это нужно вам.

### Списки исключений

Как мы уже говорили выше, Списки исключений позволяют выбрать, на каких сайтах AdGuard VPN будет работать, а на каких — нет. Чтобы открыть раздел *Исключения*, нажмите на вторую слева иконку в нижней части экрана.

Есть два режима работы: *Основной* и *Выборочный*. В *Основном режиме* сайты, перечисленные в списке, исключаются из работы VPN. В *Выборочном режиме*, наоборот, VPN работает только на сайтах, указанных в списке.

Добавить домены (например, `google.com`) или поддомены (например, `*.google.com`) сайтов в *Исключения* можно тремя способами: 1) ввести их вручную в приложении, 2) прямо из браузера, нажав кнопку *Поделиться* и выбрав AdGuard VPN в открывшемся списке ниже, 3) из встроенного списка сервисов, разделённых на категории.

![Исключения](https://cdn.adguardvpn.com/public/Adguard/kb/VPN/Screenshots/add_site_android.jpg)
> При ручном добавлении доменов нужно учитывать некоторые нюансы. Например, если вы вручную исключите домен `google.com`, все поддомены `*.google.com` также будут внесены в список исключений. Однако доменные имена с другими доменами верхнего уровня, такие как `google.ru` или `google.it`, не будут исключены. Или вы можете добавить `youtube.com` в исключения, но домен того же сервиса `youtu.be` не попадёт в список. В этом случае безопаснее использовать встроенные списки сервисов, так как мы помещаем туда все поддомены, относящиеся к каждой платформе.

Поскольку в списках сервисов можно деактивировать поддомены, мы добавили иконки, отражающие статус каждого сервиса. Их можно увидеть на главном экране *Исключений* слева от названия каждого сервиса: статус **Полностью включён** обозначен белой галочкой на зелёном фоне, **Полностью отключён** — серым квадратиком, а статус **Частично включён**, означающий, что один или несколько параметров были изменены, — зелёным квадратиком на белом фоне. Хорошая новость: вы всегда можете вернуться к стандартному виду списков, в случае если вы отключили или вовсе удалили какой-либо сайт.

![Исключения](https://cdn.adguardvpn.com/content/kb/vpn/android/statuses.png)

Ещё одна полезная функция — *Импорт/Экспорт списков исключений*. Чтобы воспользоваться ей, нужно выполнить всего четыре шага:

1. Откройте AdGuard VPN на устройстве/в браузере, откуда вы хотите экспортировать списки исключений. Найдите соответствующий раздел и нажмите кнопку *Экспортировать исключения*. Будет загружен архив `adguard_vpn_exclusions.zip`.
2. Внутри архива находятся два файла `.txt`, по одному для каждого из списков — *Основного* и *Выборочного*. Добавьте в них новые исключения, удалите существующие или просто оставьте архив с файлами как есть.
3. При передаче между различными устройствами не забудьте отправить файл `.zip` на устройство для импорта. Например, если вы импортируете списки исключений с устройства Windows на Android, не забудьте предварительно отправить `.zip-файл` на Android.
4. Откройте AdGuard VPN на устройстве, куда вы хотите импортировать архив с готовыми списками исключений. Найдите соответствующий раздел, нажмите кнопку *Импортировать исключения* и выберите архив.

![Импорт/Экспорт](https://cdn.adguardvpn.com/content/kb/vpn/android/imp-exp.png)

### Настройки приложений

В исключения можно легко добавить не только веб-сайты. Выберите, для каких приложений вам нужен AdGuard VPN, а для каких — нет. Нажмите на вторую справа иконку в нижней части экрана, чтобы открыть Настройки приложений. По умолчанию AdGuard VPN работает со всеми приложениями, но вы можете переключить ползунок напротив любого приложения в списке — и отключить AdGuard VPN для него.

Если включён режим *Совместимости* с AdGuard, вы сможете управлять приложениями только через приложение AdGuard. Поэтому при нажатии на кнопку открывается блокировщик.

![Настройки приложений](https://cdn.adguardvpn.com/content/kb/vpn/android/apps_settings.png)

## Настройки

Чтобы попасть в *Настройки*, нажмите на иконку в виде шестерёнки в правом нижнем углу экрана. Первый раздел, который вы там увидите, и которому стоит уделить особое внимание, называется *Настройки приложения*. Благодаря ему вы сможете настроить AdGuard VPN для Android под себя.

![Настройки приложений](https://cdn.adguardvpn.com/content/kb/vpn/android/app_settings.png)

### Автозапуск AdGuard VPN

Переведите переключатель вправо, чтобы активировать автозапуск AdGuard VPN после запуска устройства.

### DNS-серверы

Цель [системы доменных имён](https://adguard-dns.io/kb/general/dns-filtering/#what-is-dns) (DNS) — преобразование имён сайтов в нечто, понятное браузерам, т. е. в IP-адреса. Эта работа выполняется DNS-серверами. AdGuard VPN для Android предлагает на выбор несколько DNS-серверов, каждый из которых обладает особыми свойствами. Например, [AdGuard DNS](https://adguard-dns.io/kb/) устраняет рекламу и защищает ваше устройство от отслеживания, а AdGuard DNS Семейный сочетает функции AdGuard DNS с Безопасным поиском и блокировкой контента для взрослых. Также есть возможность добавить пользовательский DNS-сервер.

### Автозащита

Эта функция включает AdGuard VPN автоматически, когда ваше устройство подключается к сотовой или Wi-Fi сети.

### Kill Switch

Вы можете настроить функцию Kill Switch на своём устройстве Android, следуя простым инструкциям на экране. Зачем вам это нужно? Если по какой-то причине ваше VPN-соединение внезапно прервётся, в то время как вы будете подключены к мобильной сети или общественному Wi-Fi, Kill Switch автоматически отключит интернет-соединение, чтобы не позволить злоумышленникам завладеть вашими данными.

Обратите внимание, что если Kill Switch включён, *Настройки приложений* и *Исключения* не будут работать.

### Тема

Вы можете выбрать тему приложения по умолчанию, тёмную или светлую.

![Тема](https://cdn.adguardvpn.com/content/kb/vpn/android/theme-light-dark.png)

### Расширенные настройки

В *Расширенных настройках* мы разместили пять разделов. Вы можете *Помочь нам стать лучше*, сдвинув переключатель в верхнем блоке. Это действие позволит AdGuard VPN собирать отчеты о сбоях в работе приложения, технические данные и данные о взаимодействии. Информация будет поступать анонимно.

В разделе *Режим работы* вы можете выбрать один из трёх режимов работы приложения: VPN, Прокси и Режим совместимости. В *Режиме VPN* весь трафик автоматически направляется через AdGuard VPN. Когда включён *Режим прокси* (SOCKS5), AdGuard VPN запускает локальный прокси-сервер, доступный для использования другими приложениями для маршрутизации трафика. Используйте этот режим, только если знаете, что делаете. Включённый *Режим совместимости* позволяет AdGuard VPN и Блокировщику рекламы AdGuard работать вместе.

> Обратите внимание, что некоторые функции AdGuard VPN в *режиме Совместимости* не работают: возможность выбора DNS-сервера, Kill Switch и Автозащита. А функция добавления приложений в исключения осуществляется через Блокировщик рекламы AdGuard.

Следующие два раздела — *Уровень логирования* и *Диагностическая информация*. Что касается первой опции, не рекомендуется включать Расширенный или Экстремальный уровень логирования, если это не попросила сделать наша служба поддержки. Диагностическая информация, т. е. локально сохранённая техническая информация об устройстве и соединениях (IP-адрес, ID, ping и т. д.), может быть отправлена нам в случае каких-либо технических проблем.

Последний раздел *Расширенных настроек* — это *Низкоуровневые настройки*. Мы настоятельно рекомендуем не заходить в этот раздел, если вы не обладаете достаточными техническими знаниями или вас не попросила об этом наша служба поддержки. Здесь можно включить «Запись сетевых пакетов» или протокол IPv6 на VPN-интерфейсе, выбрать порт, на котором будет работать прокси-сервер, или версию HTTP-протокола, которую следует использовать.

### Поддержка

В разделе *Поддержка* вы можете оставить отзыв, сообщить об ошибке или экспортировать логи и системную информацию для последующей отправки в службу поддержки.
