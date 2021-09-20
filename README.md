# hello-gh-pages-api

GitHub PagesをAPIとして使う

https://katai5plate.github.io/hello-gh-pages-api/

```js
(async () => {
  const res = await(await fetch("https://katai5plate.github.io/hello-gh-pages-api/")).json();
  console.log(res);
})()
```
