Draw a pen-and-paper diagram of all the tables and how they relate to each other

Make your own branch and try to write some rspec tests to get your head around the interaction between models

Fire it up on localhost and try to break it... do stuff like put random numbers into URL params, break their forms, etc. you might wind up catching some bugs

Read the tests! (Hopefully there are some...). If the tests are well-written, they should double as documentation.

Anytime you see a controller that is obtusely-written, thorw a binding.pry in there and inspect the variables

A talk on rails debugging - http://slides.com/deniseyu/rails-debugging#/

Denise Yu


If you’re trying to build a new feature, try and find a similar feature, and trace the execution path from erb, to controller, to model, and back out again.

The REPL (PRY) is also your friend.

Spike