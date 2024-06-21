# Fractals🎩

My journey into learning what fractals are and how to see them on my computer.

<b>Roadmap</b>: 
* Theory / Notes.
* Implementation.
* Further on documentation.
* Last touches / cleanup.

<b>Ideas later down the road:</b>
* Julia set.
* Mandelbulb.
* Animation.


## Theory - Math🧮

<hr>

### i : To the power of...🔢
<br>
i : The number i! An imaginary unit.

i : Defined as <b><u>i^2 = -1</u></b>.

i^0 = 1

i^1 = i

i^2 = -1

i^3 = i^2 * i = -1 * i = -i

i^4 = i^2 * i^2 = -1 * -1 = 1 

i^5 = i^4 * i = 1 * i = i

i^6 = i^4 * i^2 = 1 * -1 = -1

i^7 = i^4 * i^3 = 1 * -i = -i

i^8 = i^4 * i^4 = 1 * 1 = 1

i^9 = i^8 * i = 1 * i = i

i^10 = i^8 * i^2 = 1 * -1 = -1

<hr>

### i : Squaring and √roots!
<br>

Numbers that have the form of b * i such as <b>3i</b> or <b>17i</b> are imaginary numbers where b is a non-zero real number.

By further on taking the square of the number 3i we can see that: (3i)^2 is equal to =
(3^2) * (i^2) = 9 * i^2 = 9 * (-1) = -9. So 3i is a square root of -9.

Another example featuring (4i)^2 = (4^2) * (i^2) = 16 * (-1) = -16. So 4i is a square root of -16.

Imaginary numbers are square roots of negative numbers.

<hr>

### Simplified and unsimplified forms
<br>

ps. Tables are generated using this [table generator tool](https://www.tablesgenerator.com/markdown_tables).

pss. Math is visualized using this [equation editor tool](https://editor.codecogs.com/).

|                        Unsimplified                         |                           Simplified                            |
|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
|  <img src=https://latex.codecogs.com/svg.image?\sqrt{-9}>   |        <img src=https://latex.codecogs.com/svg.image?3i>        |
|  <img src=https://latex.codecogs.com/svg.image?\sqrt{-5}>   | <img src=https://latex.codecogs.com/svg.image?&space;i\sqrt{5}> |
| <img src=https://latex.codecogs.com/svg.image?-\sqrt{-144}> |       <img src=https://latex.codecogs.com/svg.image?-12i>       |

Let's delve into the <u>example</u> of <img src="https://latex.codecogs.com/svg.image?\sqrt{-9}=3i">:

-9 is an imaginary number and the square root of 9 is 3.

The square root of negative 9 (-9) is 3 imaginary units (3i).

Let's see another example of <img src="https://latex.codecogs.com/svg.image?\sqrt{-18}">:

Since this is an imaginary number we can write is as such <img src="https://latex.codecogs.com/svg.image?i\sqrt{18}">

Then we just keep simplifying it.  

<img src="https://latex.codecogs.com/svg.image?&space;i*\sqrt{9*2}=i*\sqrt{9}*\sqrt{2}=i*3*\sqrt{2}=3i\sqrt{2}">
