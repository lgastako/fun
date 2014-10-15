# fun

A simply functional programming language.

## fun

Hopefully it will be fun to use and fun to create.

I think I'll use instaparse.

## Language Notes

So basically the language will have values.

There will be primitive values (bools, numbers, strings, etc).

It will be a functional language, so it will have functions.  And of course
functions are first class values.

It will be strongly and statically typed.  With eventually HM type inference.

Initially you'll probably have to specify all the types though.

The only built in data structure will be a tuple (2-tuple? n-tuple?) and other
data structures will be built on that.

No inherent nulls, those will be handled via Option, Maybe, Either etc types but
what do we do about simple Lips style lists via tuple-based cons cells.  Wither
None, nil, null, etc.

Maybe tuples are the (only?) magic data structure that can is untyped.  A tuple
contains values, whatever types those values may have.

We could of course imagine wanting a typed tuple, so maybe all tuples have types
but they can be of some top level "Object" type which of course the single
instance of Null or Nil or whatever descends from...

But of course then you could include a Nil anywhere you could include an Object,
and we might want to specify that you have exactly a non-Nil object.

Of course you might want to specify that you have a non-String object or a
non-Integer object too.  Hmm.  Is this where dependent types come in to play?

Can we have Nils in a "class hierarchy" such that our Lispy Cons cells work
without null'ing up the rest of the language?  Do we even need a null/nil type
then?  How do you represent an unknown value then, without SQL-style pain?

Of course we don't really have a class hierarchy, well, or do we?

I guess we need to think about values, classes, generics, etc.

We definitely want to be able to have generic lists with different things in
them.  And algorithms that operate on the generic data structures. without
knowing anything about whats in the structures.

## Examples

x = 42
b = false

y =

## Usage

    make

## License

Copyright © 2014 John Evans
