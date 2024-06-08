@AshleyKeliane
Title: Image search algorithm with GoLang

This project was created by me for a school personal project about programming paradigms.

There's a few useless lines of code that i left as comments for my own learning, please do not take too much attention to those as they do not work properly.

The code generates 5 threads (each for the 5 images that should be shown in the output) which are all synced thanks to the waitgroup. 
The histogramChanel created helps them communicate with one another while they are all running at the same time so there's no error or panic inside the program. 
The code therefore finds 5 similar images (out of the image database) to the one entered from the query image (please choose any image from the query image dataset).
