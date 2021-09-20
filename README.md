# Blinky example for the Corstone-300 FVP

Below is a Blinky example which can be run on the [Corstone-300 FVP](https://developer.arm.com/tools-and-software/open-source-software/arm-platforms-software/arm-ecosystem-fvps)

## Simple getting started instructions

### Compile with Arm Compiler

```bash
$ git clone https://github.com/jasonrandrews/Blinky.git
$ cd Blinky
$ cbuild.sh Blinky.Target_1.cprj
```
### Run 
```console
$ ./run.sh
```

### The program output should be:
```console

= Blinky is running =
LED timer interval is set to 1s

```

### To run without the FVP user interface 
```console
$ ./run.sh -f fvp_config.txt 

```
The output will appear in the terminal with No user interface
