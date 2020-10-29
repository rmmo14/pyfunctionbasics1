# pyfunctionbasics1
## 1
variable|value
---------|------
a()| 5
prints| 5

## 2
variable|value
---------|------
a()|5
prints|10

## 3
variable|value
---------|-----
a()|5, 10
prints| 10

## 4
variable|value
---------|-----
a()|5
prints| 10, 5

## 5
variable|value
---------|-----
a()|
x|a()
prints|5

## 6
variable|value
---------|-----
a|1 -> 2
b|2 - > 3
a(b,c)|1+2 -> 2+3 - > 3+5
prints|3, 5, 8

## 7 
variable|value
---------|-----
b|2
c|5
a(b,c)|"25"
prints|"25"

## 8
variable|value
---------|-----
a()|10 - > 7
b|100
prints|100, 7

## 9
variable|value
---------|-----
a(b,c)|7 -> 3 -> 14 -> 3
b|2 -> 5 
c|3 - > 3
prints|3, 3

## 10
variable|value
---------|-----
a(b,c)|8, 10
b|3
c|5
prints|10

## 11
variable|value
---------|-----
b|500 -> 300
a()|
prints|500, 500, 300, 500

## 12
variable|value
---------|-----
b|500 -> 300
a()|
prints|500, 500, 300, 300

## 13
variable|value
---------|-----
b|500 -> 300 -> 300
a()|300
prints|500, 500, 300,  300

## 14
variable|value
---------|-----
a()|
b()|
prints|1, 3, 2

## 15
variable|value
---------|-----
a()|10
b()|5
y|10
x|5
prints|1, 3, 5, 10