# 67 - Формула Моцарта, Бетховен и теория групп {#ch67}

Между музыкой и математикой существует близкая, практически естественная, связь. По крайней мере, есть множество сходств. Равномерно темперированная хроматическая гамма является простым логарифмическим уравнением, а основные интервалы — это соотношения наименьших целых чисел, по которым мозг может отслеживать тоники в аккордовых последовательностях [(68) Теория, сольфеджио]. Для музыканта естественно интересоваться насколько математика участвует в создании музыки. В теории композиции математические преобразования симметрии стали основным средством еще до Баха (Соломон, Ларри). Это неудивительно, так как математика применима практически ко всему, это язык, описывающий все количественно. Изучить взаимосвязь между музыкой и математикой можно на примере математического разбора работ величайших композиторов. Рассмотрим несколько примеров.

Формула Моцарта (Маленькая ночная серенада, K. 525)

Профессор Гарвардского университета Роберт Левин (Левин, Роберт) в декабре 1977 г. провел лекцию «Почерк Моцарта: статистический анализ концертов» в которой затронул тему «сложной и особой иерархии, лежащей в основе концертной формы Моцарта» на научном семинаре компании Bell Laboratories (квартал Марри-Хилл, Нью-Джерси). Я благодарен Брайану Кернигану (соавтору книги «Язык программирования Си») за то, что он нашел записи этой лекции — они хранились на его компьютере более 30 лет!

Профессор Левин говорил об особой иерархии музыкальных мотивов, которая может быть использована для атрибуции сочинений Моцарта. С одной стороны, из-за своего незнания музыкальной теории я мало что понял в лекции, я ожидал услышать о ясной и понятной музыкальной структуре. С другой стороны, благодаря лекции я заинтересовался структурами в музыке, что побудило меня самостоятельно исследовать структуры в произведениях Моцарта.

Возьмем один атом углерода. Если изменить его микроструктуру, можно получить различные материалы от твердых сверкающих алмазов до графитовой смазки и легких рукояток клюшек для гольфа, сверхпроводников и фуллерена с удивительными свойствами. Разница в микроструктуре атомов углерода обуславливает разницу в свойствах материалов. Я занимался как раз исследованием микроструктур атомов.

Поэтому неудивительно, что я сразу же заметил повторяющуюся структуру музыки Моцарта. Кто не знаком со структурой в музыке, с трудом сможет заметить повторяющуюся структуру, кажется, что она не относится к последовательности мелодии. Я провел тест со своими коллегами по музыке. Большинству из них потребовалось время, чтобы заметить в музыке структуру. Такие проблемы с распознаванием микроструктуры в прошлом затруднили ее исследование, потому что музыкантам она казалась слишком простой и не заслуживающей внимания. Наилучшим примером является медленная часть концерта №21 для фортепиано оркестром, которая не считается повторяющейся, так как потрясающее эмоциональное содержание скрывает повтор.

Повторения — это ключ почти к любому произведению. Тактовый размер задает ритм всему произведению, этот формальный ритм полностью повторяется. В музыке Моцарта чаще всего применяется одно повторение (2 единицы подряд). Бах часто применял повторения, но единой схемы, как у Моцарта, у него не было. В Инвенциях Бах применяет чаще всего 2 повторения (3 единицы подряд, см. Инвенцию №8). Повторения в большем масштабе также важны, как отмечает Сленчиньска, Рут (с. 49): «Играйте все повторы, которые отметил композитор» — совет от опытного музыканта, так как повторения служат определенным целям.

Такие типы повторяющихся структур хорошо известным композиторам, в статьях по анализу и композиции музыки начинает встречаться их подробное обсуждение (Брандт). В литературе появились обсуждения множеств высот и преобразований симметрии, схожие с анализом в настоящей книге (Бернард, Соломон).

В ходе структурного анализа я выявил, что Моцарт сочинял практически все свои произведения еще со времен ранней юности по одной формуле, которая удлиняла его сочинения более чем в десять раз. Если он сочинял новую мелодию на одну минуту, он уже знал, что продолжительность его финальной композиции будет не менее десяти минут. Иногда продолжительность была намного больше, так как основная часть его формулы — умножение на два. Если умножить 10 минут, мы получаем 20, а затем 40 и т. д.!

Первый компонент формулы Моцарта — повторение «мотива». Эти мотивы очень короткие — всего лишь несколько нот, намного короче мелодии — мы всегда думаем о мелодии, а не о мотивах. Мы смотрим на Тадж Махал, но не видим отдельные мраморные блоки. Такие короткие мотивы просто растворяются в мелодии, они слишком короткие, чтобы их распознать. Определенно, композитор специально создал их, чтобы скрыть.

Затем мотив два-три раза изменяется, чтобы составить по мнению аудитории мелодию. Как показано ниже, эти изменения включают в себе различные математические и музыкальные симметрии: обращения, перестановки, изменения гармонии, разумное размещение украшений и пр. Эти повторения собираются в секцию, которая целиком повторяется. Первое повторение дает множитель два, различные изменения дают множители 2–6 (или более), всей секции снова дает множитель два, таким образом, итоговый множитель равен не менее 2 x 2 x 2 = 8. Благодаря такому способу Моцарт мог составлять большие произведения с минимумом тематического материла.

Предопределенная структура позволяла Моцарту записывать произведения с любого места, один голос за раз, так как он знал заранее, куда относится каждая часть. Композитору не было необходимости записывать произведение до того, как будет видна цельная картина. Моцарт мог сочинять несколько фрагментов одновременно, так как они имели одинаковую структуру.

Эта формула преувеличила реальные способности Моцарта: он мог сочинять много музыки, записывать ее в прямом и обратном порядке, сочинять произведение полностью в уме и т. д. Естественным образом возникает вопрос: насколько его «гений» был просто иллюзией? Гениальность Моцарта не оспаривается — музыка говорит за него! Тем не менее, большая часть удивительных способностей гениев была обусловлена простыми приемами, которые можно изучить [(65) Воспитание гениев].

Знание формулы Моцарта позволяет легче разбирать и запоминать его произведения. Первый шаг к пониманию его формулы состоит в умении определять мотив и анализировать его изменения и повторения. Повторения не просты; Моцарт гениально модифицировал и скрывал эти повторения, чтобы они создавали музыку и не выглядели, как повторения.

Еще одна важная сторона его композиций — краткость выражения сложных идей. Рассмотрим в качестве примера известную мелодию аллегро из Маленькой ночной серенады. Это та самая мелодия, которую сыграл Сальери в начале художественного фильма «Амадей», и которую узнал пастор. Это мелодия представляет собой повторение в виде вопроса и ответа. Мужской голос спрашивает: «Эй, ты идешь?». Женский голос отвечает: «Да, иду!». Голос мужчины состоит только из двух нот, отличающихся на кварту и повелительно повторяющихся три раза, вопрос создается за счет добавления двух восходящих нот в конце (похоже, что во всех языках вопросительная интонация характеризуется восходящим тоном). Отвечает женский голос (так как высота звука выше) тоже из двух нот, которые повторяются (как вы уже догадались) три раза! Происходит скачкообразное движение мелодии. Это ответ, так как последние три ноты имеют нисходящий тон. Эффективность конструкции просто поражает. Что еще больше удивляет, так это маскировка повторяющихся пар нот. При прослушивании произведения целиком повторения незаметны, слышится единая мелодия.

Рассмотрим другой пример Соната для фортепиано №11 в ля-мажор, K331 (или K300i, которая оканчивается «Рондо аля Турка»). Базовая единица (мотив) начальной темы — четвертная нота с идущей за ней восьмой нотой. Первое использование этой единицы в такте 1 скрывается добавлением шестнадцатой ноты. Затем снова следует основная единица, завершая такт 1. Таким образом, в первом такте единица повторяется два раза. Затем Моцарт понижает высоту всей конструкции и создает второй такт. Такой же прием Бетховен использовал в начале своей симфонии №5, где «мотив судьбы» повторяется на низком тоне. Третий такт представляет собой двойной повтор базовой единицы. В четвертом такте Моцарт снова скрывает использование единицы из первого такта за счет использования шестнадцатых нот. Такты 5–8 представляют собой такты 1–4 с незначительными изменениями. Если судить по структуре, то первые восемь тактов созданы по образу первого такта. С мелодической точки зрения эти восемь тактов создают две мелодии с похожим началом, но разными окончаниями. Так как все восемь тактов повторяются, то Моцарт практически умножил конструкцию первого такта на 16! Если считать по базовым единицам, то множитель равен 32. Затем Моцарт развивает невообразимые вариации базовой единицы и создает первую часть сонаты, в результате итоговый множитель увеличивается. Он применяет повторения повторений. Растягивая повторения измененных единиц, Моцарт создает протяжную на слух мелодию.

Во второй части вступления композитор вводит новые изменения базовой единицы. В такте 10 впервые добавляется мелодическое украшение, чтобы скрыть повтор, а затем появляется еще одно изменение — базовая единица играется как триоль. После введения триоли она дважды повторяется в такте 11. Такт 12 похож на такт 4 (повтор базовой единицы), но его структура выступает связующим звеном между предшествующими тремя тактами и последующими тремя тактами. Таким образом, такты 9–16 похожи на такты 1–8, но отличаются от последних музыкальным замыслом. Последние два такта (17 и 18) завершают вступление.

На основе проведенного анализа вы сможете самостоятельно разобрать оставшуюся часть сонаты. Вы увидите, что схема повторов одинакова во всем произведении. По мере анализа произведений Моцарта вам следует учитывать комплексность — композитор мог вводить три или четыре повтора, а затем сочетать их с другими изменениями, чтобы скрыть повторы. Моцарт мастерски скрывает повторы, при обычном прослушивании музыки (без анализа ее структуры) повторы и другие конструкции просто незаметны.

Формула Моцарта безусловно повысила его производительность. Возможно, он обнаружил какие-то магические (гипнотические? притягивающие?) свойства множественных повторений либо имел особые причины для распределения определенным образом настроений в темах. Другими словами, если проводить дальнейшую классификацию мелодий по настроениям, которые они вызывают, можно увидеть, что Моцарт всегда распределял настроения одним и тем же образом. Возникает вопрос: если углубляться дальше в анализ, обнаружится ли еще более глубокое использование математического аппарата или таких простых структур, наложенных друг на друга, или под музыкой скрывается нечто большее? Почти наверняка можно выявить такое использование, но пока никому не удалось его обнаружить, даже самим великим композиторам, насколько мы можем судить по их творческому наследству. Нам, простым людям, остается лишь проводить дальнейшие изыскания.

Дальнейший анализ Сонаты №11 ля-мажор (K331) приведен в Скоггин, Нэнси, с. 224.

Моцарт не является изобретателем этой формулы, похожие формулы использовались многими композиторами его времени. Некоторые композиции Сальери созданы по очень похожей формуле, скорее всего, так Сальери пытался подражать Моцарту. Фактически большая часть любой музыки основана на повторениях. В качестве примера далее проводится анализ начала симфонии №5 Бетховена,мы увидим знакомую простенькую мелодию, образованную в точности по формуле Моцарта. Следовательно, Моцарт просто использовал универсальный подход к сочинению музыки.

В простейшем виде формула Моцарта видна в знаменитой колыбельной «В небе звездочка горит» (Twinkle, Twinkle, Little Star), где в основе мотива лежит одна повторяющаяся нота. В этой небольшой мелодии, написанной еще до рождения Моцарта, воплощено большинство основных правил композиции. Так как Моцарт наверняка слышал ее в детстве, то он, возможно, начал сочинять музыку, используя эту мелодию как модель, и, в конечном итоге, стал ее применять для почти всех своих композиций. Такая гипотеза объясняет, почему Моцарт использовал такую формулу с самого начала своей композиторской деятельности. Для большинства детей «Звездочка» — первая мелодия в жизни. Возможно, вначале Моцарт строил свои композиции по этой формуле, а потом обнаружил, что ему не нужны дополнительные средства — так он мог сочинять произведение целиком в уме без необходимости его записывать.

Бетховен и теория групп ( симфония №5, Аппассионата, Вальдштейновская соната)

В музыке Бетховена прочно укоренилось использование математических приемов. Поэтому произведения Бетховена лучше всего подходят для поиска взаимосвязей между математикой и музыкой. Я не утверждаю, что другие композиторы не использовали математический аппарат в своей работе. В основе практически каждой музыкальной композиции лежит математический аппарат, и каждый известный композитор им пользовался. В случае Бетховена использование математики заходит очень далеко, на таком примере можно выявить математические основы с достаточной точностью.

Известно, что Бетховен не изучал высшую математику, хотя использовал понятия из теории групп для создания своей знаменитой симфонии (Бернард, Джонатан У., поиск по ключевым словам «теория групп» или «симметрия в музыке» в Интернете). Более того, он использовал то, что специалисты по кристаллографии называют пространственной группой преобразований симметрии! Положения теории групп используются во многих современных отраслях науки (например, квантовой механике, ядерной физике), которые лежат в основе современной технической революции. При таком уровне абстракции кристалл алмаза и симфония №5 Бетховена представляются одинаковыми! Попробую объяснить.

Бетховен использовал пространственную группу, которая применяется для описания полезных характеристик кристаллов, например кремния и алмаза. Как будто физикам потребовалось добраться от Нью-Йорка до Сан-Франциско, а математики предоставили им карту! Так совершенствовался кремниевый транзистор, что привело к появлению интегральных схем, компьютера и Интернета. Итак, что такое пространственная группа? Почему она оказалась так пригодна для сочинения симфонии №5?

Математики выяснили, что группы состоят из членов и операций над ними. Если выполнить операцию над членом, получится новый член той же группы. Всем знакома группа целых чисел: -1, 0, 1, 2, 3, т.д. Одна из операций этой группы сложение: 2 + 3 = 5. Обратите внимание, применение операции «+» к членам «2» и «3» дает член той же группы «5». Так как операции трансформируют один член в другой, они называются трансформациями. Членом пространственной группы может быть что угодно: атом, лягушка, нота. Атом и лягушка существуют в четырехмерном пространстве-времени. Нота существует в музыкальном измерении, наряду с высотой, скоростью, громкостью. В кристаллографии встречаются следующие операции пространственной группы (в порядке возрастания сложности): трансляция, поворот, зеркальное отражение, инверсия, унитарная операция. Названия операций говорят сами за себя (трансляция — перемещение члена на определенное расстояние в пространстве), за исключением унитарной операции, которая, по сути, не изменяет член. Унитарная операция немного отличается от трансформации равенства, поэтому в учебниках она приводится в конце. Унитарные операции обычно относятся к наиболее специфическому члену группы, назовем его унитарным членом. В приведенной выше группе целых чисел этим членом будет «0» для операции сложения и «1» для умножения (5 + 0 = 5 x 1 = 5). На этом примере видно, что унитарный оператор достаточно сложен.

Рассмотрим, как можно использовать пространственную группу в повседневной жизни. Вы сможете объяснить, почему в зеркальном отражении человека левая рука поменялась с правой, а голова и ноги остались на своем месте? Согласно положениям пространственной группы невозможно повернуть правую руку и получить левую, так как проекция лево-право является операцией отражения, а не вращения. Отметим, что это необычная трансформация: В зеркальном отражении правая рука становится левой, следовательно, родинка на правой руке в отражении будет расположена на левой руке. Для симметричного объекта, например лица, было бы странно увидеть в зеркале родинку на одной стороне, а на фотографии — на другой стороне лица. Хотя правая и левая рука «меняются» местами, зеркало не может осуществить вращение, поэтому голова и ноги остаются на месте. Устройство изогнутых зеркал, в которых могут наблюдаться оптические иллюзии (переворот головы и ног), намного более сложно, они могут выполнять дополнительные операции пространственной группы. Теория групп помогает также в анализе изображений в изогнутом зеркале.

Решение задачи с плоским зеркалом оказалось легким, так как перед нами было зеркало, и мы знали, по какому принципу работают зеркала. Ту же самую задачу можно сформулировать в другом виде, она станет намного сложнее и необходимость использования теории групп станет явной. Если вывернуть наизнанку правую перчатку останется ли она перчаткой для правой руки или станет перчаткой для левой руки? Оставлю эту задачу на самостоятельное решение читателю (подсказка: используйте зеркало).

Посмотрим, как Бетховен применял интуитивное представление о преобразованиях симметрия для создания симфонии №5. Первая часть состоит из короткого мотива судьбы из четырех нот. Первые три ноты одинаковы. Четвертая нота отличается, так называемая «нота неожиданности». Гений Бетховена заключался в том, чтобы сделать ее ударной. Данный мотив можно представить в виде последовательности 5553, где 3 — «нота неожиданности», жирное выделение означает акцент. Это пространственная группа по высоте. Бетховен применил (сознательно) пространство, по меньшей мере, с тремя измерениями: высотой, временем и громкостью. Далее я буду рассматривать только высоту и время.

В начале симфонии №5 Бетховен вводит член группы: 5553. Затем наступает короткая пауза, чтобы слушатель мог узнать этот член, далее Бетховен выполняет операцию трансляции 4442. Каждая нота транспонируется вниз. В результате получается еще один член той же группы. Затем снова пауза, чтобы слушатель смог отличить оператор трансляции. Затем Бетховен как бы произносит: «Интересно? Продолжим!» и показывает потенциал этого оператора на примере ряда трансляций, из которых состоит музыка. Чтобы слушатель наверняка понял конструкцию, Бетховен пока не добавляет другие, более сложные операторы. Вспомним, что трансляция — простейший оператор.

В следующих тактах он последовательно применяет оператор вращения, создавая структуру 3555, а также оператор зеркального отражения, создавая структуру 7555. Примерно в середине первой части Бетховен вводит что-то подобное унитарному члену: 5555. Обратите внимание, что Бетховен просто повторяет группы 4 одинаковых нот, что является унитарной операцией над унитарным членом и эта операция вводится последней! Вспомним, что унитарное преобразование является самым сложным.

В завершающих быстрых частях Бетховен снова использует ту же самую группу. На этот раз он применяет только унитарный член на более высоком уровне. Весь мотив повторяется три раза. Что любопытно, за мотивом идет четвертая последовательность — неожиданная последовательность 7654, которая не является членом. Три раза повторенный унитарный член и неожиданная последовательность составляют супергруппу оригинальной группы. Бетховен обобщил понятие группы! Супергруппа содержит три члена и один элемент, не являющийся членом изначальной группы, что удовлетворяет условиям изначальной группы (три повтора и неожиданность).

Таким образом, начало симфонии №5 Бетховена в переводе на язык математики звучит как первая глава из учебника по теории групп, практически предложение в предложение!

Теория групп — одна из высших форм математики. Бетховен представляет материал в правильном порядке, как и в учебнике. Он даже демонстрирует обобщение понятия, создавая супергруппы исходной группы. Невероятно.

Бетховен часто использовал такую тему из четырех нот во многих своих композициях, например (58) Бетховен, соната Аппассионата, соч. 57, 1-я часть. Будучи настоящим мастером, он осмотрительно избегает пространства высоты в Аппассионате и использует пространство времени (темп) и пространство громкости (такты 234–238). Этот факт поддерживает гипотезу, что Бетховен интуитивно понимал пространства в теории групп и сознательно их разделял. Математически невозможно, чтобы структуры Бетховена так точно соотносились с теорией групп и появились случайно, это практически служит доказательством того, что композитор экспериментировал с понятиями из науки. По-настоящему поражает тот факт, что Бетховен использовал все эти средства (в 1700-х годах) задолго до того, как математики или физики осознали важность структур, до того как теория групп появилась в качестве отдельного направления математики (а произошло это в 1800-х годах)!

Почему такая структура оказалась столь подходящей в этой симфонии? Она обеспечивает единую платформу для музыки композитора. Простота и единообразие позволяет аудитории не отвлекаться, а сконцентрироваться только на музыке. Также она увлекает слушателя. Такие подсознательные повторения (предполагается, что аудитория не знает об использовании конкретного средства) могут производить значительный эмоциональный эффект. Подобно трюку фокусника — он производит гораздо более сильный эффект, если аудитория не знает, что лежит в основе фокуса. Это один из многих способов, с помощью которых Бетховен контролировал аудиторию без ее ведома. Как и Бетховен, мы можем интуитивно ощущать существование какого-либо шаблона, но не можем это выяснить. Моцарт достигал похожего эффекта с помощью повторений. Сможете ли вы увидеть схожесть повторений в симфонии №5 Бетховена с произведениями Моцарта?

Возможно, наиболее важным фактором является понятие пространства; находясь в одном пространстве и проводя в нем трансформации, мозгу легче следить за ними, также как начало в одной тональности и проведение аккордовых последовательностей через квинтовый круг, облегчает мозгу отслеживание тоник [(68) Теория, сольфеджио ].

Знание этих схем на основе теории групп помогает при исполнении музыки Бетховена, так как мы понимаем, какой конкретно инструмент использовал композитор для создания своих произведений. Рассмотрим другой пример — третью часть Вальдштейновской сонаты, которая целиком основана на мотиве из трех нот 155 (первые CGG в начале). Первоначальная тема повторяется на протяжении всей части и по мере ее развития становится настойчивой. К тому времени, аудитория настолько увлечена ее, что даже не замечает, как эта тема управляет всей музыкой.

Музыка является разновидностью математики. Великие композиторы, как мы увидели на примере Бетховена, исследовали и использовали эту взаимосвязь. Большинство основных понятий теории музыки можно выразить математически: гармония — это ряд соотношений, гармония дает развитие хроматической гамме, которая является логарифмическим уравнением [(68) Теория сольфеджио, (76) Хроматическая гамма, (77) Квинтовый круг, темперация]. Большинство гамм в музыке являются подмножествами хроматической гаммы, а аккордовые последовательности — это простейшие отношения между ними. Музыка и математика неразрывно связаны, особенно в человеческом мозге и его автоматических функциях. Знание этой взаимосвязи может быть полезным, что видно на примере каждого великого композитора. Клавиатура фортепиано является точным аналогом логарифмической линейки [(68) Теория, сольфеджио], [(76) Хроматическая гамма]. По мере развития математического понимания музыки и использования математики исполнителями математика будет все больше находить применение в музыке. Искусство — кратчайший путь к использованию человеческого мозга для получения результатов, не достижимых другим способом. Научный подход к музыке рассматривает простые ее стороны, которые можно исследовать аналитически, что особенно важно для искоренения неправильных представлений: наука поддерживает искусство. Ошибочно утверждать, что музыка не является математикой. Исполнитель должен свободно исследовать все в искусстве, а исключение математики не только ограничивает исполнителя, но и прямо противоречит работам великих композиторов.