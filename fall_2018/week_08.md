## Last Week's Accomplishments

Last week I worked on refactoring the error system to follow the model view controller design pattern that we 
are using as well as have a better understanding of the control flow of that subsystem. 

## This Week's Plan

I want to continue working on the refactor that I mentioned above: I was unable to complete it because of the blockers
that I will specify next.

## Anything Blocking?

The design that we are using has a static Backend class which is in charge of backend operations such as connecting to
the server and processing information. That is the best place to put the error system in terms of logic but since it is a static
class I am struggling to implement it. I am trying to create an observable variable that calls the error logic when the variable
changes but I am unable to do this on a static class from what I can tell so far.

## Notes

N/A
