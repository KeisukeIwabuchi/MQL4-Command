# MQL4-Command
A module for using the Windows cmd command with MQL4 programming.


## Install
1. Download Command.mqh
2. Save the file to /MQL4/Include/mql4_modules/Command/Command.mqh

## Usage
Load the Command.mqh with #include.  
Execute cmd method.
```cpp
if(!Command::cmd("The command you want to execute.")) {
  Print("Error occured.");
}
```
