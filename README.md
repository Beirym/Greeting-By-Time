# Greeting-By-Time
Generating a greeting message for a specific time of day depending on the current hour.

# Instalation

    pip install greeting_by_time

# Libraries

The list of libraries that were used to run the parser

    datetime
    translated
    
# How it works

5 variables are passed to the function - morning, day, evening, night and lang, the first 4 of which are the time frames for greeting into which tuples containing 2 numbers are passed - the first is the beginning and the second is the end (not taking it into account) of the time interval. The fifth variable is the language in which the greeting will be displayed. There are 15 languages available for output, all of them can be viewed in the "translated" module ( https://github.com/Beirym/Translated ).
    
    
