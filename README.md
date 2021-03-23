# Example of use Pointers

The present task is intended to demonstrate a concrete application example for the use of pointers by simple means and low programming effort.

## Preparation

Create a programme that functions as an interactive table of contents. In this task, users should be able to enter the chapter number of a (fictitious) book to get the page number of this chapter displayed. A somewhat more realistic task could be to look up a telephone number in an address directory or to find the purchase price of a product with a known article number.

After starting, the programme should be available for information until it is terminated by entering an appropriate code. In the following screenshot, the number 0 is used for this purpose.

The number of chapters and the corresponding page numbers are not relevant for the implementation of this task. Choose some fictitious page numbers on your own (why not the smallest prime numbers in each hundreds space?). The information on the existing chapters and associated page numbers should be stored in the programme as constant values.

For reading the user input and for the intermediate storage or output of the relevant information, pointers or corresponding operators (e.g. & and *) should be used where possible (and sensible).

The code block below can be used as an aid and/or inspiration for working on this task.

```none
Table of contents
********************

-1- Chapter 1
-2- Chapter 2
-3- Chapter 3
-4- Chapter 4
-0- EXIT

Input : 1

You'll find chapter 1 on page 1

Table of contents
********************

-1- Chapter 1
-2- Chapter 2
-3- Chapter 3
-4- Chapter 4
-0- EXIT

Input :
```

## Contributing

This is a personal learning project for me. Please feel free to fork this repo. Pull request to submit more programs.

## Feedback

If you find any bug or have any suggestion, please do file issues. I am graceful for any feedback and will do my best to improve this package.

## License

[MIT](LICENSE) © 2020 Ioannis Christodoulakis
