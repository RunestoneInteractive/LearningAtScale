Self-Check Questions
--------------------

Multiple Choice
~~~~~~~~~~~~~~~

.. reveal:: rev1

    .. mchoicemf:: question1_1
       :answer_a: Python
       :answer_b: Java
       :answer_c: C
       :answer_d: ML
       :correct: a
       :feedback_a: Yes, Python is a great language to learn, whether you are a beginner or an experienced programmer.
       :feedback_b: Java is a good object oriented language but it has some details that make it hard for the beginner.
       :feedback_c: C is an imperative programming language that has been around for a long time, but it is not the one that we use.
       :feedback_d: No, ML is a functional programming language.  You can use Python to write functional programs as well.

       What programming language does this site help you to learn?


Multiple Choice Multiple Answer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. reveal:: rev2

    .. mchoicema:: question1_2
       :answer_a: red
       :answer_b: yellow
       :answer_c: black
       :answer_d: green
       :correct: a,b,d
       :feedback_a: Red is a definitely on of the colors.
       :feedback_b: Yes, yellow is correct.
       :feedback_c: Remember the acronym...ROY G BIV.  B stands for blue.
       :feedback_d: Yes, green is one of the colors.

       Which colors might be found in a rainbow? (choose all that are correct)


Fill in the Blank
~~~~~~~~~~~~~~~~~

.. reveal:: rev3

    .. fillintheblank:: baseconvert1
       :correct: \\b31\\b
       :blankid: baseconvert1_ans1

       What is value of 25 expressed as an octal number (base 8) :textfield:`baseconvert1_ans1::mini`



CodeLens Questions
~~~~~~~~~~~~~~~~~~

.. reveal:: rev4

    .. codelens:: codelens_question
        :question: What is the value of tot after the line with the red arrow executes?
        :breakline: 4
        :feedback: Use the global variables box to look at the current values of tot and i.
        :correct: globals.tot

        tot = 0
        prod = 1
        for i in range(10):
           tot = tot + i
           prod = prod * i
       
       
Feedback
~~~~~~~~

A student will see how they answered the question, and a breakdown of how all students in the class answered the question. `Here <http://interactivepython.org/runestone/static/luther150c_fall13/PythonTurtle/helloturtle.html#hello-turtles>`_.  As an instructor you can see how each student answered the question, and how many tries it took.
