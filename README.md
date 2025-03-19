# MFL Platform

## Description

[PlatformIO](https://platformio.org) platform implementation for the GD32F103Rx and GD32F303Rx MCUs using MFL.

## Supported boards

See [boards](https://github.com/bmourit/platform-mfl/tree/main/boards) folder.

* GD32F303RE (Cortex-M4)
* GD32F103RE (Cortex-M3)
* GD32F103RC (Cortex-M3)

Currently only three MCU versions and three boards are supported. Other MCUs and boards may be added in the future if there is interest. The main purpose of this platform is to support building Marlin Firmware for this chip.

## How to use

[Install PlatformIO](https://platformio.org)

The platform can be installed manually using `pio platform install https://github.com/bmourit/platform-mfl.git` on [the CLI](https://docs.platformio.org/en/latest/integration/ide/vscode.html#platformio-core-cli). This is done automatically when compiling one of the example projects. 
