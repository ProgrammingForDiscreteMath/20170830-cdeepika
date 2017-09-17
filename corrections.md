*. For problem 1, the correct error is ``IndexError``.
*. For problem 2, you don't need ``type(l) is int or type(l) is float``. If ``l`` cannot be added to ``s``, then ``TypeError`` is raised. Under the except clause, you need to just ``pass``.

I am not sure that you have understood the try-except construction. We can discuss it later if you like.

Score: 4/10