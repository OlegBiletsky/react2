# react-input-math.random
>
1. Створити класовий компонент в якому з допомогою стану компоненту всі дані з інпута в який юзер буде вводити тест - будуть в режимі реального часу відображатись в функціональному компоненті в h1 тегу. 
>
2. Створити 3 компонента крізь які будемо передавати функцію з рандомним числом та повертати в головний компонент  де отримане значення з компонента  С будемо множити на 1000 та записувати в стейт . (А -> B -> C > B > A)
>
>
## Def
>
в Арр імпортиться компонент А.
>
в компоненті А (класова компонента) створюю дві ф-ї:
 - одна генерує рандомне число
 - друга отримує значення першої (фактично викликає її) і множить отримане значення на 1000 і записує в стейт. 
 (я ще додав що вона записує в стейт також і то рандомне число). Логіка цих функцій прописана у компоненті А.
>
Потім передаю другу функцію в компонент В (функціональний), а звідти в компонент С
(теж функціональний)
>
В компоненті С створив кнопку, на onClick викликається з пропсів друга функція, яка викликає першу функцію (генерує число), яка множить на 1000 і записує все у стейт.
>
