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
## 1.1
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

## 1.2
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


## 1.3
* Variables and types
* mouseX and mouseY, pmouseX, pmouseY
* mouse and keyboard events
* writing to the console using print and println
> ## Assignments
> Create a set of eyes that respond to the mouse position, mouse click event, and keyboard event. something as simple as this -> [cartoon eyes](https://www.google.com/search?q=cartoon+eyes+clipart&tbm=isch&ved=2ahUKEwiV7Kup3qnuAhUb_qwKHaOeCQEQ2-cCegQIABAA&oq=cartoon+eyes+clipart&gs_lcp=CgNpbWcQAzIFCAAQsQMyAggAMgIIADICCAAyAggAMgIIADICCAAyAggAMgYIABAFEB4yBggAEAUQHjoHCAAQsQMQQzoECAAQQ1CdNFimPWD2PWgAcAB4AIABZIgBtQSSAQM2LjGYAQCgAQGqAQtnd3Mtd2l6LWltZ8ABAQ&sclient=img&ei=87kHYNWmO5v8swWjvaYI&bih=725&biw=1392) 
> 
> Watch this lecture/talk by Zach Lieberman: [Youtube link here](https://www.youtube.com/watch?v=bmztlO9_Wvo)

## 1.4
* math with integers and floats
* Booleans
* Logic operators
* Conditionals (if/else if/ else)
* || &&
* incrementing variables over time within the draw function
> ## Assignments:
> Recreate the classic "mystify" screensaver but with your own twist. [See it in action here](https://www.youtube.com/watch?v=FPfMkEgi2qI)
>
>Reading Assignment TBD

## 1.5
* Focusing on color in depth
* opacity
* hex values
* hsb vs rgba
* map function
* frameRate, frameCount
* Introduce project 1
> ## Assignments:
> Brainstorm and sketch out an idea for project 1
> 
> Reading Assignment TBD


# Module 2
## 2.1
* Transformations
* PushMatrix, popMatrix
* For loops
* Migrating to p5.js

.... The rest is coming soon





