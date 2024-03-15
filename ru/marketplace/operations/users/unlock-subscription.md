---
title: "Как отвязать купленную в {{ marketplace-full-name }} подписку"
---

# Отвязка подписки

Если вы отвяжете подписку, продукт перестанет работать до тех пор, пока вы не привяжете к ресурсу, приложению или сервису другую активную подписку. Подписка остается активной до конца оплаченного периода вне зависимости от наличия у нее привязки.

Если продукт для {{ compute-name }} доступен и по подписке, и по тарифу `Pay as you go`, при отвязке подписки от виртуальной машины продукт, установленный на нее, станет оплачиваться по тарифу `Pay as you go`. Доступные типы тарифов можно посмотреть на карточке продукта.

Чтобы отвязать подписку:

{% list tabs group=instructions %}

- Консоль управления {#console}

    1. В [консоли управления]({{ link-console-main }}) выберите каталог, в котором находится [подписка](../../concepts/users/subscription.md).
    1. Перейдите на вкладку **{{ ui-key.yacloud.marketplace-v2.label_licenses }}**.
    1. В строке с нужной подпиской нажмите ![image](../../../_assets/console-icons/ellipsis.svg) → **{{ ui-key.yacloud.marketplace-v2.action_detach-subscription }}**.
    1. В открывшемся окне нажмите **{{ ui-key.yacloud.common.continue }}**.

{% endlist %}