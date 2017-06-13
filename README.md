Где резольвер, Лебовски?
========================

В данном репозитории лежат скрипты и конфигурационные файлы для нескольких доменов из [списка РКН](https://github.com/zapret-info/z-i/).

Эти домены выбраны исходя из следующего принципа: пара доменов для https-записей, пара для http и пара для записей вообще без URL-ов.

Цель регистрации доменов из "чёрного списка" **не** так называемая _DNS-атака_, а попытка понять, какие провайдеры производят DNS-резолвинг при обработке выгрузки РКН, а какие — нет.

Для предотвращения "атаки" предприняты следующие меры:

1. для доменов с "малым" числом IP адресов используются уже указанные в выгрузке для соответствующих доменов IP адреса
1. для доменов с "большим" числом IP адресов используются случайные 2048 IP адреса указанные в выгрузке для **каких-либо** доменов

Таким образом, множество IP-адресов, в которые резольвится выгрузка, от этих доменов не должен как-либо измениться.
