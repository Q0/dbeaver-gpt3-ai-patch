# dbeaver-gpt3-ai-patch
Патч base_url для DBeaver Plugin AI через vsegpt.ru

## В чем суть

DBeaver не имеет возможности изменять base_url для плагина ChatGPT. Этот патч заменяет обращение к API ChatGPT на https://api.vsegpt.ru и позволяет использовать ключ от vsegpt.

## Инструкция

Нужно заменить файл `service-0.18.2.jar` в `"C:\Users\USER\AppData\Local\DBeaver\configuration\org.eclipse.osgi\116\data\-1336785538\plugins\org.jkiss.bundle.gpt3_0.18.3\lib\"`

Путь до файла у каждого будет разный, поэтому используйте поиск в директории `C:\Users\USER\AppData\Local\DBeaver\configuration` по слову `GPT`.
