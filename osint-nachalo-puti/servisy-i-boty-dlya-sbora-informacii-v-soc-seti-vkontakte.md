---
description: >-
  В данной публикации рассмотрим веб ресурсы, ботов и способы поиска информации
  в популярной социальной сети ВКонтакте (VK).
---

# 🇸🇴 Сервисы и боты для сбора информации в соц-сети ВКонтакте

<div align="center">

<figure><img src="../.gitbook/assets/vk2.jpeg" alt=""><figcaption></figcaption></figure>

</div>

### Предисловие

Социальная сеть Вконтакте разделяет аккаунты пользователей в основном на две категории это “открытые” и “закрытые”. Все мы прекрасно это знаем и также осведомлены о том, какие страницы тяжелее анализировать. Но существует большое множество популярных решений и методов через которые любая страница становится легка к анализу, мы рассмотрим три “уровня” сложности анализа страниц.

### Уровень Лёгкий: Страница открыта

Здесь ситуация весьма лёгкая, буквально вся информация перед нами, можно абсолютно спокойно брать и анализировать. Из обычного анализа тоже можно достать важную инфу, такую как номер и никнейм (ну это уж совсем легко, но и такие случаи бывают).

<div align="center">

<figure><img src="../.gitbook/assets/image-15.png" alt=""><figcaption></figcaption></figure>

</div>

Довольно лёгкий переход к этапу анализа номера телефона, но дополнительно можно ещё поковырять страницу при помощи некоторых приложений ВК.

#### InfoApp

Многофункциональное и местами полезное внутреннее приложение, просматривает дату создания страницы, привязку почты и самое вкусное – есть подтверждение входа или нету.

<div align="center">

<figure><img src="../.gitbook/assets/image-16.png" alt=""><figcaption></figcaption></figure>

</div>

В дополнение приложение предоставляет нам множество ссылок для “проверки настроек конфиденциальности” целевого пользователя.

<div align="center">

<figure><img src="../.gitbook/assets/3.webp" alt=""><figcaption></figcaption></figure>

</div>

<div align="center">

<figure><img src="../.gitbook/assets/5.png" alt=""><figcaption></figcaption></figure>

</div>

Весьма полезное приложение при быстром анализе.

**Tool42**

Не могу не упомянуть ещё одно приложение Tool42, но для меня оно скорее как просто прикольное приложение, которое скорее будет удобно админам различных групп. Так как здесь представлен довольно подробный анализ лайков, активности, комментариев и прочего.

<div align="center">

<figure><img src="../.gitbook/assets/6 (1).png" alt=""><figcaption></figcaption></figure>

</div>

<div align="center">

<figure><img src="../.gitbook/assets/image-20.png" alt=""><figcaption></figcaption></figure>

</div>

Единственное что лично мне малость пригодилось в этом приложении по OSINT, так это пункт “Знакомства через рукопожатия”.

<div align="center">

<figure><img src="../.gitbook/assets/image-21.png" alt=""><figcaption></figcaption></figure>

</div>

Полезен этот пункт мне был в такой ситуации: “допустим ты не совсем общительный человек и других людей к себе в жизнь не намерен пускать просто так. Вот к тебе в друзья добавляется рандомная личность и ты не понимаешь кто это и откуда. Открываешь это приложение и заходишь в этот пункт и видишь, что этот человек знает тебя через твоих знакомых и что всё в порядке.

<div align="center">

<figure><img src="../.gitbook/assets/image-22.png" alt=""><figcaption></figcaption></figure>

</div>

**3D Social Graph**

Ну и так чисто если заняться нечем и прикола ради, можно попробовать вычислить так скажем определённые группы людей в которых состоит пользователь.

<div align="center">

<figure><img src="../.gitbook/assets/image-23.png" alt=""><figcaption></figcaption></figure>

</div>

У приложения очень простенький интерфейс и разобраться в нём не составляет большой сложности. Как видим на примере сверху, у целевого пользователя в основном две крупные группы людей, которых кстати связывает всего один человек. Таким образом мы можем наблюдать и одиночных людей которые ни с кем не связаны.

**Если способы выше не привели к толковым результатам, задействуем способы которые будут описываться на следующем уровне и так с каждым уровнем.**

### Уровень средний: страница закрыта

Ну что же, переходим на уровень сложнее. В данном случае страница целевого пользователя закрыта, а добавляться в друзья будет не совсем корректно со стороны разведки, со стороны социальной инженерии ещё приемлемо, но в этой статье нас интересует именно OSINT.

<div align="center">

<figure><img src="../.gitbook/assets/image-24.png" alt=""><figcaption></figcaption></figure>

</div>

**VKHistoryRobot**

Теперь прошу вспомнить важную заповедь о том, что “Интернет помнит всё”, поэтому заходим в один замечательный телеграм-бот и вписываем ссылку на интересующего нас человека, после чего узнаём историю его профиля, чем давнее профиль, соответственно тем больше шанс найти интересующую нас информацию.

<div align="center">

<figure><img src="../.gitbook/assets/image-25.png" alt=""><figcaption></figcaption></figure>

</div>

Как можем наблюдать, такой вариант развития событий вполне возможен и вам может повести с первого раза. Но чаще разумеется бывают случаи, когда номер частично скрыт. Эти варианты тоже разберём, возьмём такой вот пример:

<div align="center">

<figure><img src="../.gitbook/assets/image-26.png" alt=""><figcaption></figcaption></figure>

</div>

Как видим, здесь у нас скрыто всего 4 последние цифры и с таким раскладом на самом деле ещё можно что-то растолковать.

**Toutatis**

Toutatis – это инструмент, способный извлекать разнообразную информацию из профилей на Instagram, включая адреса электронной почты, номера телефонов и многое другое.

**Установка и использование**

Инструмент доступен в качестве модуля в Python, поэтому устанавливаем легко и просто:

```
pip install toutatis==1.3
```

Для работы кода, нам потребуется ID сессии в Instagram, заходим разумеется лучше в левый аккаунт, нажимаем F12 и ниже будет представлен пример откуда брать sessionid

<div align="center">

<figure><img src="../.gitbook/assets/image-27-1024x173.png" alt=""><figcaption></figcaption></figure>

</div>

Копируем и вставляем в команду для запуска:

`toutatis -u username -s instagramsessionid`

<div align="center">

<figure><img src="../.gitbook/assets/image.jpeg" alt=""><figcaption></figcaption></figure>

</div>

Вот для чего нам и нужен был этот инструмент, для того чтобы узнать последние две цифры номера, аккаунт в Instagram мы разумеется должны были узнать раньше, подробней об этом в прошлой статье.

Далее остаются предпоследние цифры номера которые придётся угадать и перебрать, зато потребуется перебрать лишь две цифры, этот процесс можно автоматизировать через код и автоматически узнавать имя цели, это займёт множество времени.

А теперь рассмотрим последний вот такой вариант:

<div align="center">

<figure><img src="../.gitbook/assets/image-28.png" alt=""><figcaption></figcaption></figure>

</div>

Отправляемся в [LeakedInfoBot](../readme/leakedinfobot-luchshii-bot-dlya-poiska-slitoi-informacii..md), нынче их столько “расплодилось” что практически каждый второй бот это LeakedInfoBot. Все они работают разумеется одинокого и у всех одна база данных, чтобы в этом убедиться, просто зайдите в свою [учётную запись](../readme/leakedinfobot-luchshii-bot-dlya-poiska-slitoi-informacii..md) и узнайте насколько давно вы в “новом боте”.

<div align="center">

<figure><img src="../.gitbook/assets/image-29.png" alt=""><figcaption></figcaption></figure>

</div>

Ну а теперь просто вводим имя и фамилию человека и после чего видим и сверяем первые 6 цифр номера. Разумеется это всё делается в условно-бесплатной версии бота, а если у вас платная версия, то вам и эти способы знать не обязательно. Я не хочу лишний раз платить за то, с чем могу справиться и сам.

<div align="center">

<figure><img src="../.gitbook/assets/image-30.png" alt=""><figcaption></figcaption></figure>

</div>

Если первые цифры номера совпадают, то переходим к toutatis.

**Тяжёлый уровень**

Представим что это такой же закрытый профиль, мы суём его в VKHistoryRobot, но результат нас печалит, а сам пользователь чист как слеза младенца.

<div align="center">

<figure><img src="../.gitbook/assets/image-31.png" alt=""><figcaption></figcaption></figure>

</div>

В этом варианте нам потребуется запомнить город и фамилию с именем нашего целевого аккаунта. Переходим в Глаз Бога, вводим фамилию и имя и нам выпадает результат скрытых номеров.

<div align="center">

<figure><img src="../.gitbook/assets/image-32.png" alt=""><figcaption></figcaption></figure>

</div>

Далее заходим на [сайт](https://region-operator.ru/) с диапазонами мобильных номеров того города который указан на целевом аккаунте и сверяем оператора и первые 6 цифр чтобы узнать какой номер нам нужен.

<div align="center">

<figure><img src="../.gitbook/assets/image-33.png" alt=""><figcaption></figcaption></figure>

</div>

Выбираем интересующий нас город.

<div align="center">

<figure><img src="../.gitbook/assets/25.png" alt=""><figcaption></figcaption></figure>

</div>

Выбираем мобильного оператора у которого сходятся первые 3 цифры.

<div align="center">

<figure><img src="../.gitbook/assets/26.png" alt=""><figcaption></figcaption></figure>

</div>

С кодом 903 ничего не нашлось, а вот с кодом 983 нашлось, теперь мы уверены что искать нужно именно второй номер, а далее пытаемся прибегнуть к способам которые описаны выше.

### Заключение

В этой статье мы рассмотрели множество способов анализа страницы ВК, и несколько путей добычи номера телефона, разумеется если у вас не получился ни один вариант, то ничего страшного, это лишь одна ветка получения номера, о других методах ожидайте в моих дальнейших статьях.