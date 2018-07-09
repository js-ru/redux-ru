# <a href='http://redux.js.org'><img src='https://camo.githubusercontent.com/f28b5bc7822f1b7bb28a96d8d09e7d79169248fc/687474703a2f2f692e696d6775722e636f6d2f4a65567164514d2e706e67' height='60' alt='Redux Logo' aria-label='redux.js.org' /></a>

Redux — предсказуемый контейнер состояния для приложений на JavaScript.
(не путайте с WordPress-фреймворком [Redux Framework](https://reduxframework.com/).)

Он помогает вам писать приложения, которые ведут себя последовательно в различных окружениях (клиент, сервер и нативные приложения), а также легко тестируются. Кроме того, он предоставляет отличные возможности для разработчиков, например, [редактирование кода в режиме реального времени в сочетании c отладчиком c возможностью отладки в обратном направлении (time traveling debugger)](https://github.com/reduxjs/redux-devtools).

Можно использовать Redux вместе с [React](https://reactjs.org) или любой другой библиотекой для работы с представлениями.
Он крошечный (2Кб, включая зависимости).

[![build status](https://img.shields.io/travis/reduxjs/redux/master.svg?style=flat-square)](https://travis-ci.org/reduxjs/redux)
[![npm version](https://img.shields.io/npm/v/redux.svg?style=flat-square)](https://www.npmjs.com/package/redux)
[![npm downloads](https://img.shields.io/npm/dm/redux.svg?style=flat-square)](https://www.npmjs.com/package/redux)
[![redux channel on discord](https://img.shields.io/badge/discord-%23redux%20%40%20reactiflux-61dafb.svg?style=flat-square)](https://discord.gg/0ZcbPKXt5bZ6au5t)
[![Changelog #187](https://img.shields.io/badge/changelog-%23187-lightgrey.svg?style=flat-square)](https://changelog.com/187)


## Изучите Redux

У нас множество доступных ресурсов, которые помогут вам изучить Redux, независимо от того, какой ваш уровень знаний или стиль обучения.

### Только основы

Если вы новичок в Redux и хотите понять основные понятия, посмотрите

- **[Начальное руководство в документации Redux](https://ru.redux.js.org/basics)**
- **Бесплатная серия видеоуроков ["Getting Started with Redux"](https://egghead.io/series/getting-started-with-redux)** на Egghead.io от создателя Redux Дэна Абрамова
- **[Слайдшоу "Redux Fundamentals"**](http://blog.isquaredsoftware.com/2018/03/presentation-reactathon-redux-fundamentals/) от со-разработчика Redux Марка Эриксона, а также **[рекомендуемый список для изучения Redux](http://blog.isquaredsoftware.com/2017/12/blogged-answers-learn-redux/)**
- Если вы лучше учитесь, просматривая код и играя с ним, ознакомьтесь с нашим списком **[примеров приложений на Redux](https://redux.js.org/introduction/examples)**,доступных в качестве отдельных проектов в репозитории Redux, а также в качестве интерактивных онлайн-примеров на CodeSandbox.
- Раздел **[Redux Tutorials](https://github.com/markerikson/react-redux-links/blob/master/redux-tutorials.md)** в **[списке ссылок React/Redux](https://github.com/markerikson/react-redux-links)**. Вот список рекомендуемых нами учебных материалов:
    - Посты Дэйва Седдиа (Dave Ceddia) [What Does Redux Do? (and when should you use it?)](https://daveceddia.com/what-does-redux-do/) и [How Redux Works: A Counter-Example](https://daveceddia.com/how-does-redux-work/) — отличное введение в основы Redux и как использовать его с React, как и пост [React and Redux: An Introduction](http://jakesidsmith.com/blog/post/2017-11-18-redux-and-react-an-introduction/).
    - Пост Валентино Гальярди (Valentino Gagliardi) [React Redux Tutorial for Beginners: Learning Redux in 2018](https://www.valentinog.com/blog/react-redux-tutorial-beginners/) — отличное расширенное введение во многие аспекты использования Redux.
    - Статья на CSS Tricks [Leveling Up with React: Redux](https://css-tricks.com/learning-react-redux/) также хорошо освещает основы Redux.
    - Интерактиное руководство [DevGuides: Introduction to Redux](http://devguides.io/redux/) раскрывает различные аспекты Redux, включая действия, редюсеры, мидлвары, использование с React.


### Промежуточные концепции

Когда вы изучите основы работы с действиями, редюсерами и хранилищем, у вас могут возникнуть вопросы по таким темам, как работа с асинхронной логикой и AJAX-запросами, подключение UI-фреймворка, такого как React, к вашему хранилищу Redux, и настройка приложения для использования с Redux:

- **[Раздел документации "Продвинутое использование"](https://redux.js.org/advanced)** озватывает работу с асинхронной логикой, мидлваром, маршрутизацию.
- The Redux docs **["Learning Resources"](https://redux.js.org/introduction/learning-resources)** page points to recommended articles on a variety of Redux-related topics.
- Sophie DeBenedetto's 8-part **[Building a Simple CRUD App with React + Redux](http://www.thegreatcodeadventure.com/building-a-simple-crud-app-with-react-redux-part-1/)** series shows how to put together a basic CRUD app from scratch.


### Использование в реальном мире

Переход от приложения TodoMVC, к реальному production приложению, может стать большим скачком, но у нас есть много ресурсов, которые помогут:

- **[Бесплатная видеосерия "Building React Applications with Idiomatic Redux"](https://egghead.io/courses/building-react-applications-with-idiomatic-redux)** от создателя Redux Дэна Абрамова, основывается на его первой серии видеоуроков и охватывает такие темы, как мидлвары, маршрутизация и постоянное хранение (persistence).
- **[Redux FAQ](docs/FAQ.md)** даёт ответы на многие распространённые вопросы, связанные с использованием Redux, а также **[секция документации "Рецепты"](https://redux.js.org/recipes)**, которая содержит информацию по обработке полученных данных, тестированию, структурированию логики редюсеров и уменьшении шаблонного кода (boilerplate).
- **[Серия обучающих материалов "Practical Redux"](http://blog.isquaredsoftware.com/series/practical-redux/)** от одного из разработчиков Redux Марка Эриксона, демонстрирует реальные практические техники среднего и продвинутого уровня для работы с React и Redux (также доступен в виде **[интерактивного курса на Educative.io](https://www.educative.io/collection/5687753853370368/5707702298738688)**)


-**[Список ссылок React/Redux](https://github.com/markerikson/react-redux-links)** содержит упорядоченный по категориям список статей по работе с [редюсерами и селекторами](https://github.com/markerikson/react-redux-links/blob/master/redux-reducers-selectors.md), [управление побочными эффектами](https://github.com/markerikson/react-redux-links/blob/master/redux-side-effects.md), [архитектурой и передовым практикам Redux](https://github.com/markerikson/react-redux-links/blob/master/redux-architecture.md) и т.д.
- Наше сообщество создало тысячи библиотек, дополнений и инструментов, связанных с Redux. **[Страница документации "Экосистема"](https://redux.js.org/introduction/ecosystem)** перечисляет наши рекомендации, а также имеется полный список, доступный в **[репозитории каталога дополнений Redux](https://github.com/markerikson/redux-ecosystem-links)**.
- Если вы хотите учиться на реальной кодовой базе приложений, каталог дополнений также содержит список **[специально написанных реальных приложений](https://github.com/markerikson/redux-ecosystem-links/blob/master/apps-and-examples.md)**.

Наконец, Марк Эриксон проводит серию **[воркшопов по Redux при помощи Workshop.me](#redux-workshops)**. Посмотрите [расписание воркшопов](https://workshop.me/?a=mark) для получения информации о предстоящих дат и мест проведения.


### Помощь и обсуждения

**[Канал #redux](https://discord.gg/0ZcbPKXt5bZ6au5t)** **[сообщества Reactiflux Discord](http://www.reactiflux.com)** — это наш официальный ресурс для всех вопросов связанных с изучением и использованием Redux. Reactiflux — отличное место для того, чтобы общаться, задавать вопросы и учиться — присоединяйтесь к нам!




## Перед тем как начать

Redux is a valuable tool for organizing your state, but you should also consider whether it's appropriate for your situation.  Don't use Redux just because someone said you should - take some time to understand the potential benefits and tradeoffs of using it.

Here are some suggestions on when it makes sense to use Redux:
* You have reasonable amounts of data changing over time
* You need a single source of truth for your state
* You find that keeping all your state in a top-level component is no longer sufficient

Yes, these guidelines are subjective and vague, but this is for good reason. The point at which you should integrate Redux into your application is different for every user and different for every application.

>**For more thoughts on how Redux is meant to be used, see:**<br>
>- **[You Might Not Need Redux](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367)**<br>
>- **[The Tao of Redux, Part 1 - Implementation and Intent](http://blog.isquaredsoftware.com/2017/05/idiomatic-redux-tao-of-redux-part-1/)**<br>
>- **[The Tao of Redux, Part 2 - Practice and Philosophy](http://blog.isquaredsoftware.com/2017/05/idiomatic-redux-tao-of-redux-part-2/)**
>- **[Redux FAQ](https://redux.js.org/faq)**

Redux — это ценный инструмент для управлением вашим состоянием, но вам нужно учесть, подходит ли он для вашей ситуации. Не используйте Redux только потому, что кто-то сказал, что вам нужно — потратьте какое-то время, чтобы выяснить потенциальные выгоды и проблемы с его использованием.

Следующие несколько советов относительно того, когда имеет смысл использовать Redux:
* У вас есть обоснованные объёмы данных, меняющихся со временем
* Вам нужен единственный источник информации для вашего состояния
* Вы понимаете, что сохранение всего вашего состояния в компоненте верхнего уровня уже недостаточно

Да, эти рекомендации являются субъективными и расплывчатыми, но не без веских причин. Момент, в которой вам потребуется интегрировать Redux в ваше приложение, отличается у каждого пользователя и неодинаковый для каждого приложения.

>**Дополнительные сведения о том, как использовать Redux, см:**<br>
>- **[You Might Not Need Redux](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367)**<br>
>- **[The Tao of Redux, Part 1 - Implementation and Intent](http://blog.isquaredsoftware.com/2017/05/idiomatic-redux-tao-of-redux-part-1/)**<br>
>- **[The Tao of Redux, Part 2 - Practice and Philosophy](http://blog.isquaredsoftware.com/2017/05/idiomatic-redux-tao-of-redux-part-2/)**
>- **[Redux FAQ](https://redux.js.org/faq)**

## Восприятие со стороны разработчика

Дэн Абрамов (автор Redux) написал Redux пока работал над своим докладом на React Europe [“Hot Reloading with Time Travel”](https://www.youtube.com/watch?v=xsSnOQynTHs). Его целью было создание библиотеки управления состоянием с минимальным API, но полностью предсказуемым поведением, так чтобы можно было реализовать логирование, горячую перезагрузку, отладку в обратном направлении, универсальные приложения, запись и воспроизведение, без какого-либо участия от разработчика.

## Влияния

Redux развивает идеи [Flux](http://facebook.github.io/flux/), но избегает его сложности, воспользовавшись примерами из [Elm](https://github.com/evancz/elm-architecture-tutorial/).
Вне зависимости от того, использовали ли вы Flux или Elm, Redux занимает всего несколько минут, чтобы начать с ним работу.

## Установка

Для установки стабильной версии:

```
npm install --save redux
```

Предполагается, что вы используете [npm](https://www.npmjs.com/) в качестве менеджера пакетов.

Если нет, то вы можете [получить доступ к этим файлам на unpkg](https://unpkg.com/redux/), загрузить их или настроить ваш пакетный менеджер.

Чаще всего люди используют Redux, как набор модулей [CommonJS](https://webpack.github.io/docs/commonjs.html). Эти модули — это то, что вы получаете, когда импортируете `redux` в [Webpack](https://webpack.js.org/), [Browserify](https://browserify.org/) или Node окружение. Если вам нравится испытывать судьбу и использовать [Rollup](https://rollupjs.org), мы также поддерживаем это.

Если вы не используете сборщики модулей, это тоже прекрасно. npm-пакет `redux` включает 	предварительно скомпилированный сборки [UMD](https://github.com/umdjs/umd) для разработки и продакшена в [каталоге `dist`](https://unpkg.com/redux/dist/). Они могут быть использованы напрямую без сборщика и, таким образом, совместимы со многими популярными загрузчиками JavaScript-модулей и окружениями. Например, вы можете подключить UMD-сборку на страницу при помощи [тега `<script>`](https://unpkg.com/redux/dist/redux.js) или [установить при помощи Bower](https://github.com/reactjs/redux/pull/1181#issuecomment-167361975). Сборки UMD делают Redux доступным через глобальную переменную `window.Redux`.

Исходный код Redux написан на ES2015, но мы предварительно скомпилировали сборки CommonJS и UMD в ES5, поэтому они работают в [любом современном браузере](http://caniuse.com/#feat=es5). Вам не нужно использовать Babel или сборщик модулей чтобы [начать пользоваться Redux](https://github.com/reactjs/redux/blob/master/examples/counter-vanilla/index.html).

### Дополнительные пакеты

Скорее всего, вам также понадобится [связка (bindings) с React](https://github.com/reactjs/react-redux) и [инструменты разработчика](https://github.com/gaearon/redux-devtools).

```
npm install --save react-redux
npm install --save-dev redux-devtools
```

Обратите внимание, что в отличие от самого Redux, многие пакеты в экосистеме Redux не предоставляют сборки UMD, поэтому мы рекомендуем использовать сборщики модулей CommonJS, такие как [Webpack](https://webpack.js.org/) и [Browserify](http://browserify.org/) для наиболее комфортной разработки.

## Основные принципы

Всё состояние вашего приложения хранится в дереве объектов внутри одного *хранилища (store)*.
Единственный способ изменить дерево состояния — вызвать *действие (action)*, объект описывающий то, что произошло.
Чтобы указать, как действия преобразуют дерево состояния, вы пишете чистые *редюсеры (reducers)*.

Вот так!

```js
import { createStore } from 'redux'

/**
 * Это редюсер — чистая функция, определённая как (state, action) => state.
 * Он описывает то, как действие преобразовывает состояние в следующее состояние
 *
 * Формат состояния зависит от вас: это может быть примитивом,
 * массивом, объектом или даже структурой данных Immutable.js.
 * Важно только одно — вы не должны изменять объект состояния
 * напрямую, а возвращать новый объект, если состояние изменилось.
 *
 * В этом примере мы используем выражение switch и строки, но вы можете
 * использовать хелпер, который следует другому соглашению
 * (например, function maps), если это имеет смысл для вашего
 * проекта.
 */
function counter(state = 0, action) {
  switch (action.type) {
  case 'INCREMENT':
    return state + 1
  case 'DECREMENT':
    return state - 1
  default:
    return state
  }
}

// Создаём хранилище Redux, которое хранит состояние вашего приложения.
// Его API — { subscribe, dispatch, getState }.
let store = createStore(counter)

// Вы можете использовать subscribe() для обновления UI в ответ на изменения состояния.
// Обычно вы должны использовать библиотеку привязки (например, React Redux), а не использовать subscribe() напрямую.
// Однако также может быть полезно сохранить текущее состояние в localStorage.
store.subscribe(() =>
  console.log(store.getState())
)

// Единственный способ изменить внутреннее состояние — вызвать действие
// Действия могут быть сериализированы, залогированы или сохранены, а затем воспроизведены.
store.dispatch({ type: 'INCREMENT' })
// 1
store.dispatch({ type: 'INCREMENT' })
// 2
store.dispatch({ type: 'DECREMENT' })
// 1
```

Вместо того, что бы изменять состояние напрямую, вы определяете изменения, которые вы хотите произвести, с помощью простых объектов, называемых *действия*. Затем вы пишете специальную функцию, называемую *редюсер*, чтобы решить, каким образом каждое действие преобразует всё состояние приложения.

Если вы пришли из Flux, есть одно важное различие, которое вы должны понимать. У Redux нет Диспетчера (Dispatcher) или поддержки нескольких хранилищ. Вместо этого есть только одно хранилище с одной корневой функцией-редюсером. По мере расширения вашего приложения, вместо добавления хранилищ, вы разделяете корневой редюсер на более мелкие редюсеры, которые независимо друг от друга обслуживают разные части дерева состояния. Это аналогично тому, что в React-приложении есть только один корневой компонент, состоящий из множества мелких компонентов.

Эта архитектура может показаться излишней для счётчика приложения, но красота этого шаблона заключается в том, насколько хорошо он масштабируется для больших и сложных приложений. Она также предоставляет очень мощные инструменты для разработчиков, позволяющих проследить каждое изменение и какое действие вызвало её. Вы можете записывать пользовательские сессии и воспроизводить их просто проигрывая каждое действие.

## Изучайте Redux вместе с его создателями

### Видеоуроки Redux от Дэна Абрамова

#### Начало работы с Redux
**[Getting Started with Redux](https://egghead.io/series/getting-started-with-redux)** — это видеокурс, состоящий из 30 роликов созданных Дэном Абрамовым, автором Redux. Он предназначен для дополнения части документации «Основы», привнося дополнительные сведения о неизменности (immutability), тестировании, передовых практиках Redux, а также об использовании Redux с React. **Данный курс бесплатный и всегда будет таким.**

>[“Great course on egghead.io by @dan_abramov - instead of just showing you how to use #redux, it also shows how and why redux was built!”](https://twitter.com/sandrinodm/status/670548531422326785)
>Sandrino Di Mattia

>[“Plowing through @dan_abramov 'Getting Started with Redux' - its amazing how much simpler concepts get with video.”](https://twitter.com/chrisdhanaraj/status/670328025553219584)
>Chris Dhanaraj

>[“This video series on Redux by @dan_abramov on @eggheadio is spectacular!”](https://twitter.com/eddiezane/status/670333133242408960)
>Eddie Zaneski

>[“Come for the name hype. Stay for the rock solid fundamentals. (Thanks, and great job @dan_abramov and @eggheadio!)”](https://twitter.com/danott/status/669909126554607617)
>Dan

>[“This series of videos on Redux by @dan_abramov is repeatedly blowing my mind - gunna do some serious refactoring”](https://twitter.com/gelatindesign/status/669658358643892224)
>Laurence Roberts

И так, чего же вы ждёте?

#### [Посмотрите 30 бесплатных уроков "Getting Started with Redux"!](https://egghead.io/series/getting-started-with-redux)

> Note: Если вам понравился мой курс, подумайте о поддержке Egghead путём [покупки подписки](https://egghead.io/pricing). Подписчики имеют доступ к исходному коду каждого примера в видеоуроках, а также к массе продвинутых уроков по другим темам, включая углублённое изучение JavaScript, React, Angular и т.д. Многие [преподаватели Egghead](https://egghead.io/instructors) также являются авторами библиотек с открытым исходным кодом, поэтому покупка подписки — это хороший способ поблагодарить их за работу, которую они сделали.


#### Создание React-приложений с помощью Redux

**[Building React Applications with Idiomatic Redux](https://egghead.io/courses/building-react-applications-with-idiomatic-redux)** — это вторая бесплатная серия видеоуроков от Дэна Абрамова. Он продолжает темы, начатые в первой серии и охватывает практические технологии, используемые в продакшене, необходимые для создания ваших приложений React и Redux: усовершенствованное управление состоянием, мидлвары, интеграция React Router и другие распространённые проблемы, с которыми вы, вероятно, столкнетесь при создании приложений для своих клиентов и заказчиков. Как и первая серия, **этот курс всегда будет бесплатным**.

#### [Посмотрите бесплатный видео курс "Idiomatic Redux"](https://egghead.io/courses/building-react-applications-with-idiomatic-redux)


### Практический курс Redux

**[Практический Redux](https://www.educative.io/collection/5687753853370368/5707702298738688/)** — платный интерактивный курс одного из главных разработчиков Redux [Марка Эриксона](https://twitter.com/acemarke ). Курс предназначен для того, чтобы показать, как применять базовые концепции Redux к созданию чего-то большего, чем приложение TodoMVC. Он включает в себя такие реальные темы, как:


- Добавление Redux к новому проекту Create-React-App и настройка горячей замены модулей (Hot Module Replacement) для более быстрой разработки
- Управление пользовательским интерфейсом с помощью Redux
- Использование библиотеки Redux-ORM для управления связанными данными в хранилище Redux
- Создание главного/детального представления для отображения и редактирования данных
- Написание пользовательской усовершенствованной логики редюсера Redux для решения конкретных проблем
- Оптимизация производительности подключенных к Redux полей формы

И многое другое!

Курс основывается на оригинальной бесплатной учебной серии **[«Практический Redux»](http://blog.isquaredsoftware.com/series/practical-redux/)**, но с обновлённым и улучшенным контентом.


### Воркшопы Redux

Один из разработчиков Redux [Mark Erikson](https://twitter.com/acemarke) совместно с [Workshop.me](https://workshop.me/) проводит серию воркшопов по Redux

Первый семинар [**Redux Fundamentals** состоялся в Нью-Йорке 19-20 апреля](https://workshop.me/2018-04-react-redux?a=mark) и познакомил со следующими темами:

- История и цель Redux
- Редюсеры, действия и работа с хранилищем Redux
- Использование Redux с React
- Использование и написание мидлвара для Redux
- Работа с вызовами AJAX и другими побочными эффектами
- Тестирование приложений Redux
- Реальные приложения на Redux и их разработка

Билеты по-прежнему доступны и их [можно приобрести через Workshop.me](https://workshop.me/2018-04-react-redux?a=mark)


## Documentation

* [Введение](http://redux.js.org/introduction/index.html)
* [Основы](http://redux.js.org/basics/index.html)
* [Продвинутое использовани](http://redux.js.org/advanced/index.html)
* [Рецепты](http://redux.js.org/recipes/index.html)
* [FAQ](http://redux.js.org/FAQ.html)
* [Troubleshooting](http://redux.js.org/Troubleshooting.html)
* [Глоссарий](http://redux.js.org/Glossary.html)
* [Справочник API](http://redux.js.org/api/index.html)

Обратите внимание на [paulkogel/redux-offline-docs](https://github.com/paulkogel/redux-offline-docs) для экпорта в PDF, ePub и MOBI для офлайн-чтения, там вы найдете инструкции, как это можно сделать.

Для документации в режиме офлайн смотрите [devdocs](http://devdocs.io/redux/)

## Примеры

Почти все примеры имеют соответствующую песочницу CodeSandbox. Это интерактивная версия кода, с которой вы можете играть онлайн.

* [**Counter Vanilla**](https://redux.js.org/introduction/examples#counter-vanilla): [Source](https://github.com/reduxjs/redux/tree/master/examples/counter-vanilla)
* [**Counter**](https://redux.js.org/introduction/examples#counter): [Source](https://github.com/reduxjs/redux/tree/master/examples/counter) | [Sandbox](https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/counter)
* [**Todos**](https://redux.js.org/introduction/examples#todos): [Source](https://github.com/reduxjs/redux/tree/master/examples/todos) | [Sandbox](https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/todos)
* [**Todos with Undo**](https://redux.js.org/introduction/examples#todos-with-undo): [Source](https://github.com/reduxjs/redux/tree/master/examples/todos-with-undo) | [Sandbox](https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/todos-with-undo)
* [**TodoMVC**](https://redux.js.org/introduction/examples#todomvc): [Source](https://github.com/reduxjs/redux/tree/master/examples/todomvc) | [Sandbox](https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/todomvc)
* [**Shopping Cart**](https://redux.js.org/introduction/examples#shopping-cart): [Source](https://github.com/reduxjs/redux/tree/master/examples/shopping-cart) | [Sandbox](https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/shopping-cart)
* [**Tree View**](https://redux.js.org/introduction/examples#tree-view): [Source](https://github.com/reduxjs/redux/tree/master/examples/tree-view) | [Sandbox](https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/tree-view)
* [**Async**](https://redux.js.org/introduction/examples#async): [Source](https://github.com/reduxjs/redux/tree/master/examples/async) | [Sandbox](https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/async)
* [**Universal**](https://redux.js.org/introduction/examples#universal): [Source](https://github.com/reduxjs/redux/tree/master/examples/universal)
* [**Real World**](https://redux.js.org/introduction/examples#real-world): [Source](https://github.com/reduxjs/redux/tree/master/examples/real-world) | [Sandbox](https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/real-world)

Если вы новичок в экосистеме NPM и имеете проблемы с получением и запуском проекта или не уверены, куда вставить шаблон, попробуйте [simplest-redux-example](https://github.com/jackielii/simplest-redux-example) который использует Redux вместе с React и Browserify.


## Отзывы

>[“Love what you’re doing with Redux”](https://twitter.com/jingc/status/616608251463909376)
>Jing Chen, автор Flux

>[“I asked for comments on Redux in FB's internal JS discussion group, and it was universally praised. Really awesome work.”](https://twitter.com/fisherwebdev/status/616286955693682688)
>Bill Fisher, автор документации Flux

>[“It's cool that you are inventing a better Flux by not doing Flux at all.”](https://twitter.com/andrestaltz/status/616271392930201604)
>André Staltz, creator of Cycle


## Благодарности

* [The Elm Architecture](https://github.com/evancz/elm-architecture-tutorial) за великолепное введение в моделирование обновления состояния посредством редюсеров;
* [Turning the database inside-out](http://www.confluent.io/blog/turning-the-database-inside-out-with-apache-samza/) за взрыв моего сознания;
* [Developing ClojureScript with Figwheel](https://www.youtube.com/watch?v=j-kj2qwJa_E) за убеждение меня в том, что переоценка должна "просто работать";
* [Webpack](https://github.com/webpack/docs/wiki/hot-module-replacement-with-webpack) за Hot Module Replacement;
* [Flummox](https://github.com/acdlite/flummox) за обучение меня подходу Flux без шаблонного кода (boilerplate) или синглтонов;
* [disto](https://github.com/threepointone/disto) за доказательство концепции хранилищ "hot reloadable";
* [NuclearJS](https://github.com/optimizely/nuclear-js) за доказательство того, что такая архитектура может быть производительной;
* [Om](https://github.com/omcljs/om) за популяризацию идеи одного атома состояния;
* [Cycle](https://github.com/cyclejs/cycle-core) за демонстрацию того, как часто функция является лучшим инструментом;
* [React](https://github.com/facebook/react) за прагматические инновации.


Особая благодарность [Jamie Paton](http://jdpaton.github.io) за передачу прав на название `redux` для NPM-пакета.

## Логотип

Вы можете найти официальное логотип [на GitHub](https://github.com/reactjs/redux/tree/master/logo).

## История изменений

Это проект придерживается принципов [семантического версионирования](http://semver.org/).
Каждый релиз, вместе с инструкциями миграции, документированы на странице [релизов](https://github.com/reactjs/redux/releases) GitHub.

## Меценаты

Разработка Redux была [профинансирована сообществом](https://www.patreon.com/reactdx).
Познакомьтесь с некоторыми из выдающихся компаний, которые сделали это возможным:

* [Webflow](https://github.com/webflow)
* [Ximedes](https://www.ximedes.com/)

[См. полный список меценатов Redux.](PATRONS.md), а также постоянно растущий список [людей и компаний, которые используют Redux](https://github.com/reactjs/redux/issues/310).

## Лицензия

MIT
