# Example Jupyter Notebooks

## Jupyter Notebooks

The easiest way to run Jupyter Notebooks on your computer, is to install the latest version of Anaconda. Choose the version which coresponds to your Operatinng System and install it using the default settings during the instalation.

When you want to run a Jupyter Notebook, you could either start the 'Anaconda Navigator' and select 'Jupyter Notebooks', or for a faster aproach, open the "Anaconda Promt" and type: jupyter notebook

After a few seconds, your default web-browser will open up automatically and a server will be running in the background.

At this point, you could either open an existing Jupyter Notebook or altrenatively you could start from scratch and create a new Jupyter Notebook.

## Contents of a Jupyter Notebook

We can insert three types of cell in a Jupyter Notebook:

* Cells with Markdown language in them
* Cells that contain code to be executed 
* Cells with Raw text that remains exactly as it was entered

## Markdown language

Below there's an overview of the markdown syntax:

(Firstly, the markdown syntax is shown in the highlighted window and then, just below, the output format appears)

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

