<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Implement a Capitalizer through UART communication that converts lowercase alphabetic characters to uppercase. The design features a UART receiver, a FIFO buffer, and a UART transmitter to handle serial data in a pipelined manner.

## How to test

Send random letters as input. If a letter is lowercase, the system will automatically convert it to uppercase. 

## External hardware

Connect to a UART interface configured at a 9600 baud rate for TX/RX communication.
