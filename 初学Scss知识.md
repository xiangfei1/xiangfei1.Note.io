### Scss(Syntactically Awesome StyleSheets)  

Sass 是一款强化CSS的辅助工具，官网 [sass.hk](https://www.sass.hk/)

CSS功能的扩展

1. 父选择器 &

   ```css
   /*在嵌套 CSS 规则时，有时也需要直接使用嵌套外层的父选择器，例如，当给某个元素设定 hover 样式时，或者当 body 元素有某个 classname 时，可以用 & 代表嵌套规则外层的父选择器。*/
   a {
     font-weight: bold;
     text-decoration: none;
     &:hover { text-decoration: underline; }
     body.firefox & { font-weight: normal; }
   }
   /*编译为*/
   a {
     font-weight: bold;
     text-decoration: none; }
     a:hover {
       text-decoration: underline; }
     body.firefox a {
       font-weight: normal; }
   ```

   