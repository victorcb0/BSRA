# BSRA (The Babylonian Square Root Algorithm)
The Babylonian algorithm for calculating the square root is one of the oldest and simplest methods of approximating square roots. The fundamental principle of the algorithm consists in the successive approximation of the square root through an iterative process.

The algorithm starts with an initial estimate of the square root of a given number. This estimate can be any positive value, preferably one as close as possible to the true answer. Then, in each iteration, the algorithm uses a simple formula to improve the current estimate. This formula involves calculating the arithmetic mean between the current estimate and the ratio of the given number to the current estimate. The process is repeated until the absolute difference between the current estimate and the actual response becomes small enough, that is, below some specified error value.

## Form 1 - Calculation Of The Root
The application created in Visual Studio is a practical tool for approximating the square root of a given number using the Babylonian algorithm. The form's intuitive interface allows the user to enter the number for which the square root is desired, as well as the desired error value for the approximation. After the user has provided this information and pressed the "Calculate" button, the application performs the necessary calculations according to the Babylonian algorithm. Thus, the answer obtained - the square root of the given number calculated according to this algorithm and calculated according to the mathematical function integrated in the language - are displayed on the interface, together with the associated error and the number of iterations performed to obtain this approximation. The application is designed to be user-friendly, ensuring a smooth experience for users and providing them with accurate and easy-to-understand results. By combining the logic of the Babylonian Algorithm with the power and versatility of Visual Studio, this application is an efficient solution for calculating the square root, useful in a variety of practical and educational contexts.

![picture alt](https://github.com/victorcb0/BSRA/blob/main/Imagini/Form1.png)

## Form 2 - Testing The Algorithm
The application built in Visual Studio provides an interactive platform for testing and evaluating the Babylonian square root algorithm. The form's intuitive interface allows the user to enter the minimum and maximum values of the range to test the algorithm on, as well as the number of values to perform these tests on. The user can also specify the desired error for the square root calculation. After all this information is entered, the application generates random values in the specified range and applies the Babylonian algorithm to calculate the corresponding square roots.

Once all calculations are completed, the application displays the average error obtained as well as the average number of iterations required for each value generated. This information is essential for evaluating the algorithm's performance and determining its effectiveness in various contexts and for different types of data.

In addition, the application also provides an interactive graph that shows the number of iterations performed against the generated values. This graph visualizes how the Babylonian algorithm converges to the square roots of given numbers and provides an intuitive insight into its real-time performance.

![picture alt](https://github.com/victorcb0/BSRA/blob/main/Imagini/Form2.png)
