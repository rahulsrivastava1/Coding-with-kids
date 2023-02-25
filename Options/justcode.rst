Just Code 
=========

Key Goals
---------

Options
-------

Scratch
~~~~~~~

KidsRuby
~~~~~~~~

Python
~~~~~~

Here is some code:

.. code-block:: python3

    # Program to sort alphabetically the words form a string provided by the user

    my_str = "Hello this Is an Example With cased letters"

    # To take input from the user
    #my_str = input("Enter a string: ")

    # breakdown the string into a list of words
    words = [word.lower() for word in my_str.split()]

    # sort the list
    words.sort()

    # display the sorted words

    print("The sorted words are:")
    for word in words:
        print(word)


And here is some C# code just in case
you wanted to see it::

    namespace CSharpTutorials
    {
        class Program
        {
            static void Main(string[] args)
            {
                string message = "Hello World!!";
                Console.WriteLine(message);
            }
        }
    }

Hopscotch
~~~~~~~~~