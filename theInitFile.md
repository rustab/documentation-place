# The init file.
## So you want to create a python package? 
When defining a python package, many references mention that it is necessary to include the notorious ```__init__.py``` file. 
What is this file?

- Lets assume that you have a package called ```cool_stuff```.
- Lets also assume that the package is structured as:
    ```
    cool_stuff
    ├── __init__.py
    ├── module1.py
    ├── module2.py
    └── module3.py
    ```

So  

Now lets assume that we create a script where one of the first lines of code is:
```python
1   import cool_stuff
```


