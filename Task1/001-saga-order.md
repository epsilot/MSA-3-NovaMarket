# Реестр событий Saga-хореографии оформления заказа


| Этап                       | Тип события | Название             |
|----------------------------|-------------|----------------------|
| Заказ сформирован          | Domain      | OrderFormed          |
| Заказ зарезервирован       | Domain      | ReservationSucceeded |
| Ошибка резерва заказа      | Failure     | ReservationFailed    |
| Адрес доставки сохранён    | Domain      | ShippingAddressSaved |
| Счёт на оплату сформирован | Domain      | InvoiceFormed        |
| Счёт на оплату сформирован | Domain      | Invoice              |
| Оплата успешна             | Domain      | PaymentSucceeded     |
| Ошибка оплаты              | Failure     | PaymentFailed        |
| Заказ отменён              | Domain      | OrderCanceled        |
