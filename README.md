# schemas

## Styles

`site.css` is compiled from `sass/site.sass` with [Sassy](https://github.com/bfren/sassy) (a submodule):

```sh
git submodule update --init
sass --no-source-map --style=compressed sass/site.sass site.css
```
