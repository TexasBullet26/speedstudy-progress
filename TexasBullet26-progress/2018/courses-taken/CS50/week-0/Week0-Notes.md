## CS50 Week 0

---

### Table of Contents (Video)
  - Introduction (6 mins)
  - Binary (6 mins)
  - Binary Lamps (2 mins)
  - ASCII (3 mins)
  - RGB (2 mins)
  - Thinking with Peanut Butter (6 mins)
  - Finding Mike Smith (3 mins)
  - Computational Complexity (3 mins)
  - Pseudocode (4 mins)
  - Staff Introductions (3 mins)
  - Course Teaser (3 mins)
  - Introducing Scratch (8 mins)
  - meow (6 mins)
  - Oscartime (4 mins)
  - counting sheep (2 mins)
  - pet the cat (1 mins)
  - don't pet the cat (1 mins)
  - threads (2 mins)
  - events (1 mins)
  - hi hi hi (2 mins)
  - Ivy's Hardest Game (4 mins)

### My Notes

**Problem Solving**:

Inputs => Algorithms => Outputs

**Binary**:
001 = 1
010 = 2
011 = 3
100 = 4
101 = 5
110 = 6
111 = 7
1000 = 8
1001 = 9
1010 = 10
1011 = 11
1100 = 12
1101 = 13
1110 = 14
1111 = 15
etc.

**Transistors**:
Switches of 0s and 1s representing off and on.

**ASCII**:
A => 65
B => 66
C => 67
D => 68
E => 69
F => 70
G => 71
H => 72
I => 73
J => 74
K => 75
L => 76
M => 77
N => 78
O => 79
P => 80
Q => 81
R => 82
S => 83
T => 84
U => 85
V => 86
W => 87
X => 88
Y => 89
Z => 90

**UNICODE**:
Came along once programming became popular in non-english speaking countries, therefor the need for more characters.

1 byte = 8 bits
8 bits = 111 binary

0 0 0 0 0 0 0 0

2 2 2 2 2 2 2 2

7 6 5 4 3 2 1 0 (Powers of 2)

128-64-32-16-8-4-2-1

11111111 binary = 256 bits = 32 bytes

**Algorithms**:
  - Steps of instructions for a desired output
  - n
  - n/2
  - log**n

**Psuedocode**:
Human-readable instructions for code. Example:
```
0  pick up phone book
1  open to middle of phone book
2  look at names
3  if Smith is among names
4      call Mike (you should only do if Smith is among names)
5  else if Smith is earlier in book
6      open to middle of left half of book
7      go back to step 2 (recursive)
8  else if Smith is later in book
9      open to middle of right half of book
10     go back to step 2
11 else
12     quit
```

Functions
Conditions
Boolean expressions

**Introducing Scratch**:
  - "hello, world" in C:
```C
#include <stdio.h>

int main(void)
{
  printf("hello, world\n");
}
```

Scratch is a program written by MIT that enables you to write programs as a set of puzzle pieces.

functions
conditions
Boolean expressions
loops
variables
threads
events
...

purple = functions
orange = variables
yellow = conditions
green = Boolean expressions

**Multi-threading**: Doing multiple things at a time. (Interaction)

**Event-handling**: Something doing another thing in response to that something. Example:
```
when green flag clicked
  forever (loop)
    if (loop) space pressed then
      say Marco for 2 secs
      broadcast event (event-handling)
    end if loop
  repeat forever (loop)
```

0 false
1 true
