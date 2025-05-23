# knitting helper
A small program that converts knitting instructions into patterns.

Knitting can be complicated, especially to a beginner such as myself. Instructions may be difficult to follow when they look like a jarred mess of letters and numbers. To help myself with the process, I usually use pen and paper to figure out how the pattern will look. This takes a pretty long time. To save time and apply my new-learned JavaScript skills, I've created a tool to help turn the not-so-often intelligeble instructions into visually represented patterns. The point of that is exact the same as the pen and paper trick - to resemble the look of the finished fabric in real life. Knitting is a sort of programming after all, and Knitter helper is a program created with a very specific usecase in mind. Thus, it maybe a little hard to understand at the beginning, especially if one's not familiar with the art of knitting.

# User Guide

- To understand how the Knitting helper works, one needs to first and foremost be familiar with the knitting-specific terminology.

- "CO" stands for "Cast On". This means the number of stitches that we are *casting on* to the knitting needles. The cast on number will determine the length of the fabric on the needle.

- "K" stands for "Knit", and "P" stands for "Purl". They are the two basic knitting stitches. They look different, and in the program we represent them as "v" for "knit" and "-" for "purl", resembling their appearence in real knitted fabric.

- Usually the pattern also indicates edge stitches, at the beginning and at the end of the row.

- This is what the program invites us to enter: the CO number, the starting edge, the part the repeats (usually indicated by being placed between parenthesis () or stars ** in the pattern), and the end edge.

![knitterhelper3](https://github.com/user-attachments/assets/beca75d3-ff5e-439c-b65b-817edaf83d3f)


- Now let's look at an example instructions from So Woolly:

![alternatingdot](https://github.com/user-attachments/assets/d5f22c52-7e88-4016-8b7a-2e452139042e)

- The pattern calls for an odd number of stitches. Let's try casting on (CO) 21 stitches, and following the instructions:

![knitterhelper1](https://github.com/user-attachments/assets/d48aba43-1f17-4103-9ceb-e641a971654a)

- Entering the instructions will give us this pattern:
 
![knitterhelper2](https://github.com/user-attachments/assets/b2a8bed0-b6e1-477e-9133-6fcd2d4fcbdb)

- Which would looks something like this, knitted:
 
![alternatingdot2](https://github.com/user-attachments/assets/a7c179f9-ac4d-4c13-8e37-d989e0f51d0c)

# Things to improve:
  -  Add an example instruction to get the user started.
  -  Allow for "flipping" the rows.
  -  Allow adding new rows as needed.
  -  Allow to repeat the entire output pattern to get a better understanding of the finished fabric.
  -  Give feedback to the user when the pattern has gaps, indicating that there might something wrong with the input.
  -  Improve the look of the page.
  -  Allow for more than 28 columns.
  -  Allow for more than 4 rows.
  -  The amount of variables can probably be improved (read: reduced). Right now I have about 30 variables which is way too much for something this small. 
  -  The important part of the array manipulations are made with .concat method which I've learned is not the proper way to do this. Can probably be improved with .splice, so this is something I would need to look into.
