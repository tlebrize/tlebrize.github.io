__This project is an introduction to graphic programming.
The goal is to create a simplified graphic "wireframe" representation
of a relief landscape, by linnking various points together.__

__Fdf project was written in C, usgin Minilibx as a graphical library.
Minilibx is a really small graphical library, with it you can only draw pixels one
by one on a 2D plane. I had to implement a line drawing and projection algorithm.__

![42](42.png)

__The coordinates are stored in a file passed to the program.
the horizontal position of each value corresponds to its axis,
the vertical position corresponds to its ordinate and his value corresponds to its altitude.__

__This is the input given to produce the picture above.__
```
0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
0  10  10   0   0  10  10   0   0  10  10  10  10  10   0   0
0  10  10   0   0  10  10   0   0   0   0   0   0  10  10   0
0  10  10   0   0  10  10   0   0   0   0   0   0  10  10   0
0  10  10  10  10  10  10   0   0   0  10  10  10  10   0   0
0   0  10  10  10  10  10   0   0  10  10   0   0   0   0   0
0   0   0   0   0  10  10   0   0  10  10   0   0   0   0   0
0   0   0   0   0  10  10   0   0  10  10  10  10  10  10   0
0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
```

__I decided to add colors depending on the altitude, they are choosed randomly.
Two more examples :__

![pyra](pyra.png)

![mars](mars.png)

![mars_zoom](mars_zoom.png)


[Subject](https://cdn.intra.42.fr/pdf/pdf/881/fdf.en.pdf)