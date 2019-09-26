# LaTeX Template for NYU

A simple latex template for NYU students~

Written by [Yuan Li](https://github.com/FoxerLee), idea comes from [homework-template](https://github.com/SXKDZ/homework-template).

### Key commands

- `\newsectionone` Section

- `\newsectiontwo` Subsection

- `answer` Where to write your answer

  ```latex
  \begin{answer}
  	Answer question here!
  \end{answer}
  ```

- How to add Code

  ```latex
  \begin{lstlisting}[title=Python code, frame=shadowbox]
  import numpy as np
  x = np.array([137, 135, 127, 122, 120, 118, 118, 117, 117, 114])            
  y = np.array([28540, 40133, 39900, 0, 0, 42050, 43220, 39565, 40400, 54506])
  
  A = np.vstack([x, np.ones(len(x))]).T                                       
  m, c = np.linalg.lstsq(A, y, rcond=None)[0]  
                                 
  \end{lstlisting}
  ```

- `\image` Add a image

  ```latex
  \image{0.4}{img/NYU.png} % para1 -- size, para2 -- image source
  ```

- `equ` Where to write equation

  ```latex
  \begin{equ}
  	E_{in}(w) &= \frac{1}{10}\sum_{i=1}^{10}(\hat{y}_i + y_i)^2\\
  	&= \frac{1}{N}||Xw-y||_2^2
  \end{equ}
  ```

- Other basic information

  ```latex
  \course 
  {\setlength{\unitlength}{1mm}
          \begin{picture}(0,0)
          \put(0,0){\includegraphics[width=0.7cm]{img/NYU.png}} 
          \end{picture}
  } % University's logo
  {Fall 2019} % semester
  {CS-GY 6923} % course number
  
  \university
  {New York University} % university
  {Tandon school of Engineering} % department
  
  \assignment
  {Homework} % assignment name
  {Foxerlee} % student name
  {N12345678} % student ID
  {foxerlee1@gmail.com} % student email
  ```

- Chinese is supported.

### How to contribute?

Feel free to fork it, and make a new pull request!

### Who am I?

- A student of Computer Science and Engineering, NYU Tandon School of Engineering.

- Contact me via foxerlee1@gmail.com

### Thanks

- [SXKDZ](https://github.com/SXKDZ)

### License

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

