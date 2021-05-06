# Static API

## Portugal

### Zip Codes

Example to lookup `1000-100` zip code:  
[http://staticapi.org/api/pt-zipcode/1000-100.json](http://staticapi.org/api/pt-zipcode/1000-100.json)

```js
fetch("https://staticapi.org/api/pt-zipcode/1000-100.json")
  .then(response => response.json())
  .then(json => console.log(json));
```
```js
{
  DD: "11",
  CC: "06",
  LLLL: "21696",
  LOCALIDADE: "Lisboa",
  ART_COD: "11300611",
  ART_TIPO: "Rua",
  PRI_PREP: "",
  ART_TITULO: "",
  SEG_PREP: "",
  ART_DESIG: "Cidade da Horta",
  ART_LOCAL: "",
  TROÇO: "Impares de 1 a 19",
  PORTA: "",
  CLIENTE: "",
  CP4: "1000",
  CP3: "100",
  CPALF: "LISBOA"
}
```
