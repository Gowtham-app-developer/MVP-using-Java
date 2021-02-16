# MVP-using-Java

## What is MVP?

- It as Model-View-Presenter architecture. 
- View more separated from Model and the Presenter is the mediator between Model and View.
- Easier to create unit tests.

__Model__

- It is business logic and Data State. 
- Getting and manipulating the data, communicates with the presenter, interacts with the database. 
- It doesn't interact with the view.

__View__

- Consists of UI, activity, and fragment. 
- It interacts with the presenter.

__Presenter__

- The Presenter is responsible to act as the middle man between View and Model. 
- It retrieves data from the Model and returns it formatted to the View.
- But unlike the typical MVC, it also decides what happens when you interact with the View.

__Advantages__

-	It makes view dumb so that you can swap the view easily.
-	Reusable of View and Presenter.
-	Code is more readable and maintainable.
-	Easy testing as business logic separated from UI.

__Disadvantages__

- Tight coupling between View and Presenter.
- Huge amount of interfaces for interaction between layers.
- The code size is quite excessive.
