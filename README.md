## Comp 304 - Project 1: Shelldon

**Team Member 1:** Alper Toygar - 60105

**Team Member 2:** Cüneyt Emre Yavuz - 54347

### How do i compile and run the project?

To compile, run command ```make``` in terminal then run from the out file using ```./out/shelldon```

### Part 3

**birdakika**

To run the command ```birdakika```, mpg321 package should be installed. To install the package, run command:
```apt install mpg321```.

**Custom Command**

As the custom command, we implemented the ```pomodoro``` comment. To execute ```pomodoro```, run command:
```pomodoro [NUMBER]```.
Number is how many pomodoro cycles you would like to generate.

Further information for pomodoro, please visit [this page](http://www.wikizeroo.net/index.php?q=aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvUG9tb2Rvcm9fVGVjaG5pcXVl).

### Part 4

To check the output generated by your kernel module use command: ```sudo dmesg | cat```. Note that you can also use commands like tail, less instead of cat to display the kernel log.