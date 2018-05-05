# SIM800x Component for PSoC4, PSoC5LP and PSoC6

The SIM800x component is beinig developed as a personal project, it surely can be improved, pull request are always welcome!.


## How to use this component on your PSoC project?

You can directly clone this repo inside your project directory and update it as you want. After that you have to include it into your project dependencies.

If you want you can also include this repo as a git submodule.

## Coding style

The code style in the v2.0 will be similar to the [Linux kernel coding style](https://www.kernel.org/doc/html/v4.10/process/coding-style.html), for this the tool clang-format is used, the repo contains the .clang-format file.

The SIM800x modules have several functionalities, SMS, GPRS, TCPIP, etc.
Each functionality have a related couple of files, for example:
- SIM800x_SMS.h
- SIM800x_SMS.c

All the functions related to SMS start with SIM800x_SMS_x where x represent
the name of the function, this applies for all the functionalities.
