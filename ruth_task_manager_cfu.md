
CRUD stands for create, read, update and destroy.

We use set method_override: true to allow us to use _method in the form

the name is going into the task's parameters and pulling out whats associated title (setting it to name)
the value is calling the title method on a ruby object, task.

params is a hash. in the case of this exercise, its a hash that holds a key, and value, another hash with the title and description. It was made this way beause of how we named the input fields in the forms we made, and what we typed into them.

I'm assuming that we need different routes because each command does an entirely different thing, especially in regards to your database. You wouldn't use the same route to do two separate functions on opposite sides of a huge library, so why would that be the case with a computer? It would be inefficient.
