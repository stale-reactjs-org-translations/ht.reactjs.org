# Gis Style Inivèsèl

Dokiman sa a dekri règ ki ta dwe aplike pou ** tout **  tradiksyon pou sit [ht.reactjs.org](https://ht.reactjs.org).

## IDs Tit Yo

Tout tit gen idantifikasyon klè tankou egzanp anba a:

```md
## Eseye React {#try-react}
```

** Pa ** tradui ID sa yo! Nou itilize yo pou navigasyon. Lyen yo ka kraze si dokiman an se yon lyen ekstèn tankou:

```md
Checke seksyon [An n Kòmanse](/getting-started#try-react) pou plis enfoòmasyon.
```

✅ Fè:

```md
## Eseye React {#try-react}
```

❌ Pa Fè:

```md
## Eseye React {#eseye-react}
```
Eganp sa ta kraze lyen pou seksyon Eseye React la.


## Tèks nan Blòk Kòd

Kenbe tèks nan blòk kòd san tradiksyon eksepte pou kòmantè. Ou ka chwazi tradui tèks nan strings, men ou dwe fè atansyon pou pa tradui strings ki refere a kòd la!

Egzanp:
```js
// Example
const element = <h1>Hello, world</h1>;
ReactDOM.render(element, document.getElementById('root'));
```

✅ Fè:

```js
// Egzanp
const element = <h1>Hello, world</h1>;
ReactDOM.render(element, document.getElementById('root'));
```

✅ Pèmen:

```js
// Egzanp
const element = <h1>Bonjou, mond</h1>;
ReactDOM.render(element, document.getElementById('root'));
```

❌ Pa Fè:

```js
// Egzanp
const element = <h1>Bonjou, mond</h1>;
// "root" refere a yon eleman ki gen ID "root".
// Pa Tradui
ReactDOM.render(element, document.getElementById('root'));
```

❌ Pa Fè Sa Menm:

```js
// Egzanp
const eleman = <h1>Bonjou, mond</h1>;
ReactDOM.renderizar(eleman, documento.pranElemanPaId('rasin'));
```

Pou lyen ki pa gen okenn tradisyon (StackOverflow, videyo sou YouTube, elatriye), sevi ak lyen orijinal la.

## Tradiksyon Komen

Pawòl ak tèm sijesyon:

| Pawòl/Tèm orijinal | Sijesyon |
| ------------------ | ---------- |
| assertion |  |
| browser |  |
| bubbling |  |
| bug |  |
| class component |  |
| class |  |
| client |  |
| client-side |  |
| container |  |
| context |  |
| controlled component |  |
| debugging | |
| DOM node | |
| event handler | (event handler) |
| function component |  |
| handler |  |
| helper function |  |
| high-order components |  |
| key |  |
| library |  |
| lowercase |  |
| package |  |
| React element |  |
| React fragment |  |
| render | |
| server |  |
| server-side |  |
| siblings |  |
| stateful component |  |
| stateful logic |  |
| to assert |  |
| to wrap |  |
| uncontrolled component |  |
| uppercase |  |

## Kontni ki pa ta dwe tradui

* array
* arrow function
* bind
* bundle
* bundler
* callback
* camelCase
* DOM
* event listener
* framework
* hook
* log
* mock
* portal
* props
* ref
* release
* script
* single-page-apps
* state
* string
* string literal
* subscribe
* subscription
* template literal
* timestamps
* UI
* watcher
* widgets
* wrapper