Установи ГИТ с сайта

Коммандную строку ты знаешь - в гитбаш - те же команды + команды гита - см ниже

Задать глоб параметры локального гита - имя и емайл
git config --global user.name "UNAME"		
git config --global user.email email

См конфиг
git config --list		
cat ~/.gitconfig		

Инициализация в папке
git init
ls -a		

Проверка статуса
git ststus		

Подключить Все или конкретные файлы к проекту после изменения файлов и перед коммитом
git add .		
git add readme.txt		

Коммит проекта
git commit -m "Коммент"		

См лог изменений
git log		

Подключить удаленную репу
git remote add origin https://github.com/ASerp3/P1.git		

Создать ветку 
git branch -M master		

Отправить у даленную репу из локальной
git push -u origin main		


Создать пару ключей публичный и секретный
ssh-keygen -t ed25519 -C aserp3@gmail.com		
ls -a ~/.ssh		
ssh -T git@github.com		

См состояние уд.репы
git remote -v	
	
git push -u origin master		
git push -u origin master		

