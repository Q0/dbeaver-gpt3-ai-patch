# dbeaver-gpt3-ai-patch
Патч base_url для DBeaver Plugin AI через vsegpt.ru

## В чем суть

DBeaver не имеет возможности изменять base_url для плагина ChatGPT. Этот патч заменяет обращение к API ChatGPT на https://api.vsegpt.ru:6070 и позволяет использовать ключ от vsegpt.

## Инструкция

Нужно заменить файл `service-0.11.1.jar` в `C:\Users\USER\AppData\Local\DBeaver\configuration\org.eclipse.osgi\111\data\-1686902550\plugins\org.jkiss.bundle.gpt3_0.11.3\lib`
