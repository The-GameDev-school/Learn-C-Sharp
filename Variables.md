المستوى 0

Variables

-------------------- Level 0 --------------------

- What is a variable:

A variable is a container of value of a specific data type.

- How to write a variable:

A variable is made of a data type, followed by a name for the variable, variable names are all small letters if it’s one word, if more than one word then we make the other word’s first letter capital.

A variable name cannot start with a number, and it can’t have characters neither a space.

Having two variables with the same name isn’t allowed, because the program will not know which one of them you want to use.

int is a data type which we will use for our example, int data type are numbers with no decimals

```cs

Int applesOnTheTree;

```

- Variables default value:

When making a variable, it starts with a default value, and each data type has it’s starting value, numbers data always have a starting value of 0, although we can give a number a different default value of our choice. We’ll use our previous example

```cs

int apples = 25; ```

- Using a variable:

When we want to use a variable’s value, we just call it by its name, using a variable value is called “Reading”.

```cs

Print (apples);

```

The variable value can be changed without saving the changes to the variable itself

```cs

Print (apples + 4);

``` this will print 29, but the variables value will remain 25.

- Saving Value to a variable:

Saving a value to a variable is called “Writing”, it can be done by writing the variable’s name, after it an equal sign (=), then the value you want to assign to the variable.

```cs

int apples;

apples = 10;

apples = 4;

```

-------------------- Level 1 --------------------

-------------------- Level 2 --------------------

- Saving Value to a variable:

A chain of assigning can be made by putting variables and an equal sign (=) after them multiple times, then ending it with a value in one line.

```cs apples, oranges, bananas;

apples = oranges = bananas = 7; ```

Here the program will start from the end of the line and will start assigning values accordingly, so the bananas will get the value first, then oranges, the apples, the assigning process will be as follows, the bananas will be returned after assigning the seven to it, then oranges will be returned after assigning bananas to it, then apples will be returned after assigning oranges to it, you may write it like follows to make it easier to understand ```cs

apples, oranges, bananas;

(apples = (oranges = (bananas = 7) ) );

// or like follows

bananas = 7;

oranges = bananas;

apples = oranges;

```

- Casting:

“Casting” means changing the data type of a value to another type, and the value will change accordingly if needed.

```cs

int apples;

apples = (int)22.1;

```

The apples variable here will have a value of 22, because cannot have decimals, and when we cast a float to int, the number gets rounded to the nearest number.

- local variable:

Local variables are temporary variables created inside a container that cannot be accessed by anywhere other than its own container, and it’ll be destroyed when its container is done working.

Local variables can have the same name as global ones and they will override them, so that they’re used instead, naming a local variable just like a global variable won’t gain it it’s value.

```cs

void DoingSomething()

{

Int apples = 4;

}

```

-------------------- Level 3 --------------------

-------------------- Level 4 --------------------

- Operators:

§ +

Returns the result of adding the value before and after as a new value

§ -

Returns the result of subtracting the value after of the one before as a new value

§ *

Returns the result of multiplying the value before and after as a new value

§ /

Returns the result of dividing the value before by the one after as a new value

§ =

Returns the variable before after assigning the value after to it

§ !

Returns a flipped value of the bool after

§ ==

Returns true if the values before and after are equal

§ !=

Returns true if the values before and after are not equal

§ >

Returns true if the value before is greater than the one after

§ >=

Returns true if the value before is greater or equal to the one after

§ <

Returns true if the value after is greater than the one before

§ <=

Returns true if the value after is greater or equal to the one before

§ %

Returns the reminder of diving the value before by the one after

§ ;

Ends the line

§ “”

Holds a string between

§ ‘’

Holds a character between

§ //

Turns everything on this line to a comment

§ ||

Returns true if at least one of the bools before and after is true

§ &&

Returns true if both of the bools before and after are true

§ []

Used to access an element by sending an element inside it

§ Signs left [~, \, {}, (), ^, $, @, #, ?, ??, :]

- Returning value:

It's the value replaced with the existing code after using it
