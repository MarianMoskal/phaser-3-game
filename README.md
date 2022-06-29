# phaser-3-game

My Fantasy: Make Your Story
GDD TZ

Стак технологий:

- You must use ​Phaser3 framework​ for UI
- UI must be adaptable for mobile
- (Extra) Adaptable for playable ads format will be a plus

Посилання до App Store:
https://apps.apple.com/us/app/id1491717191

Опис:
Гра основана на геймплеї My Fantasy: Make Your Story і використовує механіку вибору опцій.

Екрани:
Інтро (анімація);
Туторіал (оверлей);
Геймплей (екран 1);
Геймплей (екран 2);
Геймплей (екран 3);
Емейзінг скрін (анімація);
Луз скрін (анімація);
Енд карта.

Вимоги:
Довжина по часу: не менше 7 секунд від першого тапу.
Довжина по тапах: не менше 4х тапів.
Орієнтація екрану: горизонтальна \ вертикальна.

Інтро:

Програється швидка діалогова анімація в який на темному оверлеї з’являються іконка жіночого персонажа з текстовим блоком.
Текстовий блок: “I received an invitation to the party!”
Програється анімація здивування.
Текстовий блок: “I need to prepare my appearance”.
Програється анімація радості і знаходження ідеї.

Довжина по часу: 1, 5 секунд.

Туторіал:

З'являється головний екран гри з темним оверлеєм.
Без темного оверлея з’являється жіночий персонаж.
Над темним оверлеєм з’являється текстовий блок: “Choose your appearance”.
Без темного оверлея: іконка опції вибору 1 (плаття 1) та іконка опції вибору 2 (костюм 2).
Над темним оверлеєм з’являється хінт поінтер, який почергово вказує на іконку опції вибору 1 (плаття 1) та на іконку опції вибору 2 (костюм 2).
Якщо гравець тапає на будь-яку іконку опції вибору - то чорний оверлей; хінт поінтер та текстовий блок зникають. Іконки опції вибору змінюються на іконку опції вибору 1 (аксесуар 1) та на іконку опції вибору 2 (аксесуар 2).
Починається основний геймплей.

Основний геймплей:

Гравець почергово вибирає з 2х опіцій вибору декоративні елементи. Ці елементи відображаються з анімацією на персонажу після вибру гравця. Після відображення іконки опції вибору змінюються на наступні.
Ігровий прогрес відображається на прогрес барі. Прогрес бар має 4 ділення.

Екран 1: гравець обирає аксесуари 1-2;
Екран 2: гравець обирає аксесуари 3-4;
Екран 2: гравець обирає мейкап 1-2.

При кожному виборі гравця програється анімація радості персонажа.

Якщо гравець не обирає з опції вибору після 2х секунд з’являється хінт поінтер, що почергово показує на опції вибору.

Після останнього вибору гравцю демонструється Емейзінг Скрін (анімація) або Луз Скрін;
В цій анімації жіночий персонаж зі результатом виборів зустрічається разом з чоловічим персонажем на вечірці в клубі.
Чоловічий персонаж в кежуал костюмі.
В залежності від початкового вибору гравця гра демонструє або Емейзінг Скрін з Енд картою або Луз Скрін.

Емейзінг скрін (залежить від модифікації):
Якщо вибране плаття 1.
Компоненти:
Жіночий персонаж;
Чоловічий персонаж з текстовим блоком “You are beautiful!”
Анімація радості жіночого персонажа;
Бекграунд;
Партікли.

Луз Скрін:
Якщо вибраний костюм 2.
Компоненти:
Жіночий персонаж;
Чоловічий персонаж з текстовим блоком “What a weird appearance!”
Анімація суму жіночого персонажа;
Бекграунд;

Після анімації з’являється чорний оверлей.
Певерх оверлею анімована кнопка ретраю.
Текстовий блок “Retry!”

Нотаток: Будь який тап на Ретрай Скріні відправляє гравця в магазин.

Енд карта:

Компоненти:
Текстовий блок: “ Swipe to play!”;
Бекграунд;
Анімовані стрілки що показують свайп рух.

Нотаток: Будь який тап чи свайп на Енд карті відправляє гравця в магазин.

Нотаток: SQ - Super Quick - перехід в магазин на певному тапі (взаємодії) з грою без анімацій чи Енд карти.
Нотаток: Повна гра - це повний геймплей з Позитивним підтвердженням та Енд картою.

Модифікації:

Повна гра з інтро

Матеріали:

https://www.figma.com/file/yDojHDNdQde7hqAFBEdxEa/playable-ads_for-TZ?node-id=275%3A47

PSD characters:

https://drive.google.com/drive/folders/1EEmFwitMcX0_GhpwX7_PDwxR-t7o_NLg?usp=sharing

Рефенс:

https://drive.google.com/drive/folders/1tDhhBHh6bSwOfvlwl6IoK5FQv8La28aN?usp=sharing
