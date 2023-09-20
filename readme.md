# Setup - Week 0

### Logistics

There will be weekly meetings, both online and in person. The schedule is TBD and announced on Discord.

### Prerequisites

We develop our code on linux, and the setup is consistent if you are using linux. 

- The recommended option is dual booting, a tutorial to do so can be found here:
  [How to Dual Boot Any Linux Distribution With Windows – and Get Rid of It When You Need To](https://www.freecodecamp.org/news/how-to-dual-boot-any-linux-distribution-with-windows/)

- It is also possible to complete the following steps on Windows or Mac, however they are less documented and are more likely to sporadically stop working. 

If you would like to test on an actual board, you can buy one for like 15 bucks [here](https://www.mouser.com/ProductDetail/STMicroelectronics/NUCLEO-F446RE?qs=PRtH0mD6DWYnuBoPSlbRCA%3D%3D), else you can run example code in the [ARM mbed Simulator](http://195.130.59.221/). One thing to keep in mind with the simulator is that this is an older version of mbed. While most things are the same, sleep commands and other timing, threading, interrupt related things may be different in syntax when you transition to a real board.

### Setup steps

If you will be using the simulator, there is no setup. You can run code [here](https://www.mouser.com/ProductDetail/STMicroelectronics/NUCLEO-F446RE?qs=PRtH0mD6DWYnuBoPSlbRCA%3D%3D).

If you will be using a board then follow the steps on the [TR-mbed readme](https://github.com/Triton-Robotics/TR-mbed/blob/main/README.md).

### Testing your setup

The most you can do without a physical board to test your setup is to build a blinky and see if it compiles. All the rest of our training program, can be done on the online simulator. However, it is highly recommended you use a board if you have one.

# Assignment

For Week 0 you have to turn in a `.bin` or .`elf` file from the first build of the code. Build a basic blinky or anything you want and submit the bin or elf file. Make sure to also read our [coding style guide](https://github.com/Triton-Robotics/TR-mbed/wiki/Very-Short-Coding-Style-Guide). While you probably won't need all of it now, you definitely will once you become and embedded member.

If you have trouble with setup, compilation, or anything else, contact us on Discord `@Embedded TA`.
