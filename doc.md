# Documentation

Documentation on working with the module for generating greetings depending on the current time - "Greeting By Time"

# greeting_by_time

   The main function of the module for generating greetings

   ### Import
```python
from greeting_by_time.greeting_by_time import greeting_by_time
```

  ### Function arguments
  
  **morning, day, evening, night**
  
  Arguments which take two numbers in tuple that are ranges of hours for a certain time of day.
  * the first number is the start point of the range, and the second number is the end of the range ( not including it )

  **lang**
  
  the language ( lang_code ) in which the greeting will be generated.
  * there are 15 languages available, you can view them in the "translated" module.


  ### Example
  
```python
from greeting_by_time.greeting_by_time import greeting_by_time

greeting = greeting_by_time(lang='ru')

print(greeting) # Доброго времени суток
```
  
