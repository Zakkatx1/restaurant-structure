# Редактирование

## Персонал (Staff)
- Имя           text
- Должность     text
- Телефон       integer id

## Меню (Menu)
- Блюдо_ID      integer
- Категория     text
- Цена          float

## Бронирование (Reservation)
- Клиент_ID     integer
- Дата_время    datetime
- Столик_ID     integer
- Гости         integer

## Заказы (Orders)
- Заказ_ID      integer
- Столик_ID     integer
- Блюдо_ID      integer
- Статус        text (в процессе/готово/оплачено)

## Клиенты (Customers)
- Клиент_ID     integer
- Имя           text
- Телефон       integer
- История_посещений text

## Столики (Tables)
- Столик_ID     integer
- Вместимость   integer
- Статус        text (свободен/занят)

---

**Иванов Петр**  
05.10.2023, 14:30  
Ресторан "Гурман"  
