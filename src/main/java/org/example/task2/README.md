Создайте систему управления производством автомобилей, где каждая фабрика может производить разные компоненты (двигатели, колеса, кузовы) для разных марок автомобилей. Используйте паттерн "Абстрактная фабрика".



- Абстрактная фабрика CarFactory позволяет создавать компоненты для каждой марки автомобилей через конкретные фабрики (ToyotaFactory, BMWFactory).
Каждая фабрика возвращает уникальные компоненты, специфичные для конкретной марки.