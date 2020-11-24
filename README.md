# Sorting Algorithm Visualisation in C++ using OPENGL 
While learning the common sorting algorithms I was told the intermediate steps how the sorting used to happen in each algorithm and the number of comparisons required to sort. Similarly most books and tutorial videos show the step by step working of how each algorithm makes comparisons and sorts. This step is fundamentaly important for understanding the algorithm. Bun when we run a code of a sorting algorithm it sorts all at once.
So I wished to emulate the intermediate steps as is often taught to us and display the process of sorting. Thus I wrote this program using OPENGL Graphics Library to visualise the sorting process which is very intriguing in itself 
  
We can see and realize first hand the speed and efficiency of the Sorting Algorithms which otherwise we only prove by time-complexity analysis.

I have as of now coded the following sorting algorithms: Quicksort, Selection Sort, Bubble Sort, Merge Sort

I got the inspiration to do this by watching Clément Mihailescu's wonderful video on the same topic(https://www.youtube.com/watch?v=pFXYym4Wbkc). Although he made the thing as a web app using JavaScript, Html and CSS but I not being that familiar with JS, did the thing entirely in C++ all by myself.
 
Please feel free to use the code and tinker and play around...

How to run the code?
->Install OpenGL Library. Then Run the Command in Terminal :- g++ sort_viz.cpp -lGL -lGLU -lglut
