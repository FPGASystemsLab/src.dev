# src.dev
# Device Interface Collection for FPGA Projects

This repository contains a collection of device interface modules designed for FPGA projects. These modules enable FPGA developers to easily integrate various peripherals and functionalities into their designs. Specifically, these interfaces are particularly suited for projects involving the Eco32 microprocessor and the RingNet NoC (Network on Chip) project, facilitating seamless integration and enhanced capabilities.

## Compatibility

### Eco32 Microprocessor

The modules provided in this repository are designed to be highly compatible with the Eco32 microprocessor project. By incorporating these device interfaces, developers can extend the Eco32's capabilities with additional peripherals such as SD cards, keyboards, VGA outputs, and more. For more information on the Eco32 project, visit [Eco32 Microprocessor on GitHub](https://github.com/FPGASystemsLab/src.eco32_core).

### RingNet NoC Project

Additionally, these modules support the integration with the RingNet NoC project, enabling efficient communication and data transfer within FPGA-based systems. The inclusion of interfaces like UART, SPI, and I2C can significantly enhance the RingNet NoC's functionality and performance. For further details, check out [RingNet NoC Project on GitHub](https://github.com/FPGASystemsLab/src.rbus).

## Modules

- **dev_hdmi_i2c**: HDMI control over I2C interface module.
- **dev_i2c**: Basic I2C interface module for general-purpose I2C communication.
- **dev_keyboard**: Module for interfacing with a standard keyboard.
- **dev_led_sw_push**: Module to control LEDs with push-button switches.
- **dev_sd**: SD card interface module for reading/writing data to SD cards.
- **dev_SPI_flash**: Module for interfacing with SPI flash memory.
- **dev_ts**: Touchscreen interface module for integrating touch functionalities.
- **dev_uart2mem**: UART to memory interface module for direct data storage operations.
- **dev_uart**: Basic UART interface module for serial communication.
- **dev_vga_ddr_XP2**: VGA interface module optimized for DDR on XP2 FPGA boards.
- **dev_vga_spartan61**: VGA interface module for Spartan-6 FPGA boards.
- **dev_vga_v2**: An enhanced version of the VGA interface module.
- **dev_vo**: Video output module for video display functionalities.
- **pwm.v**: Pulse Width Modulation (PWM) module for controlling motor speed, LED brightness, etc.
