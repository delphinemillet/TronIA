# TronIA
Google AI Challenge 2010

The detail of the project can be found [Here](http://tron.aichallenge.org)

### Compiling and running

Just run the following command to compile the C++ starter package.

```
make
```

To start the IA, select the engine with :

```
java -jar engine/Tron.jar
```

Next, select the map in the maps folder : 

```
java -jar engine/Tron.jar maps/empty-room.txt
```

Then the first IA (here a cpp compiled one) :

```
java -jar engine/Tron.jar maps/empty-room.txt "./MyTronBot"
```

And finally the second IA (here a java one in the example_bots folder) :

```
java -jar engine/Tron.jar maps/empty-room.txt "./MyTronBot" "java -jar example_bots/RandomBot.jar"
```

Enjoy !