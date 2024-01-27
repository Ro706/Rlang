# R Programming Language

R is a programming language and software environment for statistical computing and graphics. It is widely used among statisticians and data miners for developing statistical software and data analysis.

## Features of R

- **Statistical Computing**: R is often used for statistical computing, data analysis, and data visualization.
- **Graphics**: R has strong graphics capabilities, making it a popular choice for creating high-quality plots, charts, and other visualizations.
- **Open Source**: R is open-source, which means it's free to use and modify. It's also cross-platform, so it can run on various operating systems like Windows, Linux, and MacOS.
- **Community**: R has a large and active community of users and developers, which contributes to its robustness and wide range of available packages for various statistical techniques, graphical devices, data manipulation tools, and import/export capabilities.

## Example of R Code

Here's a simple example of R code that prints "Hello, World!" to the console:

```r
print("Hello, World!")
```
# Declaring Variables in R

In R, a variable is a named space in the memory, used for storing data values. Here are some key points about variables in R:

- **Dynamically Typed**: R is a dynamically typed language, which means variables take the data type of the R-object assigned to them.
- **Assignment**: Variables in R can be assigned in three ways:
    * Using equal operator: `variable_name = value`
    * Using the leftward operator: `variable_name <- value`
    * Using the rightward operator: `value -> variable_name`
- **Naming Rules**:
    * A valid variable name consists of a combination of alphabets, numbers, dot (.), and underscore (_) characters.
    * Variables can start with alphabets or dot characters, but not with numbers or underscore.
    * If a variable starts with a dot, the next thing after the dot cannot be a number.
    * The variable name should not be a reserved keyword in R.

## Example of Declaring Variables in R

Here's an example of declaring variables in R:

```r
var1 = "hello"  # Using equal operator
print(var1)

var2 <- "hello"  # Using leftward operator
print(var2)

"hello" -> var3  # Using rightward operator
print(var3)

```
```r
a <- 4
print(paste("a = ",a))
b <- "rohit"
print(paste("b = ",b))
c <- 12.999090
print(paste("c =",c))
```
