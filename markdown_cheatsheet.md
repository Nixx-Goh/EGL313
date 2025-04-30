# Headers
This is for **heading 1**.

## Heading 2
This is for *heading 2*.

### Heading 3
This is for ***heading 3***.


# List
This is how you list items in markdown.
1. Member 1 
    * Team Leader
        * Project Owner
2. Member 2
    * Hardware
3. Member 3
    * Software
3. Member 4
    * Cheerleader


# Inserting an Image

To insert an image, you will need to drag + hold shift + drop 

![alt text](<seventeen ima.JPG>)

[Click here to link](https://www.google.com)

[Click here to jump to test.md](/test/test.md)


# Code Block

To highlight of insert a particular section of code, you can do the following:

1. In Raspberry Pi, if you want to update you will `sudo apt update` 

```
from tkinter import *

main = Tk()

main.mainloop()
```

# Quotes

A famous quote by **Sir Isaac Newton**
> For every action, there will be a reaction.


# Tables

This is how you insert tables

|Header A|Header B|Header C|
|--------|--------|--------|
|Row 1   |Data A  |Data B  |
|Row 2   |Data C  |Data D  |

```
|-----:| This is to justify right
|:-----| This is to justify left
|:----:| This is to justify center
```


# Horizontal Rule

This is how to insert a section line

---


# Flowchart

```mermaid
graph LR

A[Sensor 1] --GPIO 17--> B
B[Raspberry Pi]-->C[L-Acoustic K2 </br>Linear Line Array]
A--> B
B--> C
C--> A

```


# Sequence Diagram

```mermaid
sequenceDiagram;

Alice-->> Bob: Hello, how are you?
Bob-> Alice: I am good, thanks!
Alice--> Charlie: Have you eaten?
Charlie-> Alice: No, I have not.

```


