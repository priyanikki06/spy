**Strategy**
- Flow from class to class (GIST TO GIST) -> Code addition, Code refactor

- Flow from slide to slide -> Jumping to IDE, In-Class exercises

- What concept to exclude?

- How to introduce or make them feel the need of a concept through project design?

- Examples -> Analogy, Visualization

- Fun -> Meme/Gif


Slides = Outlining in this Readme + Gist

variables -> lists -> dictionaries -> classes



Pending Python Concepts

- String indices, splice, split

- Tuple, Difference between tuple and list




**Class Outlining**


**Class Two - Greet the spy**

   # GIST - https://gist.github.com/avmain/803013991f4d7cc0f7888c4fbc0526c6
   # Greeting message
    - String basics -> single, double quotes - Done
    - Print a line, escape characters - Done
    - Get user name from terminal and put it in a variable - Done
    - Include Comments - Done
    - Simple string concatenation - Done
    - Explain variables - Done
    - Explain variable re-assignment - Done
    - Explain how strings are stored,  Introduction to len() - Done


**Class Three - Create your spy personality**

    # GIST - https://gist.github.com/avmain/adef8cbecbda974e16b43d764d844561

    # Concepts: indentation in python, if, elif, else, variables, simple string concatenation

    - Check for name to be not zero characters, Conditionals are introduced, Indentation in python is introduced
    - Empty variables declared, introduction to Null, variables reassignment enforced
    - Get age of user. Introduction to int. Introduction to type() and int() methods.
    - Check for it to be not negative, re-introduction to conditionals, white spaces in python
    - Accept user’s height. If he is tall for his age print an appropriate message. Conditions reinforced
    - Set Is Online to False initially, after all data validations are done, set it to be True, Explain True and False here




**Class Four - A spy has many choices**

    # Gist - https://gist.github.com/avmain/d33eec8b7f83297fae891025c9a1b466

    # String formatting in python -> 15 minutes
        - %s, %d, %f, %.2f

    # Importing Stuff -> 30 minutes
        - Cumbersome to keep adding the details
        - Let’s move user details to a helper file.
          import from this file from now on (file import and variable import introduced)
        - Various ways to import

    # Introducing Functions -> 30 minutes
        - What if we want to use different details?
        - Take a choice and add else condition
        - Introduce functions

    # Options Menu - While loop -> 10 minutes
        - While loop, reinforce raw input, int, conditionals. Concept of a loop introduced.

    Extras:
        - Named parameters in python methods
        - Default parameter values in python
        - Args and Kwargs in python





**Class Five - A spy has few friends**


    # Gist - https://gist.github.com/avmain/7d2a248f849c301053d2f22cde0a67b1

    # Concept Introduced: lists, for loops

    # Add a status update - For loop + List -> 45 minutes
        - Print current status message if it exists otherwise print an appropriate message
        - Make a choice of whether you want an existing message or a new one
        - For new status check length, add it to existing list of messages, set it to current message
        - For older status print status messages to choose from, for loop
        - Choose from the list
        - Check if index even exists
        - Set it to current status

    # Status Message Refactor - 10 minutes
        - Wrap the status update into a method (Slide + Code)
        - Pass the current status as an input (Slide + Code)
        - Add updated_status_message (Slide + Code)
        - return the same (Slide + Code)


    # User friends - Functions, loops, lists reinforced - 30 minutes
      - Start with one variable for each friend for each attribute. (Slide)
      - This is a mess, too many variables to keep track of (Slide)
      - Let us use a list (Slide)
      - Declare lists of friends attributes (Slide + Code)
      - Create function add_friend, because better to wrap this functionality (Slide + Code)
      - Accept a new friend using this function only if conditions are met (Slide + Code)
      - Make it return a value (Slide + Code)

    Extras:
      - List comprehension
      - List methods in Python Docs




**Class Six - This is getting messy**

      # Gist - https://gist.github.com/avmain/75e42b26eff81345257dbfa72a5dad51

      # Concepts Covered: Dictionaries, Virtual Env

      # Solving for multiple lists through dictionaries - 50 minutes
      - Let us look at our spy details, these are littered across variables
        won't it be easier to contain them? like a list of words in
        a dictionary? Introduce Dictionary (Slide)
            - Update spy_details (Slide + Code)
            - Update import statement in main.py (Slide + Code)
            - Update code everywhere in main.py
              according to this -> Talk about refactoring -> (Slide + Code)

      # Send a secret message -

          - Choose a friend first, for loop reinforced.
          - This is cumbersome, let’s introduce dictionary list (Slide)
          - Dictionary List
          - Let’s update the older code, Cover Key Error While doing this

      # Virtual Env
          - Why?
          - Pip
          - Installation

      Extras:
        - Dict methods in python docs, iteritems()

**Class Seven - Send and receive a secret message**

    # Gist - https://gist.github.com/avmain/a328377e19e617d8b92115b2dbe37174
     
    # Dictionaries + Lists, Date time, Strftime, Steganography

    # Importing friends from the other file

    # Send and save a secret message
      - Have friend selection as a function
      - Add a chats key
      - Give path to the image, and the text message

    # Date time introduced.
      - Cover various functions
      - Cover strftime

    # Receive and save a secret message
      - Give path to image
      - Write chat message to friend’s chat key in dictionary.

    # Extras:
      - date time docs in python docs



**Class Eight - A spy has his own class**

    # Gist - https://gist.github.com/avmain/956d13665f3ee4d20da42f61399be307

    # Classes

    # Print Chat History
    - should contain timestamp, sender's name and message

    # Solving for repeated blueprints of the spy object
    - Let's create a spy class
    - Using the spy class refactor the entire codebase

