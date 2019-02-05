# Interactive Tutorial 1: Markdown

## Working with Markdown

Press `Ctrl + Shift + M` to open a formatted preview on the right.

## Basic Text

Write two sentences about yourself, each in a different paragraph.

Hi, I'm Ronya, and I'm a biomedical engineering major from Seattle.

Some of my favorite things include cats, rock climbing, and bubble tea.

## Headers

Make a 3rd level header with your name:

### Ronya Strom

## Emphasis

Write 4 of your favorite words using each type of emphasis:

*cats* **dogs** ***bunnies*** ~~pigs~~

## Lists

Make an ordered list of 3 things you hope to achieve this semester, and elaborate on them with sub items. Then, make an unordered list of 3 classes that you're taking this semester:

1. Learn more about the scale of the untreated water crisis
2. Become involved in the aguaclara team as a whole
3. Help my subteam find answers concerning the factors that affect sand filtration

- Math 1920
- Biomg 1350
- Physics 1112

## Links

Write a sentence describing your major, and insert a link to your major's department website:

[I'm majoring in biomedical engineering, which uses technology to solve problems in healthcare and medicine](https://www.bme.cornell.edu/bme)

## Images

Insert the Cornell seal image with:
  1. A relative file path(`/images/Cornell_University_seal.png`)
  2. A URL (https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)

!(`/images/Cornell_University_seal.png`)
!(https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)


## Code Formatting

Put the name of this file in an in-line (single backtick) code format.

`Interactive-Tutorial-1-Markdown`

Put the following text in a Python-formatted code block:

```
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

```python
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

## Tables

Create a table listing your 3 favorite animals, books, and places on campus. Use a different alignment for each column.

| Animals | Books | Places on Campus |
| --- | :---: | ---: |
| Cats  | Pride and Prejudice  | Lindseth Climbing Wall |
| Bunnies  | Being Mortal  | Mann  |
| Dogs   |  I Am a Cat | Clara Dickson  |


## Blockquotes

Write your favorite quote. It must be attributed to Albert Einstein.

> "I have no special talent. I am only passionately curious."

## Horizontal Rules

Add a horizontal rule:

---

## LaTeX Formatting

Copy the equation towards the end of the [Markdown tutorial](https://github.com/AguaClara/aguaclara_tutorial/wiki/Markdown#latex-formatting) and paste it here:

$$ a^2 + b^2 = c^2 $$
