# Introduction to the Jupyter Notebooks

## Jupyter Notebooks

The easiest way to create a new Jupyter Notebook, or to open an existing one on your computer, is to install the latest version of Anaconda. 

**[Anaconda Main Page](https://www.anaconda.com)**  

**[Anaconda Installer](https://www.anaconda.com/distribution/)**  

Choose the version which coresponds to your Operatinng System and install it using the default settings during the instalation.

Then, whenever you want to run a Jupyter Notebook, you could either start the "Anaconda Navigator" and select "Jupyter Notebooks", or for a faster aproach, open the "Anaconda Promt" and type: jupyter notebook

After a few seconds, your default web-browser will open up automatically, while a server will be running in the background.

At this point, you could either open an existing Jupyter Notebook or altrenatively, you could start from scratch and create a new Jupyter Notebook.

## Contents of a Jupyter Notebook

We can insert three types of cells in a Jupyter Notebook:

* Cells that contain Markdown language
* Cells that contain code to be executed 
* Cells that contain Raw text which remains exactly as it was entered

## Markdown language

In a Jupyter Notebook, we type the Markdown syntax in a Markdown cell and then, we click to run the cell, so that the Markdown syntax will appear in it's correct form.

Should we need to make changes, we just click inside a Markdown cell and as soon as we complete our changes, we click to run, once again the Markdown cell.

Below there's an overview of the Markdown syntax.

*(Firstly, the Markdown syntax is shown in the highlighted window and then, just below, the output format appears)*

## Headings:

```
# this is a size 1 heading
## this is a size 2 heading
### this is a size 3 heading
#### this is a size 4 heading
##### this is a size 5 heading
###### this is a size 6 heading
```

# this is a size 1 heading
## this is a size 2 heading
### this is a size 3 heading
#### this is a size 4 heading
##### this is a size 5 heading
###### this is a size 6 heading

## Bold and Italics:
```
**this thext is bold**

_this text is italized_

**combination of _italized_ and bold**

_combination of **bold** and italized_

```
**this thext is bold**

_this text is italized_

**combination of _italized_ and bold**

_combination of **bold** and italized_

## Ordered Lists:
```
1. first item
2. second item
3. third item
```
1. first item
2. second item
3. third item
```
1. first item
2. second item
   1. second item a
   2. second item b
   3. second item c
3. third item
   1. third item a
   2. third item b
   3. third item c
```
1. first item
2. second item
   1. second item a
   2. second item b
   3. second item c
3. third item
   1. third item a
   2. third item b
   3. third item c

## Unordered Lists:

```
* first item
* second item
* third item
```
* first item
* second item
* third item
```
* first item
* second item
   * second item a
   * second item b
   * second item c
* third item
   * third item a
   * third item b
   * third item c
```
* first item
* second item
   * second item a
   * second item b
   * second item c
* third item
   * third item a
   * third item b
   * third item c

## Task Lists:

```
* [ ] unchecked item 1
* [x] checked item 2
* [x] checked item 3
```

* [ ] unchecked item 1
* [x] checked item 2
* [x] checked item 3

```
* [ ] unchecked item 1
    * [ ] subitem 1a
    * [ ] subitem 1b
* [x] checked item 2
* [x] checked item 3
    * [x] subitem 3a
```

* [ ] unchecked item 1
    * [ ] subitem 1a
    * [ ] subitem 1b
* [x] checked item 2
* [x] checked item 3
    * [x] subitem 3a

## Tables:
```
header one | header two | header three
-----------|------------| ------------
first item in #1 | first item in #2 | first item in # 3
second item in # 1 | second item in # 2 | second item in # 3
third item in # 1 | third item in # 2 | third itemm in # 3
```
header one | header two | header three
-----------|------------| ------------
first item in #1 | first item in #2 | first item in # 3
second item in # 1 | second item in # 2 | second item in # 3
third item in # 1 | third item in # 2 | third itemm in # 3

```
items align left | items align center | items align right
:---   |   :---:   |   ---:
item 1a | item 2a | item 3a
item 1b | item 2b | item 3b
item 1c | item 2c | item 3c
```
items align left | items align center | items align right
:---   |   :---:   |   ---:
item 1a | item 2a | item 3a
item 1b | item 2b | item 3b
item 1c | item 2c | item 3c

## Code:

`` this is an `inline code` example ``

this is an `inline code` example

````
```
This is a longer

code example
```
````

```
This is a longer

code example
```

## Links:

```
https://www.google.com
```
https://www.google.com

```
[GitHub](http://github.com)
```
[GitHub](http://github.com)

## Images

```
![profile photo of a large brown and white dog named merfys](merfys.JPG)
```
![profile photo of a large brown and white dog named merfys](merfys.JPG)


## Clickable Images

First, we write the code for the link and then, the code for the image:

```

Link:
[Merfy's GitHub Page](https://antzm.github.io/)

Image:
![Merfy's the dog looking at the camera](merfy.jpg)

```

Now, use the code for the link and replace whatever is inside the `[...]` with the full code of the image:

i.e. Just replace the link description "Merfy's GitHub Page" with the image. So, a clickable link is just using an image to describe a link, instead of using traditional text.

```

Clickable Image:
[![Merfy's the dog looking at the camera](merfy.jpg)](https://antzm.github.io/)


```

[![Merfy's the dog looking at the camera](merfy.jpg)](https://antzm.github.io/)

