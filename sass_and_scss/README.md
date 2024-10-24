![Sass](images/sass.jpg)

# Resources

**Read or watch:**

- [Sass Basics](https://sass-lang.com/guide/)
- [Sass flow control directives: @if, @for, @each and @while](https://sass-lang.com/documentation/at-rules/control/)
- [Sass references](https://sass-lang.com/documentation/)

# Learning Objectives
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/), **without the help of Google:**

## General

- What Sass means
- How to write Sass & Scss file
- What is the difference between Sass and Scss
- What is the Sass preprocessing
- How to declare a variable
- How to use nested definition
- How to import a Sass file
- How to use mixins
- How to declare extend/inheritance styles
- How to manipulate operators

# Requirements

## General
- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be executed on Ubuntu 18.04 LTS using `Sass 3.7.4` (or higher)
- All your files should end with a new line
- All your Scss files should have a comment at the beginning (i.e. syntax above)
- All your files should start by a comment describing the task
- A `README.md` file, at the root of the folder of the project, is mandatory
- The length of your files will be tested using `wc`

# More Info

## Comments for your Scss file:

**All your Scss file must start with a comment block**

```scss
$ cat my_styles.scss
/* My style */
body {
    .container {
        color: #3D3D3D;
    }
}
$
```

**Install Sass/Scss on Ubuntu 18.04 LTS**

```bash
$ sudo apt-get install -y ruby2.5 ruby2.5-dev
$ sudo apt-get install ubuntu-dev-tools
$ gem install sass -v 3.7.4
$ sass --version
Ruby Sass 3.7.4
```

![Image](images/image.jpg)

## Quiz questions

### Question #0

What Sass means?

- [ ] Simply Awesome StyleSheets

- [ ] Super Awesome StyleSheets

- [ ] Syntactically Augmented StyleSheets

- [ ] Syntactically Awesome StyleSheets

### Question #1

How to import a file?

- [ ] from my_file import *

- [ ] @import 'my_file';

- [ ] @import 'my_file.scss';

- [ ] #import 'my_file';

Question #2
Who designed Sass?


Natalie Weizenbaum


Hampton Catlin


Guido van Rossum

Question #3
How to declare variable?


const my_var


var my_var


$my_var


int my_var


let my_var

Question #4
How to create a “for each” loop?


@each $my_item in $my_list


@for $my_item in $my_list


@foreach $my_item in $my_list


@for $my_item each in $my_list

Question #5
Does Sass allow function creation?


No


Yes

Question #6
How to create a “while” loop?


@for $i < 10


@while $i is under 10


@while $i < 10


@while $i < 10 then
