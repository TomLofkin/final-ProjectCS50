# TODO LIST
#### Video Demo:  <https://youtu.be/uhmtXQ07XM4>
#### Description:
While researching what kind of project to make, I came across the concept of using class based views within Python and Djano. 
While function based views are more beginner-friendly and more explicit line-by-line, class based views allowed code to be 
extended using inheritance, frameworks and libraries, allowing the dev to create single sections of parameters that could 
then be linked back to elsewhere in the project, for example wrapping a section of html code so that it inherits the same 
styling from a main html parent file.  
I also wanted to create something using class based views because apps used in a software dev workplace would be more likely 
to use them, so I felt it important to challenge myself to learn them now so as to better prepare myself for using them in a 
workplace scenario in the future. In short, Django provides this library of methods and class that can be called instead of 
writing everything out within a function, so why not learn to use them in order to produce cleaner, reusable code?
In my ‘views.py’ file, I created a series of views that form the basis of the Todo app’s functionality, that is to say, a view 
each to allow a user to: see a list of their to do items, view a single entry in the list, create a new item in the list, update 
an existing list item and to delete an item. At the top of the ‘views.py’ file, you can see where I have imported each of the 
relevant models, as well as the ‘reverse_lazy’ functionality which allows users to be redirected to a specified page, depending 
on a user’s interaction with the app (for example, clicking a button to create a task, and the app redirecting them back to 
their main task list page.) On top of this, lines 9 to 12 show models that I have imported to handle to login, logout and 
registration side of the apps functionality.
