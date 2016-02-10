# LINX-Simulation
Repo for testing LabVIEW MakerHub LINX library on Proteus. The repo has all files except the serial port emulator.

# Requirements
- LabVIEW 2015 or above.
- Proteus ISIS 8.4 SP0 or higher
- Virtual com port. Here is a [freeware tool] (http://freevirtualserialports.com)

# Projects included
1. Digital I/O: Testing Digital Input and Output.
2. Servo : Testing Servo library.
3. Oven : Testing analog input and digital output with Oven plant on Proteus.

# Note:
You may confront **timeout error** if you choose low timedelay on LabVIEW side. Also make sure you overrdide Baudrate of LINX to be fixed at 9600 kbps
