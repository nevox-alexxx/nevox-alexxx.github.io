# Задачі по рефакторингу коду

-[x] Винести імеджи на один рівень із папкою styles.
-[x] Видалити зайві імеджи.
-[x] Або створити новий файл \_reset.scss і залишити там тільки потрібні css правила, або видалити із вже існуючого файлу зайві правила (я би радив створити новий файл.)
-[x] \_base.scss файл це майже копія \_reset.scss файлу - старайся відслідковувати моменти дублювання.
5. Виправити зауваження, які описані в index.html файлі.
6. Виправити зауваження, які описані в main.scss файлі, а також:
   -[x] Розділити весь файл на окремі файли (можна розбити по секціям)
   2. Видалити всі непотрібні коментарі.
   3. Пропрацювати неймінг класів, щоб він був універсальним, читабельним.
   -[x] Використовувати нестінг на повну.
   5. Не дублювати однакові правила, а об'єднувтаи однакові правила у схожих класах в універсальні класи.
   6. transition issue
   7. Переписати центрування з posisiton на флекс або грід.
   8. Для повторюваних частин стилів створити міксіни, змінні і т.д.

Коли будеш розуміти, що пункт з цього списку виконаний, замість цифри поставь таке `- [x]` - це створить як в списку задач відмічений галочкою квадратик, наприклад:

- [x] Зробити рев'ю і залишити коментарі до фіксів.
