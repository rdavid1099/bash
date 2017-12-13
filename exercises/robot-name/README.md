# Robot Name

Manage robot factory settings.

When robots come off the factory floor, they have no name.

The first time you boot them up, a random name is generated in the format
of two uppercase letters followed by three digits, such as RX837 or BC811.

Every once in a while we need to reset a robot to its factory settings,
which means that their name gets wiped. The next time you ask, it will
respond with a new random name.

The names must be random: they should not follow a predictable sequence.
Random names means a risk of collisions. Your solution must ensure that
every existing robot has a unique name.


In order to make this easier to test, your solution will need to implement a
`Robot.forget` method that clears any shared state that might exist to track
duplicate robot names.

Bonus points if this method does not need to do anything for your solution.

## Source

Modified from [Ruby Exercism](exercism.io/exercises/ruby/robot-name/readme) which was created following a debugging session with Paul Blackwell at gSchool.

## Submitting Incomplete Solutions

It's possible to submit an incomplete solution so you can see how others have completed the exercise.
