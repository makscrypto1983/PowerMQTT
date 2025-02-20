### Описание устройства  

**PowerMQTT** – это компактное и умное устройство для мониторинга энергопотребления, которое измеряет ток, напряжение и мощность подключенных к нему устройств с питанием 5 В. Оно автоматически передает собранные данные на MQTT-сервер, что делает его идеальным решением для интеграции в системы умного дома или IoT-проекты.  

#### Основные возможности:  
1. **Точный мониторинг**: Благодаря использованию высокоточных датчиков (например, INA219), устройство измеряет:  
   - Напряжение (В);  
   - Ток (мА);  
   - Мощность (мВт).  

2. **Беспроводная передача данных**:  
   Устройство передает данные в реальном времени на MQTT-сервер по Wi-Fi, что позволяет отслеживать энергопотребление удаленно.  

3. **Совместимость с IoT-системами**:  
   Легко интегрируется с популярными платформами умного дома, такими как **Home Assistant**, **Node-RED**, или собственными приложениями.  

4. **Компактность и простота использования**:  
   Легкий монтаж, компактные размеры и минимальные требования к настройке.  

#### Примеры применения:  
- **Умный дом**: Отслеживание энергопотребления отдельных устройств.  
- **Прототипирование**: Использование в проектах IoT для мониторинга энергии.  
- **Диагностика**: Контроль за потреблением электроэнергии в реальном времени для выявления неэффективности.  

#### Технические характеристики:  
- **Питание**: 5 В.  
- **Диапазон измерений напряжения**: 0–26 В (зависит от используемого датчика).  
- **Диапазон измерений тока**: до 3 А (INA219).  
- **Интерфейс передачи данных**: MQTT по Wi-Fi.  
- **Комплектующие**: Arduino/ESP32/ESP8266, датчик тока и напряжения (INA219 или ACS712).  

**PowerMQTT** – ваш надежный помощник в измерении и мониторинге энергопотребления!
