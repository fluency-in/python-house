# Python: House

Write a program that outputs the nursery rhyme 'This is the House that Jack Built'.

> [The] process of placing a phrase of clause within another phrase of
> clause is called embedding. It is through the processes of recursion
> and embedding that we are able to take a finite number of forms (words
> and phrases) and construct an infinite number of expressions.
> Furthermore, embedding also allows us to construct an infinitely long
> structure, in theory anyway.

- [papyr.com](http://papyr.com/hypertextbooks/grammar/ph_noun.htm)


The nursery rhyme reads as follows:

```plain
This is the house that Jack built.

This is the malt
that lay in the house that Jack built.

This is the rat
that ate the malt
that lay in the house that Jack built.

This is the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the man all tattered and torn
that kissed the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the priest all shaven and shorn
that married the man all tattered and torn
that kissed the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the rooster that crowed in the morn
that woke the priest all shaven and shorn
that married the man all tattered and torn
that kissed the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the farmer sowing his corn
that kept the rooster that crowed in the morn
that woke the priest all shaven and shorn
that married the man all tattered and torn
that kissed the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the horse and the hound and the horn
that belonged to the farmer sowing his corn
that kept the rooster that crowed in the morn
that woke the priest all shaven and shorn
that married the man all tattered and torn
that kissed the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.
```

To run a test file, pass it as an argument to the `python` command:

    python hello_world_test.py

If you want to stop the tests after the first failure, then you can use the pytest library.

Install pytest with pip:

    pip install pytest

Run the tests with the `py.test` command using the `-x` flag to exit after the first failure.

    py.test -x hello_world_test.py

## Source

British nursery rhyme [http://en.wikipedia.org/wiki/This_Is_The_House_That_Jack_Built](http://en.wikipedia.org/wiki/This_Is_The_House_That_Jack_Built)

This exercise is from the [Python][python] track on [Exercism][exercism]

[exercism]: http://exercism.io
[python]: http://exercism.io/languages/python



