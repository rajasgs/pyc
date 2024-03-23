---
layout: page
title: Method Overloading
---

/ [Home](index.md)

# Python Commands


{% highlight js %}
class Calculator:
    # Method to add numbers with variable number of arguments
    def add(self, *args):
        return sum(args)

# Create a Calculator object
calc = Calculator()

# Call the add method with different numbers of arguments
print(calc.add(10, 20))          # Outputs: 30
print(calc.add(10, 20, 30))      # Outputs: 60
print(calc.add(10, 20, 30, 40))  # Outputs: 100
{% endhighlight %}


```
class Greeting:
    def say_hello(self, name=None):
        if name is not None:
            print(f"Hello, {name}!")
        else:
            print("Hello!")

# Create a Greeting object
greet = Greeting()

# Call say_hello with different signatures
greet.say_hello()            # Outputs: Hello!
greet.say_hello(name="Alex") # Outputs: Hello, Alex!
```


