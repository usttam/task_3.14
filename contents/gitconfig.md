[<<< к содержанию](/readme.md)
## git config

Команда настройки параметров для *Git* на вашем компьютере.

Первое, что вам следует сделать после установки *Git* — указать ваше имя и адрес электронной почты. Каждый коммит в *Git* содержит эту информацию, и она включена в коммиты, передаваемые вами, и не может быть далее изменена:

__Пример:__

```bash=
git config --global user.name "Your Name"
git config --global user.email "your_email@whatever.com"
```