# Ivan Ivanov

## [Contact Info](#contact-info)
* Discord: IvanIvanov79999999999
* E-mail: IvanIvanov79999999999@mail.com
* Tel: +79999999999

## [Summary](#summary)
I am studying Front-End Development in RSSchool!

## [Code examples](#code-examples)
```
const selectionSort = arr => {
  const a = [...arr];
  for (let i = 0; i < a.length; i++) {
    const min = a
      .slice(i + 1)
      .reduce((acc, val, j) => (val < a[acc] ? j + i + 1 : acc), i);
    if (min !== i) [a[i], a[min]] = [a[min], a[i]];
  }
  return a;
};
```

## [Education and courses](#education-and-courses)
1. https://ru.code-basics.com/languages/html
2. https://ru.code-basics.com/languages/css

## [Languages](#languages)
* Russian
* English - level A2
