#### Извършване на проверки и обработка на изходните данни

Вече сме направили нужните пресмятания и **следващата стъпка** е да **проверим** дали **получените литри** вино са **достатъчни**. За целта ще използваме **проста условна конструкция** от типа **`if-else`**, като в условието ще **проверим** дали **литрите вино** от реколтата са **повече от** или **равни** на **нужните литри**. 

Ако проверката върне резултат **`true`**, от условието на задачата виждаме, че на **първия ред** трябва да разпечатаме **виното, което сме получили от реколтата**. За да спазим условието **тази стойност** да бъде **закръглена до по-ниското цяло число**, ще използваме метода **`Math.Floor(…)`** при разпечатването й чрез **placeholder**. 

На втория ред има изискване да разпечатаме резултатите, като ги **закръглим към по-високото цяло число**, което ще направим с метода **`Math.Ceiling(…)`**. Стойностите, които трябва да разпечатаме, са на **оставащото количество вино** и **количеството вино, което се пада на един работник**. Оставащото количество вино е равно на **разликата** между **получените литри вино** и **нужните литри вино**. Стойността на това количество ще изчислим в нова променлива, която ще декларираме и инициализираме в **блок тялото** на **`if`**, **преди** разпечатването на първия ред. Количеството вино, което **се полага на един работник**, ще изчислим като **оставащото вино** го **разделим** на **броя** на работниците. 

![](/assets/chapter-3-2-images/04.Harvest-03.png)

Ако проверката ни върне резултат **`false`** от условието на задачата виждаме, че трябва да **разпечатаме разликата** от **нужните литри** и **получените от тази реколта литри вино**. Има условие резултата да е **закръглен към по-ниското цяло число**, което ще направим с метода **`Math.Floor(…)`**.

![](/assets/chapter-3-2-images/04.Harvest-04.png)

### Тестване в Judge системата

Тествайте решението си тук: [https://judge.softuni.org/Contests/Practice/Index/507#3](https://judge.softuni.org/Contests/Practice/Index/507#3).