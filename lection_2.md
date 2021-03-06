
### Лекція 2

# GIT

#### _Словник термінів_
- _Репозиторій_ = сховище
- _Git заточена під Linux_ (WSL - це перехід від Windows до Linux)
- _Git Bash_ = оболонка/термінал
- _Термінал_ - це робочий інструмент розробника
- _Frontend_ - відображення в браузері (юзер інтерфейс)
- _Backend_ - механізм роботи поза видимою клієнтською частиною
- _Java Script_ - мова програмування
- _Python_ - мова програмування бекенду
- _Scrum_ - підхід до розробки / фреймворк
- _CSS_ - відображення (колір, форма)
- _Sketch/Figma_ - програми для верстання сайтів
- _Linux_ - безкоштовна операційна система, котра підтримується виключно ком'юніті та на волонтерській основі
- _Сервер_ - залізо з даними; жаргон - код, який щось виконує

##### Тrainee ➞ Junior ➞ Middle ➞ Senior ➞ Tech-lead ➞ Architect ➞ Solution Architect
_все залежить від мотивації та особистісного розвитку_

#### _Системи контролю версій_
_Git Subversion, Mercurial_ - системи, що дозволяють роботу в команді та зберігають історію дій. Ці системи дозволяють відслідковувати зміни файлу, історію, шукати приналежність змін до автора.

_Git Hub_ - мережа для відображення зміни коду.
_Git_ - сохранка у грі.

#### _Команди для термінала_



| Назва команди | Дія команди |
| ------ | ------ |
| ls | виводить інфу де ми знаходимось, в якій директорії |
|ls -a| показ прихованих папок|
| cd | перехід до майбунього шляху  (cd +назва директорії)|
| cd ~/Desktop/module_git|якщо потрібно повернутися назад до папки, що існувала до переходу|
|tree |утиліта, що демонструє дерево папок або файлів у папці|
| git init| проініціалізований гіт по заданому шляху (вкажеться у стрічці після команди) |
|git status| стан файлів у директорії|
|git add (файл.txt)| слідкування за файлом системою git
|git commit -m "first commit"| збереження змін із маркуванням назви зміни в "|
|git branch someName|нова гілка із назвою someName
|git checkout someName/master| перехід на елемент, з якого відбувається дія
|git checkout -b <branch name>| створення та перевірка нової гілки з переключенням на неї автоматично в один хід

##### РОБИ ГІЛКИ ЗАВЧАСНО, РОБИ ГІЛКИ ЧАСТО!!!
🠗🠗🠗
_Коли ми почнемо використовувати гілки та коміти, ми побачимо як вони поєднуються між собою. Але зараз просто запам'ятай, що гілка зберігає роботу теперішнього коміту і всіх його попередників!_
