# Chrome-DevTools
Інструменти розробника (від англ. Development tools або скорочено DevTools) ─ це програми, що дозволяють створювати, тестувати і налагоджувати (debug) програмне забезпечення.

Сучасні браузери, Safari, Firefox, Microsoft Edge, Chrome, Яндекс та інші мають вбудовані інструменти розробника, що дозволяють переглянути вихідний код сайту. Окремо встановлювати їх не потрібно. З їх допомогою можна переглядати та налагоджувати HTML сайту, його CSS та Javascript. Також можна перевірити мережевий трафік, споживаний сайтом, його швидкодію та багато інших параметрів.

![Приклад](https://github.com/RomanPravdiuk/Chrome-DevTools/blob/main/Page1.png)

У правому куті розміщеної вище ілюстрації можна побачити структуру веб-сторінки та стилі, застосовані до поточного елемента.Типова веб-сторінка є текстовим файлом у форматі HTML, який визначає структуру та контент сторінки, а також може містити посилання на файли в інших форматах (текст, графічні зображення, відео, аудіо, бази даних та ін), а також гіперпосилання для швидкого переходу на інші веб-сторінки або доступу до посилальних файлів.Декілька веб-сторінок, об'єднаних спільною темою та дизайном, а також пов'язаних між собою посиланнями, утворюють веб-сайт. При цьому сторінки, що створюють веб-сайт, можуть знаходитися на одному або декількох веб-серверах, які можуть розташовуватися в одному дата-центрі або віддалено один від одного, часто в різних країнах.

![Приклад](https://github.com/RomanPravdiuk/Chrome-DevTools/blob/main/Page2.jpeg)

HTML (HyperText Markup Language) - це скелет веб-сторінки. Для того, щоб вся ця історія почала рухатися і потрібен Javascript (календарики, меню, спливаючі вікна, анімація та інше, робиться за допомогою JS). Для надання сторінці божественного вигляду вам знадобиться CSS (каскадні таблиці стилів).

Представимо HTML-документ у найпростішій формі:

![Приклад](https://github.com/RomanPravdiuk/Chrome-DevTools/blob/main/Page3.png)

Фактично HTML-документ складається з елементів (рядок з тегом, що відкриває і закриває, і, власне, сам вміст).
Щоб розширити можливості окремих тегів та більш гнучко керувати вмістом контейнерів, застосовуються атрибути тегів, вони містять інформацію, яку ви не хочете показувати у фактичному контенті.

Атрибут - використовується для визначення характеристик html-елемента і міститься всередині елемента, що відкриває тега. Допустимо використовувати деякі атрибути у тегів, не присвоюючи їм жодного значення. Дивіться приклад нижче, у ньому використовується атрибут disabled, у якого явно не задано значення.

![Приклад](https://github.com/RomanPravdiuk/Chrome-DevTools/blob/main/Page4.png)

Якщо всередині будь-якого тега використовується ще один або навіть кілька інших, це називається вкладеність тегів html.

Використовуємо DevTools на практиці

Доторкнутися спочатку до прихованих браузером DevTools можна дуже просто, використовуючи поєднання клавіш або перейшовши в розділ «Додаткові інструменти / Інструменти Розробника». Також можна штовхнути курсором у будь-яке місце сторінки, натиснути на праву клавішу миші та вибрати "Переглянути код".

