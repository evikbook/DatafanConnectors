# Power BI Desktop коннектор

1. Перед установкой коннектора, PowerBI необходимо закрыть.
2. Скачайте [файл коннектора](https://github.com/evikbook/DatafanConnectors/blob/master/PowerBi/Datafan.mez) в папку `[Documents]\Power BI Desktop\Custom Connectors`, если ее не существует, то сначала создать ее.
2. Откройте Power BI Desktop

Обратите внимание: чтобы загружать коннекторы сторонних разработчиков (Datafan.pro), вам необходимо снизить уровень безопасности для расширений в Power BI Desktop.

1. Перейдите в Файл | Параметры и настройки | Параметры
2. Перейдите на вкладку "Безопасность".
3. В разделе _Расширения данных_ выберите _Разрешить загрузку любого расширения без предупреждения или проверки_.
4. Перезапустите Power BI Desktop.

# Если после публикации отчета в Power BI Services необходимо автообновление данных

1. Вам необходимо установить на свой компьютер [On-premises data sources with a Power BI gateway](https://powerbi.microsoft.com/ru-ru/gateway/)
2. [Далее следовать инструкции](https://docs.microsoft.com/ru-ru/data-integration/gateway/service-gateway-install)

# Поддержка работы коннектора

https://datafan.pro/support/

# PowerBi connector

1. Copy the extension file Datafan.mez into the `[Documents]\Power BI Desktop\Custom Connectors` directory
2. Open Power BI Desktop

Note, to load extensions during development, you will need to lower the security level for extensions in Power BI Desktop to enable loading unsigned/uncertified connectors.

1. Go to File | Options and settings | Options
2. Go the Security tab
3. Under _Data Extensions_, select _Allow any extension to load without warning or validation_
4. Restart Power BI Desktop

# If you need to auto-refresh data in the Power BI cloud

1. You need to install [On-premises data sources with a Power BI gateway](https://powerbi.microsoft.com/en-us/gateway/)
2. [Setup Instruction](https://docs.microsoft.com/en-us/data-integration/gateway/service-gateway-install)

# Support

https://datafan.pro/support/
