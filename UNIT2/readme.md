# Executive Summary
* Summarize this assignment and the goal of this lab

In week two of IT concepts for programmers we are truly getting into what makes technology what it is, diving into the two main topics of hardware and data representation. One will be expected to understand a range of different aspects of technology. On top of learning about general computer systems (such as RAM or bytes) and the specific applicaition they have as a system, extensive technological jargon will be learned. In this assignment we will be differentiating hardwares, to show we understand. On top of that we will be learning how to go between binary, decimal, and hex (core of computing itself). All of the topics covered in the lab are to describe a detailed first lesson for the basics of how a computer/device works and what essential parts make devices run, along with the processes they entail. 

# Hardware
## Hard Drives and Memory
* What is the difference between latency and transfer rates in the performance of a hard drive?

Latency is the estimated average time for the accessible disk to rotate into position under the head. Simply, it is the average time it takes for a drive to seek for data, getting it so it is accessible to do so. A lower latency increases drive performance. A transfer rate in a drive is the speed that data is transferred from the disk (in MBps). All in all the basic difference between them is that the latency rate is the time for the data to be accessible and the transfer rate is basically the speed of data transfer. Both aid in hard drive performance when at a good speed/rate (usually 100-200 MBps transfer rate, 3-10 ms for latency) 

* How a solid state (SSD) hard drive is different from a traditional hard drive?

A solid state hard drive's main difference from a traditional hard drive is that they both differ in what they use to store and retrieve data. For example, SSDs use flash memory with "electrically eraseable programmable read-only memory" (EEPROM) memory chips while HDDs are not usually only read-only. Traditional hard drives usually have more storage space but on the flip side SSDs are faster, lighter, use less energy, and technically last longer. SSDs are defintely more expensive, and are a better bet if affordable.  

* Why does increasing RAM make the computer run faster?

RAM (random access memory) is the working memory used to load information from storage in a computer. With more RAM the speed that memory is transferred (or processing speed) is increased, resulting in a fast way for the processor to communicate with other computer components. Going further with this, having high RAM means that the processor can handle more tasks and it takes away the need to swap data back and forth to the disk drive. A lot of swappings make a computer slower, so more RAM is more efficient.

* What is the difference between 64 and 32 bit data paths?

One main difference between a 64-bit data path and 32-bit data path is that the 32-bit data path can handle a limited amount of RAM while a 64-bit path can take advantage of much much more. 4 GB is actually the maximum that a 32-bit path can handle, and that is a piece of cake for a 64-bit data processing path. If a CPU has more than 8 GB of RAM and it doesn't have a 64-bit data path processor than half of that memory will not be able to be accessed by the CPU itself. 

## ALU and Control Unit
* Explain the interaction of the control unit and ALU in the CPU

The ALU (arithmetic logic unit) performs arithmetic and logic operations such as addition and subtraction. The control unit (CU) decodes those instructions from the ALU to make the CPU work. The CU basially tells the logic unit how to respond to what has been transferred to the processor. 

## CPU, Input and Output
* Identify how the example addresses each of the components: CPU, Input and Output

I must state that I was not sure about the exact example we needed to use, so I went for describing the relation between the components that are above. The CPU, or central processing unit, is the mastermind behind computer operation. All instructions are processed by the CPU, and the CPU itself usually has more than one processor that performs all calculations since most tasks are very complex. The input and output of a computer are channels for delivering information from the user to the computer and vice versa. In modern days computers use USB ports, microphones, sensors, etc. Input sends information to the CPU for processing into binary and the output displays are calculated and projected onto/through screens, speakers, or printers. The main relational idea betweem them here is: inputing data from the physical world, storing and processing that data through memory and the CPU, and then recieving an output display from that.

## Logic Gates and circuits
* Explain what is meant by a truth table and apply your knowledge to a NAND gate.

A truth table is a logical showing of every input combonation to a logic gate or circuit with the outputs completely depending on the input combonations. Look at it this way, When given an algebraic function you make a table with X and Y, where X is the varying inputs and Y is the output depending on the inputs. Truth table inputs and outputs are solely ones and zeroes. Ones are true and Zeroes are false. In relation to NAND gates the outputs are false only if the inputs are true. For example an output of a 0 will only result if the input is 1. If the input is a 0 than the output will be 1. These combonations accomplish basic operations.

* How does the NAND gate truth table compare to that of an AND gate?

The biggest difference between the NAND truth table and the AND truth table is the input-output relational difference. AND gates have true outputs if any input is also true, and the same goes for if any input is false. For the output to be one, one of the inputs HAS to be one. In NAND gates the output is false if both inputs are true, if there are differences from that the output is true. 

## IEEE - Ethically Aligned Design
* Explain the purpose of IEEE and the importance of ethics in device design

IEEE (Institute of Electrical and Electronics Engineers) is an association that focuses on advancing technology to benefit humanity. This group focuses on the ability of technological innovation to change peoples' lives. On top of actual innovation they also focus on spreading electronics professions to everyone. With this organization technology has massively evolved to appliances and portable devices. Ethics in design are important because it is moral to consider the context of the technological product one is creating. A lot of questions have to be considered. For example, will there be a proper privacy to the client? 

# Data Representation
## Numeric Conversions
* Explain the difference between decimal, binary and hexadecimal numbers

A decimal represents a single number/digit. Decimals can be represented with a subscript of 10 and are composed of a mix of numbers 0-9. It is a base 10 number system.
Binary is a numeric system that only uses two digits, zero or one. Computers mainly operate in binary and do all calculations and storing with it. The digits of binary represent either true (1) or false (0). Binary is a base two number system. Binary is written 8 bits (numbers) at a time.
Hexadecimal is represented by 16 mmixed letters and numbers. Hexadecimal uses the same numbers as decimals do (0-9) but also contains letters A through F. Hex are a base 16 number. Hex is wrtten 4 bits at a time (half a bit).

* Convert the decimal number 211 to binary showing your work (be sure to include your name in your screenshot or scanned file) and save to a file named DecimalConversion and upload to your lab folder.

Screenshot will be uploaded to file but: after work is done, 211 to binary = 11010011

## Hexadecimal color representation
* Convert the binary representation: 10110101 to decimal and save your work to a file named BinaryConversion and upload to the lab folder.

Screenshot will be uploaded to file but: after work is done, 10110101 to decimal = 181

* Explain the representation: #ab00ff using the site: https://www.colorhexa.com/

The hex color #ab00ff's RGB reading is 67.1% red, 0% green and 100% blue. By these percentages you can see that this specific color will be more on the purple/blue side. The fact that the color has a saturation of 100% means it is very deeply pixelated and heavy in intensity. The lightness of 50% confirms the purple/blue theory, and it also shows that the color is not extremely dark or light. This hex color is labeled as NOT web safe. The shade-color variation is a range of purple-blues.

* When considering accessibility in web sites would this color be problematic? Explain what should be considered.

This color would be bordering problematic. First of all you have to consider what the user will be witnessing when looking at a site. If a color is too saturated or intense it could not only be hard on the eyes but it may not show up on all monitors as it should. An important thing to take note of when choosing site hex colors is the ability for that color to be correctly portrayed among multiple coputers. Some computers do not have the RAM capability for more than the normal 216 web-safe color list, and this specific color may surpass the abilities of a few. 

# Conclusion
* Explain what you learnt from this lab

In this lab I got a full introduction to the hardware components of computers and what makes them work. I especially learned a lot about how data is transfered and what components will make that transfer faster. My favorite part of this lab was learning about the different binary/decimal conversions and how those numbers output to display what we see when we look at our screens. 
It is truly mind boggling how I never knew any of this before, but I really do love the intro to what makes a computer work. All in all this lab was very informing! 
