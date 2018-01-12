Demonstration of multiprocessing module of Python. 
**Serialization** vs **Parallelization with static distribution of work** vs **Parallelization with dynamic load balancing**.


The [Mandelbrot set](https://en.wikipedia.org/wiki/Mandelbrot_set) is one of the most complex and beautiful images arising from mathematics. It is defined to be the set of [complex numbers](https://en.wikipedia.org/wiki/Complex_number) for which the function f<sub>c</sub>(z) = z<sup>2</sup> + c does not diverge when iterated from z=0. For a clear explanation of what that means, see [this video](https://www.youtube.com/watch?v=NGMRB4O922I) on YouTube featuring Dr. Holly Krieger from MIT.



   Each point in the image corresponds a different number, c, in the complex plane. The x-axis represents the real component of the complex number and the y-axis represents the imaginary component of the complex number.

  Each different color in the image represents how many iterations it took for the function f(z) to diverge. For points where the function f(z) does not diverge (for example, c=0), the corresponding pixel is usually colored black.
  
  
**Goal of project**:
Implementation of multiprocessing module of Python to achieve better speed by leveraging multiprocessors in modern computers for doing heavy computational tasks.
