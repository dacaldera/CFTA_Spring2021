## First Day
* Introductions, lets get to know each other
* About this course
* Ice Breakers
* Download and install Processing
  * [download here](https://processing.org/download/)
* Create an account on Open Processing
  * Visit this page [OpenProcessing.org](www.openprocessing.org) and click Join in the corner
> ## Assignments:
> Read this article -> [A Modern Prometheus](https://medium.com/processing-foundation/a-modern-prometheus-59aed94abe85)

# Module 1
## [1.1](https://github.com/dacaldera/CFTA_Spring2021/blob/main/Course%20Materials/Modules/1_1.md)
* Coordinate system
* Simple shapes
* Greyscale and Color
* Syntax, reference, the IDE
* creating a sketch
> ## Assignments:
> Select a painting by [this artist](https://www.google.com/search?q=mondrian&tbm=isch&chips=q:mondrian,g_1:art:RCyBiMoxD-g%3D&hl=en&sa=X&ved=2ahUKEwiIgaSKzanuAhWKY60KHXFPB9EQ4lYoAHoECAEQGQ&biw=1392&bih=725) and recreate it using shapes, line and/or fill/stroke functions.
> 
> Try to recreate this painting by British artist Damien Hirst: [Mickey](http://www.damienhirst.com/mickey) (hint: consider the shape of your canvas by using the size() function) 
> 
> ** Are you up for a challenge? If so, then try to recreate [THIS](https://www.theparisreview.org/blog/wp-content/uploads/2018/10/hilma_af_klint_svanen.jpg) painting by Swedish female artist Hilma Af Klint, and you can learn more about her contribution to abstraction in this article from [The Paris Review](https://www.theparisreview.org/blog/2018/10/12/the-first-abstract-painter-was-a-woman/) (hint: have a look at the reference page for the [arc()](https://processing.org/reference/arc_.html) command)
>
> Read Chapter 1 and 2 from Daniel Shiffmans book "Learning Processing, a beginner's guide" available [HERE](https://github.com/dacaldera/CFTA_Spring2021/blob/main/Course%20Materials/Readings/Learning_Processing_by_Daniel_Shiffman.pdf);

## [1.2](https://github.com/dacaldera/CFTA_Spring2021/blob/main/Course%20Materials/Modules/1_2.md)
* Radians vs degrees, arcs, PI
* Curves - everything you ever wanted to know about them can be read [HERE](https://processing.org/tutorials/curves/)
* Built-in Variables
* The basic setup() and draw() structure
> ## Assignments:
> Choose one of these to recreate: easy: [Smiley](https://www.google.com/search?q=90%27s+smiley&hl=en&sxsrf=ALeKk004_aV8J0w9Lg6KTb-a01KB8tb0aw:1611115594978&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjY6eul0anuAhWFU80KHX0OBxkQ_AUoAXoECBcQAw&biw=1392&bih=725), medium: [Yin Yang](https://www.google.com/search?q=Yin+Yang&tbm=isch&ved=2ahUKEwj1xdGC0qnuAhUWhqwKHbfqDLgQ2-cCegQIABAA&oq=Yin+Yang&gs_lcp=CgNpbWcQAzIHCAAQsQMQQzIECAAQQzIHCAAQsQMQQzIECAAQQzIHCAAQsQMQQzIKCAAQsQMQgwEQQzIICAAQsQMQgwEyBQgAELEDMgcIABCxAxBDMgcIABCxAxBDOgQIIxAnOgIIAFCbqgFYm7UBYNu5AWgAcAB4AIABaIgB8wWSAQM2LjKYAQCgAQGqAQtnd3Mtd2l6LWltZ8ABAQ&sclient=img&ei=Da0HYLWLI5aMsgW31bPACw&bih=725&biw=1392&hl=en), hard: [Peace Sign](https://www.google.com/search?q=peace+sign&tbm=isch&ved=2ahUKEwjI0O3_0anuAhUKb60KHY3tDckQ2-cCegQIABAA&oq=peace+sign&gs_lcp=CgNpbWcQAzIHCAAQsQMQQzIFCAAQsQMyBQgAELEDMgIIADIFCAAQsQMyBQgAELEDMgUIABCxAzIFCAAQsQMyBQgAELEDMgcIABCxAxBDUIciWIciYIUkaABwAHgAgAFgiAFgkgEBMZgBAKABAaoBC2d3cy13aXotaW1nwAEB&sclient=img&ei=B60HYIixLYretQWN27fIDA&bih=725&biw=1392&hl=en)
> 
>void setup(){  } //I only run once at the start of the sketch
>
>void draw(){  } //I run repeatedly in a loop forever
>
>You may create your homework assignments using the code structure or not, the choice is yours. We will be using the code structure moving forward for the rest of the semester.
>
> Create a self portrait using geometric shapes, lines, curves, arcs, colors, fill and stroke, and anything else that we have learned so far. Here is inspiration to get you going but note that you are not limited to only using curves: [Example 1](http://blog.ocad.ca/wordpress/gart1b70-fw201203-01/files/2013/01/selfportrait-processing.png), [Example 2](http://blog.ocad.ca/wordpress/gart1b70-fw201203-01/2013/01/processing-self-portrait-emma-burkeitt/), [Example 3](https://enginayaz.files.wordpress.com/2011/09/portrait.jpg)
>
>And some famous line drawing portraits [Matisse line drawings](https://www.google.com/search?q=henri+matisse+woman+face+line+drawing&tbm=isch&ved=2ahUKEwiJs4ix1qnuAhUPE6wKHYY9C4gQ2-cCegQIABAA&oq=henri+matisse+woman+face+line+drawing&gs_lcp=CgNpbWcQAzIECCMQJ1CkF1ibGGCwGmgAcAB4AIABY4gBwgGSAQEymAEAoAEBqgELZ3dzLXdpei1pbWfAAQE&sclient=img&ei=oLEHYInjKY-msAWG-6zACA&bih=725&biw=1392&hl=en), [Lennon self portrait](https://www.google.com/search?q=john+lennon+self+portrait+-h&tbm=isch&ved=2ahUKEwjAlar-trvuAhUVFqwKHcSyAXMQ2-cCegQIABAA&oq=john+lennon+self+portrait+-h&gs_lcp=CgNpbWcQA1DZJljZJmDoKmgAcAB4AIABRogBRpIBATGYAQCgAQGqAQtnd3Mtd2l6LWltZ8ABAQ&sclient=img&ei=oAARYMDFBJWssAXE5YaYBw&bih=725&biw=1392)
>


## [1.3](https://github.com/dacaldera/CFTA_Spring2021/blob/main/Course%20Materials/Modules/1_3.md)
* Variables and types
* mouseX and mouseY, pmouseX, pmouseY
* mouse and keyboard events
* writing to the console using print and println
> ## Assignments
>
> Create a bullseye/target graphic like we did in class and follow the prompts below:
```
Example bullseye/target sketch

void setup(){
  size(600,600);
}

void draw(){
 ellipse(width/2, height/2, 90,90);
 ellipse(width/2, height/2, 60,60);
 ellipse(width/2, height/2, 30,30);
}
```
>
> * Declare a set of integer variables for sizing, and modify your code to include the variables so that your graphic's size is adjustable. note: declare the variables at the top of your sketch, assign your variables' values in the setup(){  } function
>
> * Similarly use the mouseX and mouseY variables and modify your code to include them so that your graphic's position follows the mouse. note: you will be *rewriting* your positioning values relative to the mouse cursor (ex line(mouseX-50,mouseY-20, mouseX+60, mouseY+25); )
>
> * Cut and paste your graphic's code into the *void mouseClicked(){  }* callback function, turning it into a stamp. Your graphic should stamp onto the canvas everytime the mouse is clicked. note: explore what happens when you play your sketch with and without the background() command which is located in the draw(){  } function. 
>
> * Alter the size variables from step one using the *void keyPressed(){  }* callback function. If any key on the keyboard is pressed, the size increases by 1. note: how does stroke() adapt to these size changes?  
>
> Watch this lecture/talk by Zach Lieberman: [Youtube link here](https://www.youtube.com/watch?v=bmztlO9_Wvo)

## [1.4](https://github.com/dacaldera/CFTA_Spring2021/blob/main/Course%20Materials/Modules/1_4.md)
* math with integers and floats
* Booleans
* Comparison operators
* Conditional logic (if/else if/ else)
* || &&
* incrementing variables over time within the draw function
> ## Assignments:
> Create a bouncing ball sketch. The ball must bounce around inside of the canvas but not leave the canvas. There are many creative ways to do this. 
>
> When the ball hits a wall, the ball should change direction
>
> When the mouse is clicked, something interesting happens
>
>[HELPER VIDEO TUTORIAL #1](https://www.youtube.com/watch?v=U5cOB3KgFWQ)
>
>[HELPER VIDEO TUTORIAL #2](https://www.youtube.com/watch?v=YIKRXl3wH8Y)
>
> Read this article [This one](https://medium.com/better-programming/heres-what-i-learned-from-30-days-of-creative-coding-a-codevember-retrospective-8c05a8497d24)

## 1.41 Review
* we will spend the day reviewing topics that we have covered so far
* Now is the time to catch up if you are behind
* introduce map function
* Introduce project 1

## [1.5](https://github.com/dacaldera/CFTA_Spring2021/blob/main/Course%20Materials/Modules/1_5.md)
* More about Color
* blend modes
* Alpah (Opacity)
* colorMode() HSB & RGB
* map function review
* More If Statement practice

> ## Assignments:
>
> * Create a simplified character using shapes and lines and color.
>
> * Next, Follow these 3 tutorial videos to add movement to your character by using the arrow keys on the keyboard. 
>
> * * [Tutorial Part 1](https://www.youtube.com/watch?v=77L0eaBgaiI&list=PLlulQ8ha7kMNE2yMWRsIGCdMcbGlVJ_-N&index=3)
>
> * * [Tutorial Part 2](https://www.youtube.com/watch?v=TrKFvrNTSNA&list=PLlulQ8ha7kMNE2yMWRsIGCdMcbGlVJ_-N&index=4)
> 
> * * [Tutorial Part 3](https://www.youtube.com/watch?v=uTw48yJ6aP8&list=PLlulQ8ha7kMNE2yMWRsIGCdMcbGlVJ_-N&index=5)
>
> * Finally, incorporate some of what we learned about color today into the sketch.
> 
> Reading Assignment TBD


# Module 2
## 2.1
* Byte-sized histories
* case-study: generating a digital collage
* PImage - loading images and data folder structure
* toggling a boolean variable
* Arrays[]
* more if-statement practice

> ## Assignment:
>
> * Assignment: Pick one of the three code sketches that we coverend in class, dig some pictures up from the internet and plug them into the sketch, and explore.

## [2.2](https://github.com/dacaldera/CFTA_Spring2021/blob/main/Course%20Materials/Modules/2_2.md)
* For loops
* Transformations
* rotations
* PushMatrix, popMatrix

## [2.3](https://github.com/dacaldera/CFTA_Spring2021/blob/main/Course%20Materials/Modules/2_3.md)
* while loops
* More for loop practice
* PushMatrix, popMatrix and transformations practice

## 2.4 
* While() loops
* nested for loops

## 2.5
* custom functions
* GUI buttons


***

## Project 2 Collage
> Homework for Collage Project
> 
> Make a sketch of a collage idea. You many use pencil and paper, or you may use photoshop. 
>
> Label the sketch with information about what each element will be doing in the collage. 
> 
> Collect the digital assets that you will be using in your collage. Open a new blank processing sketch. Save it to give it a name, and add the data folder to the project directory. Then place your digital assets inside the data folder. 
> 



# Module 3
.... The rest is coming after we are finished with the collage project





