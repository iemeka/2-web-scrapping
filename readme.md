### web scrapping #2

Using clearly written python code:
- Colors were extracted from the html file `python_class_test.html` using regular expression
- The data extracted was stored in a dictionary using color name as key and their frequency as values
    Using pandas:
    - The mean color was determined
    - The mode color was determined
    - The median color was determined
    - Variance of the color was determined
    - If a color was chosen at random, the probability of selecting a red color was determined
- The colors and their frequencies were stored in a postgresql database using PostgreSQL database adapter for Python
- Finally a program to sum the first 50 fibonacci sequence