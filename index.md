---
layout: lesson
title: List Comprehension
---
List comprehension is a concise way to construct lists. 

> ## Prerequisites {.prereq}
> loops
> 
> lists

## Topics

1.  [The Basic Parts](01-slug.html)

List comprehensions are a concise way to create lists. 

Let's create a list of colour names in lowercase letters.

~~~ {.python}
lowerlist = ['blue', 'green', 'yellow', 'black', 'red'] 
~~~

the 'upper' method will convert the letters to uppercase.

~~~ {.python}
upperlist = []
for colour in lowerlist:
    upperlist.append(colour.upper())
~~~    

~~~{.python}    
print(upperlist)
~~~

~~~ {.output}
['BLUE', 'GREEN', 'YELLOW', 'BLACK', 'RED']
~~~

A list comprehension to do the same task would be

~~~ {.python}
upperlist = [colour.upper() for colour in lowerlist]
~~~

~~~{.python}
print(upperlist)
~~~

~~~ {.output}
['BLUE', 'GREEN', 'YELLOW', 'BLACK', 'RED']
~~~

2.  [Greater complexity](02-slug.html)

3.  [When to stop](03-slug.html)

## Other Resources

*   [Reference](reference.html)
*   [Discussion](discussion.html)
*   [Instructor's Guide](instructors.html)