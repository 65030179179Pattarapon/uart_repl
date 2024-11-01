PS D:\ESP32_Koson\uart_repl> & set IDF_PATH='C:\Users\Admin\esp\v5.3.1\esp-idf'
PS D:\ESP32_Koson\uart_repl> & 'C:\Users\Admin\.espressif\python_env\idf5.3_py3.11_env\Scripts\python.exe' 'C:\Users\Admin\esp\v5.3.1\esp-idf\tools\idf_monitor.py' -p COM3 -b 115200 --toolchain-prefix xtensa-esp32-elf- --target esp32 'd:\ESP32_Koson\uart_repl\build\uart_repl.elf'
--- WARNING: GDB cannot open serial ports accessed as COMx
--- Using \\.\COM3 instead...
--- esp-idf-monitor 1.4.0 on \\.\COM3 115200 ---
--- Quit: Ctrl+] | Menu: Ctrl+T | Help: Ctrl+T followed by Ctrl+H ---
ets Jun  8 2016 00:22:57

rst:0x1 (POWERON_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:7176
load:0x40078000,len:15564
ho 0 tail 12 room 4
load:0x40080400,len:4
0x40080400: _init at ??:?

load:0x40080404,len:3904
entry 0x40080640
I (31) boot: ESP-IDF v5.3.1 2nd stage bootloader
I (31) boot: compile time Nov  1 2024 14:16:48
I (31) boot: Multicore bootloader
I (35) boot: chip revision: v1.0
I (39) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (77) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00100000
I (92) boot: End of partition table
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=0bc84h ( 48260) map
I (121) esp_image: segment 1: paddr=0001bcac vaddr=3ffb0000 size=02394h (  9108) load
I (124) esp_image: segment 2: paddr=0001e048 vaddr=40080000 size=01fd0h (  8144) load
I (130) esp_image: segment 3: paddr=00020020 vaddr=400d0020 size=23a14h (145940) map
I (185) esp_image: segment 4: paddr=00043a3c vaddr=40081fd0 size=0bacch ( 47820) load
I (211) boot: Loaded app from partition at offset 0x10000
I (211) boot: Disabling RNG early entropy source...
I (223) cpu_start: Multicore app
I (231) cpu_start: Pro cpu start user code
I (231) cpu_start: cpu freq: 160000000 Hz
I (231) app_init: Application information:
I (234) app_init: Project name:     uart_repl
I (239) app_init: App version:      1
I (244) app_init: Compile time:     Nov  1 2024 14:16:24
I (250) app_init: ELF file SHA256:  457277ef7...
I (255) app_init: ESP-IDF:          v5.3.1
I (260) efuse_init: Min chip rev:     v0.0
I (264) efuse_init: Max chip rev:     v3.99
I (269) efuse_init: Chip rev:         v1.0
I (275) heap_init: Initializing. RAM available for dynamic allocation:
I (282) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (288) heap_init: At 3FFB30A8 len 0002CF58 (179 KiB): DRAM
I (294) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (300) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (307) heap_init: At 4008DA9C len 00012564 (73 KiB): IRAM
I (314) spi_flash: detected chip: generic
I (317) spi_flash: flash io: dio
W (321) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (335) main_task: Started on CPU0
I (345) main_task: Calling app_main()

Type 'help' to get the list of commands.
Use UP/DOWN arrows to navigate through command history.
Press TAB when typing command name to auto-complete.

Your terminal application does not support escape sequences.

Line editing and history features are disabled.

On Windows, try using Putty instead.
repl > [0;32mI (855) main_task: Returned from app_main()[0m
Unrecognized command
repl >
repl > consoletest
This is an example string, if you can read this, the example is a success!
repl > led pin 16 on
number of argc = 4
Unrecognized command
Unrecognized command
repl >
repl > consoletest
This is an example string, if you can read this, the example is a success!
repl > led pin 16 on
number of argc = 4
Parameters:
No:0, led
No:1, pin
No:2, 16
No:3, on
LED number = 0
LED number = 0
repl >