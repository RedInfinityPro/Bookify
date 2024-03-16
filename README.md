# Bookify

Bookify is a Java program that simulates a library environment, offering book management and generation features like book creation and triangular random number generator. It's versatile for educational and experimental purposes.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Imports](#Imports)
- [Rating: 6/10](#Rating)

# About

Bookify is a Java program that simulates a library environment, offering book management and generation features. It allows for book creation, generating random titles with varying lengths and characters, and generating triangular random numbers using a triangular distribution. This tool is versatile for educational and experimental purposes, showcasing the essence of book management and statistical randomness.

# Features

Bookify is a versatile Java program that allows users to create books, generate random titles, and use triangular random numbers for modeling uncertainty or variability. Users can input details like title, author, genre, and more to craft fictional worlds and narratives. The program also uses a triangular distribution to generate random numbers, which can be used for various purposes like simulating dice rolls or predicting stock prices. Bookify is also useful for education and experimentation, allowing students to explore book management concepts and researchers to analyze statistical randomness. Overall, Bookify bridges the gap between literary imagination and mathematical exploration, inspiring countless stories and discoveries.

# Imports

Scanner, Random

# Rating

Codes organization and readability, with clear separation of concerns using classes and methods. However, there are improvements to enhance readability, such as more descriptive method and variable names. The usage of `outerInstance` in the `main` method is confusing, and the `generateTriangularRandom` method could benefit from more descriptive variable names.
The program generates a random book title in title case, but its functionality is limited to generating random titles. Adding more features like authors, dates, and contents would enhance the project's completeness.
Error handling is 4/10, with the code lacking error handling mechanisms, such as `maxValue` less than `minValue` and no handling for empty `alphabet` arrays in the `createTitle` method. Efficiency could be improved in certain areas, such as using a `StringBuilder` instead of concatenating strings in a loop. Generating random titles by selecting characters randomly from an alphabet array is straightforward but might not produce realistic titles. Overall, the project demonstrates a good understanding of Java fundamentals and concepts like classes, methods, and random number generation. However, there is room for improvement in readability, error handling, and efficiency.
