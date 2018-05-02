classnames can be used to help handle conditional styles in a more elegant fashion.
allows for us to define complex classnames in an intuitive manner. 

For example, in render, we apply the todos-list-item class regardless, however, if the todo.completed
state is true, we also add the completed class. That is, if the todo is completed,
it gets 'todos-list-item completed'; if not, only 'todos-list-item' is returned.
You can, obviously, add many more conditionals for more complex classnames.

```
$ npm install classnames --save
```


## CSS Preprocessors
Sass has two syntaxes. The most commonly used syntax is known as “SCSS” (for “Sassy CSS”), and is a superset of CSS3’s syntax. This means that every valid CSS3 stylesheet is valid SCSS as well. SCSS files use the extension .scss.

The second, older syntax is known as the indented syntax (or just “.sass”). Inspired by Haml’s terseness, it’s intended for people who prefer conciseness over similarity to CSS. Instead of brackets and semicolons, it uses the indentation of lines to specify blocks. Files in the indented syntax use the extension .sass.

```
$ npm install sass-loader node-sass --save-dev
```
webpack.config.js
```
```


