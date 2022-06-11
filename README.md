# Markdown-Cheatsheet

- [Paragraph](#Paragraph)
- [Italic](#Italic)
- [Bold](#Bold)
- [Strike-through](#Strike-through)
- [Headings](#Headings)
- [Heading-ID](#Heading-ID)
- [Links](#Links)
- [Image](#Image)
- [List](#List)
- [Line-Break](#Line-Break)
- [Horizontal-Rule](#Horizontal-Rule)
- [Block-Quotes](#Block-Quotes)
- [Code](#Code)
- [Tables](#Tables)
- [Check-Box](#Check-Box)

---

## Paragraph

```
Hey this is my Paragraph
this is my <br> new line
```

Hey this is my Paragraph
this is my <br> new line

---

## Italic

```
I am very *cool* developer and passionate about _technology_.
```

I am very _cool_ developer and passionate about _technology_.

---

## Bold

```
I am trying to become a **great developer** and great __problem solver__.
```

I am trying to become a **great developer** and great **problem solver**.

---

## Strike Through

```
~~I can't do~~ I can do anything
```

~~I can't do~~ I can do anything

---

# Headings

```

# Heading1

## Heading2

### Heading3

#### Heading4

##### Heading5

###### Heading6
```

# Heading1

## Heading2

### Heading3

#### Heading4

##### Heading5

###### Heading6

<br>

Another ways to write headings using(**===,----**):-

```
Heading1
========

Heading2
--------
```

# Heading1

## Heading2

---

## Heading ID's

```
set the id to heading
## Paragraph {#para}
```

```
 Linking to Paragraph heading
 [Go to Paragraph](#para)
```

[Go to Paragraph](#Paragraph)

---

## Links

```
<htttp://wesbos.com>

[My Github](http://github.com/mahesh-bauri)

[Hackeryou.com](http://hackeryou.com "This is title")

Make sure you check out my [Github][1] and [Linkedin][2] Profile

This is my same [Github][git] id

[git]: http://github.com/mahesh-bauri
[1]: http://github.com/mahesh-bauri
[2]: https://www.linkedin.com/in/mahesh-bauri/
```

<htttp://wesbos.com>

[My Github](http://github.com/mahesh-bauri)

[Hackeryou.com](http://hackeryou.com "This is title")

Make sure you check out my [Github][1] and [Linkedin][2] Profile

This is my same [Github][git] id

[git]: http://github.com/mahesh-bauri
[1]: http://github.com/mahesh-bauri
[2]: http://linkedin.com/mahesh-bauri

---

## Image

```

##### Method 1

![this is alt text](https://aws1.discourse-cdn.com/business7/uploads/glideapps/original/2X/4/4936e0f28f79c8a2aa95582741091356d0ed61d8.jpeg "this is an image title")

<br>

##### Methode 2

![alt][image]

[image]: https://aws1.discourse-cdn.com/business7/uploads/glideapps/original/2X/4/4936e0f28f79c8a2aa95582741091356d0ed61d8.jpeg

<br>

##### Nested image

[![](https://aws1.discourse-cdn.com/business7/uploads/glideapps/original/2X/4/4936e0f28f79c8a2aa95582741091356d0ed61d8.jpeg)](http://unsplash.it/400/300/)

<br>

##### Link on image

[<img src="https://images.unsplash.com/photo-1589490047559-a1c13ec25b87?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1yZWxhdGVkfDE0fHx8ZW58MHx8fHw%3D&w=1000&q=80" />](http://unsplash.com)

<br>

##### HTML and CSS

<img src="https://images.unsplash.com/photo-1589490047559-a1c13ec25b87?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1yZWxhdGVkfDE0fHx8ZW58MHx8fHw%3D&w=1000&q=80" width="200" height="300" alt="unsplash image">

<style>
    img{
        border:2px solid grey;
    }
</style>
```

##### Method 1

![this is alt text](https://aws1.discourse-cdn.com/business7/uploads/glideapps/original/2X/4/4936e0f28f79c8a2aa95582741091356d0ed61d8.jpeg "this is an image title")

<br>

##### Method 2

![alt][image]

[image]: https://aws1.discourse-cdn.com/business7/uploads/glideapps/original/2X/4/4936e0f28f79c8a2aa95582741091356d0ed61d8.jpeg

<br>

##### Nested image

[![](https://aws1.discourse-cdn.com/business7/uploads/glideapps/original/2X/4/4936e0f28f79c8a2aa95582741091356d0ed61d8.jpeg)](http://unsplash.it/400/300/)

<br>

##### Link on image

[<img src="https://images.unsplash.com/photo-1589490047559-a1c13ec25b87?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1yZWxhdGVkfDE0fHx8ZW58MHx8fHw%3D&w=1000&q=80" />](http://unsplash.com)

<br>

##### HTML and CSS

<img src="https://images.unsplash.com/photo-1589490047559-a1c13ec25b87?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1yZWxhdGVkfDE0fHx8ZW58MHx8fHw%3D&w=1000&q=80" width="200" height="300" alt="unsplash image">

<style>
    img{
        border:2px solid grey;
    }
</style>

---

## Lists

##### Unordered List

```
_using (\-)_

* Item
* Item
* Item
* Item

_using (\-)_

- Item2
- Item2
- Item2
- Item2

_using (\+)_

+ Item3
+ Item3
+ Item3
+ Item3
```

**using (\*)**

- Item
- Item
- Item
- Item

**using (\-)**

- Item2
- Item2
- Item2
- Item2

**using (\+)**

- Item3
- Item3
- Item3
- Item3

#### Ordered List

```
1. Item
1. Item
1. Item
1. Item

<br>

1. Item2
2. Item2
3. Item2
4. Item2
```

1. Item
1. Item
1. Item
1. Item

<br>

1. Item2
2. Item2
3. Item2
4. Item2

#### Nested List

```
1. Outer
   - inner
   - inner2
     - nested inner
     - nested inner
     - nested image
       ![](https://c4.wallpaperflare.com/wallpaper/819/300/939/train-valley-glenfinnan-viaduct-hd-wallpaper-preview.jpg)
2. Outer2
```

1. Outer
   - inner
   - inner2
     - nested inner
     - nested inner
     - nested image
       ![](https://c4.wallpaperflare.com/wallpaper/819/300/939/train-valley-glenfinnan-viaduct-hd-wallpaper-preview.jpg)
2. Outer2

---

## Line Break

```
Mahesh is cool <br>
He really love Programming
```

Mahesh is cool <br>
He really love Programming

---

## Horizontal Rules

```
This is HR. After line must add one line space.

---
```

This is HR. After line must add one line space.

---

## Block Quotes

```
> Crazy dreams takes crazy effort.
  _just do it_
  multiline
>
> Another line
```

> Crazy dreams takes crazy effort.
> _just do it_
> multiline
>
> Another line

---

## Code

Here is my code :

using (**indent**)

```
    //indent
    var x = 100;
    const name = "mahesh";
```

    var x = 100;
    const name = "mahesh";

using (**```**)

> \```
> var x = 100;
> const name = "mahesh";
> \```

```
var x = 100;
const name = "mahesh";
```

<br>

_Syntax highlight for specific languages :-_

**php**

> \```php
> $age = 30;
> echo "hello";  
> \```

```php
$age = 30;
echo "hello";
```

**javascript**

> \```js
> var x = 100;
> const id = "hacker";
> \```

```js
var x = 100;
const id = "hacker";
```

**json**

> \```json
> {
> "firstName": "John",
> "lastName": "Smith",
> "age": 25
> }
> \```

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

**Inline code**

```
Hey did you try `var x = 100;` ?
Difference b/w `let` and `var`?
```

Hey did you try `var x = 100;` ?
Difference b/w `let` and `var`?

**diff**

> \``` diff
> var x = 100;
> \- var y = 200; //
> \+ var y = 300; // updated
> \```

```diff
var x = 100;
- var y = 200; //
+ var y = 300; // updated
```

---

## Tables

```
text alignment
center |:----:|
left   |:-----|
right  |-----:|


| Sites Name | Solved |
|:-----------|-------:|
| Leetcode   |180+    |
| GFG|200+|
|Codechef|150+|
```

| Sites Name | Solved |
| :--------- | -----: |
| Leetcode   |   180+ |
| GFG        |   200+ |
| Codechef   |   150+ |

**text alignment center**

```
| Sites Name | Solved |
|:----------:|:------:|
| Leetcode   |180+    |
| GFG|200+|
|Codechef|150+|
```

| Sites Name | Solved |
| :--------: | :----: |
|  Leetcode  |  180+  |
|    GFG     |  200+  |
|  Codechef  |  150+  |

**text aling left**

```
| Sites Name | Solved |
| :--------- | :----- |
| Leetcode   | 180+   |
| GFG        | 200+   |
| Codechef   | 150+   |
```

| Sites Name | Solved |
| :--------- | :----- |
| Leetcode   | 180+   |
| GFG        | 200+   |
| Codechef   | 150+   |

**text aling right**

```
| Sites Name | Solved |
| ---------: | -----: |
|Leetcode|180+|
| GFG |200+ |
|   Codechef |   150+ |
```

| Sites Name | Solved |
| ---------: | -----: |
|   Leetcode |   180+ |
|        GFG |   200+ |
|   Codechef |   150+ |

---

## Check box

```
* [X] Javascript
* [ ] Python
* [X] C++
* [ ] C
* [ ] Go
* [ ] Ruby
```

- [x] Javascript
- [ ] Python
- [x] C++
- [ ] C
- [ ] Go
- [ ] Ruby

**Nested checkbox**

```
* [ ] Language
    * [ ] Python
    * [X] JavaScript
    * [ ] Java
* [ ] Library
    * [X] React
    * [ ] Angular
    * [ ] Vue
```

- [ ] Language
  - [ ] Python
  - [x] JavaScript
  - [ ] Java
- [ ] Library
  - [x] React
  - [ ] Angular
  - [ ] Vue

[Go to Top :point_up:](#Markdown-Cheatsheet)

Made with :heart: by [Mahesh](https://www.linkedin.com/in/mahesh-bauri/)
