# Deep Learning and the Game of Go - Clojure implementation

A go board game implementation.

Based on the great book:

https://github.com/maxpumperla/deep_learning_and_the_game_of_go

See exercises

https://github.com/danielmarreirosdeoliveira/exercises/blob/master/dlgo/README.md

## Start

```
clojure src/go/go.clj
```

### Create and use a jarfile


Create an empty classes dir and remove the call to -main in go.go

```
user=> (compile 'go.go)
```

Then run 

    java -cp `clj -Spath` go.go

### Test

    $ clj -A test
