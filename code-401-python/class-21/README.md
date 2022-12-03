# Read 21

## DJANGO FORMS


### What are Django Forms?
>It is a class which is used to create an HTML form by using the Model. It is an efficient way to create a form without writing HTML code. Django automatically does it for us to reduce the application development time

### How Django Forms work?
>Django's form handling uses all of the same techniques that we learned about in previous tutorials (for displaying information about our models): the view gets a request, performs any actions required including reading data from the models, then generates and returns an HTML page

### What is the difference between forms and models in Django?
>The main difference between the two is that in forms that are created from forms. ModelForm , we have to declare which model will be used to create our form. In our Article Form above we have this line " model = models. Article " which basically means we are going to use Article model to create our form.

### What is the main things that django forms do?
> 1: Display the default form the first time it is requested by the user.

> 2: Receive data from a submit request and bind it to the form.

> 3: Clean and validate the data.

> 4: If any data is invalid, re-display the form, this time with any user populated values and error messages for the problem fields.


> 5: If all data is valid, perform required actions (such as save the data, send an email, return the result of a search, upload a file, and so on).


> 6: Once all actions are complete, redirect the user to another page.