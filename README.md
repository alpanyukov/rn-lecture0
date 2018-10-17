# Уроки по React Native

## Лекция 0. Введение

### Что такое React Native

React Native — это фреймворк для разработки кроссплатформенных приложений для iOS и Android c использованием React.

- появился в начале 2015 года
- построен на базе React
- не использует WebView и HTML - технологии
- нативные компоненты имеют биндинги в JS и обернуты в React

### Как это работает

В каждом приложении React Native есть два потока.

Один из них - основной поток, который также работает в любом стандартном нативном приложении. Он обрабатывает отображение элементов пользовательского интерфейса, жесты пользователя и т.д.

В другом потоке выполняется JS код.

Взаимодействие между потоками происходит не напрямую, а через мост.
Коммуникации асинхронны, данные сериализованы и отправляются пачками.

### Ссылки

#### Документации

- [Expo SDK](https://docs.expo.io/versions/latest/)
- [React Native](https://facebook.github.io/react-native/docs/getting-started)

#### Почитать / посмотреть

- [React Native Under The Hood](https://www.youtube.com/watch?v=hDviGU-57lU) ([слайды](https://speakerdeck.com/frantic/react-native-under-the-hood))

#### Инструменты / библиотеки

- [Курируемый список материалов](https://github.com/jondot/awesome-react-native)
- [Список различных библиотек](http://native.directory/recommended)
