# About
Set of examples how to use [CLion](https://www.jetbrains.com/clion/) with various unsupported compilers using
[Custom Defined Compiler](https://youtrack.jetbrains.com/issue/CPP-9615) feature

## Supported variants so far

* [CMake-Embarcadero-BCC32C](CMake-Embarcadero-BCC32C)
  * Build System: [CMake](https://cmake.org/)
  * Compiler: [Embarcadero Free C Compiler](https://www.embarcadero.com/free-tools/ccompiler)
    * Compiler definition file: [custom-compiler-bcc.yaml](CMake-Embarcadero-BCC32C/custom-compiler-bcc.yaml)
  * Host Platforms: Windows 32bit
  * Target Platform: Windows 32bit
* [CMake-Texas-Instruments-MSP430-CGT](CMake-Texas-Instruments-MSP430-CGT)
  * Build System: [CMake](https://cmake.org/)
  * Compiler: [TI MSP430 CGT compiler](https://www.ti.com/tool/MSP-CGT)
    * Compiler definition file: [custom-compiler-msp430.yaml](CMake-Texas-Instruments-MSP430-CGT/custom-compiler-msp430.yaml)
  * Host Platforms: Windows, Linux, Mac
  * Target Platform: MSP430 MCU
  