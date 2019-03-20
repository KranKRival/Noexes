# Noexes Atmosphere SysModule 

A multi-platform graphical remote debugger for the Nintendo Switch on Atmosphere Custom Firmware.

## Quick Start Guide

### Pre-Requisites

* [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere/releases) on your switch
* [Java 10](https://www.oracle.com/technetwork/java/javase/downloads/jre10-downloads-4417026.html) installed on your PC

### Downloading

Go to Releases Page.

### Copying Files

Extract the downloaded release archive and copy the "0100000000000038" Directory to your SD card "/atmosphere/titles/"

### Running the Client

On most operating systems all you need to do is run the jar file from the release as you would any other programs. If you're having trouble try running the following command (within the directory where you extracted Noexes):

```
java -jar JNoexsClient.jar
```

If you still have problems please double check that you're running at least Java 10 (you can verify this by using the command ``java -version``). If you are feel free to open an issue and I'll try to get back to you ASAP!

### Using the Client

**TODO**


## Building from Source


### Building the Client

**TODO**

### Building the Server

**TODO**


## Client Dependencies

If you're using IntelliJ for building it should automatically download all the dependencies from maven, otherwise 

* [Usb4Java](http://usb4java.org/) - Used for USB communication
* [Gson](https://github.com/google/gson) - Used for serializing various objects to/from JSON
* [ASM](https://asm.ow2.io/) - For optimized pattern searching

## Server Dependencies
* [Libnx](https://github.com/switchbrew/libnx) - Without libnx there would be no homebrew on the switch, especially with what we're trying to do

## License

This project is licensed under GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* L0nk, dcx2 and a bunch of others from the old WiiRd fourms
* roblabla for their near endless help, and for putting up with my inane questions
