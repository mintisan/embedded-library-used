# embedded-library-used

## rtos
- [freeRTOS](https://www.freertos.org/) : 简单够用的 RTOS
- [Zephyr OS](https://github.com/zephyrproject-rtos/zephyr) : 里面什么都有

## event framework
- [lwevt](https://github.com/MaJerle/lwevt) : 适用于【多生产者-单消费者】模型，比如多传感器数据的读取后统一管理

## coroutine
- [protothread](http://dunkels.com/adam/pt/) : 线程中的非阻塞轮询框架

## memory manager
- [lwmem](https://github.com/MaJerle/lwmem) : 可控可调，挺好

## ring buffer
- [lwrb](https://github.com/MaJerle/lwrb) : 适用于传感器数据的读取和发送

## frame packet
- [lwpkt](https://github.com/MaJerle/lwpkt) : 可用于打包传感器数据
- [STCmdP Protocol manager](https://www.st.com/en/embedded-software/x-cube-opus.html)

## printf
- [mpaland/printf](https://github.com/mpaland/printf) : Tiny, fast, non-dependent and fully loaded printf implementation for embedded systems. Extensive test suite passing.
- [eyalroz/printf](https://github.com/eyalroz/printf) : forked [mpaland/printf] Tiny, fast(ish), self-contained and fully loaded printf, sprinf etc. implementation, mainly for embedded systems
  - [Standalone printf/sprintf formatted printing function library](https://modm.io/reference/module/modm-printf/)
- [charlesnicholson/nanoprintf](https://github.com/charlesnicholson/nanoprintf) : The smallest public printf implementation for its feature set.
- [cjlano/tinyprintf](https://github.com/cjlano/tinyprintf) : A tiny printf and sprintf library for small embedded systems
  - [A tiny printf for embedded applications](http://www.sparetimelabs.com/tinyprintf/tinyprintf.php)
- [MaJerle/lwprintf](https://github.com/MaJerle/lwprintf) : Lightweight printf library optimized for embedded systems
- blog
  - [printf() and friends… yes, really :-)](https://eyalroz.github.io/software/printf/)
  - [An Embedded-friendly printf Implementation](https://embeddedartistry.com/blog/2019/11/06/an-embedded-friendly-printf-implementation/)

## log
- [rokath/trice](https://github.com/rokath/trice) : super fast and tiny embedded device C printf-like trace code (works also inside interrupts) and real-time PC logging (trace ID visualization)
  - Homepage : https://rokath.github.io/trice/
  - [Tracing & Logging with the `TRICE` Library (Interrupts too!)](https://interrupt.memfault.com/blog/trice)
  - [TriceUserGuide.md](https://github.com/rokath/trice/blob/master/docs/TriceUserGuide.md)
  - [TriceSpeed.md](https://github.com/rokath/trice/blob/master/docs/TriceSpeed.md)
  - [Trice Similarities and differences to printf usage](https://github.com/rokath/trice/blob/master/docs/TriceVsPrintfSimilaritiesAndDifferences.md#printf-like-functions)
- [μP7 (micro P7) ](https://baical.net/up7.html) : μP7 (micro P7) is lightweight C library for sending trace/logs & telemetry data from your Micro-controller’s firmware to host/HW FIFO/cycle buffer/network/etc. for further analysis. It is designed to be integrated on almost every microcontroller, even with very limited resources.
- [Zephyr Logging](https://docs.zephyrproject.org/3.1.0/services/logging/index.html)
- [rxi/log.c](https://github.com/rxi/log.c) : A simple logging library implemented in C99
- [rdpoor/ulog](https://github.com/rdpoor/ulog) : lightweight logging for embedded microcontrollers
- [martinribelotta/elog](https://github.com/martinribelotta/elog) : Embedded logger with minimal footprint and memory usage
- [EasyLogger](https://github.com/armink/EasyLogger)
- blog
  - [printf/log Debugging](https://emp.jamesmunns.com/debug/logging.html) : Embedded: The Missing Parts
  - [BEYOND PRINTF(): BETTER LOGGING PRACTICES FOR FASTER DEBUGGING](https://hackaday.com/2020/07/21/beyond-printf-better-logging-practices-for-faster-debugging/)
  - [Embedded Logging Framework for Spacecrafts](https://ui.adsabs.harvard.edu/abs/2013ESASP.720E..52D/abstract)
  - [McuLog: Logging Framework for small Embedded Microcontroller Systems](https://mcuoneclipse.com/2020/06/01/mculog-logging-framework-for-small-embedded-microcontroller-systems/)
  - [Logging On An Embedded System](https://blog.mbedded.ninja/programming/logging-on-an-embedded-system/)


## flash
- [SFUD](https://github.com/armink/SFUD)
- [Flash Circular Buffer (FCB)](https://docs.zephyrproject.org/3.2.0/services/storage/fcb/fcb.html) : Flash circular buffer provides an abstraction through which you can treat flash like a FIFO. You append entries to the end, and read data from the beginning.


### flash database
- [FlashDB](https://github.com/armink/FlashDB)

## file system
- [littlefs](https://github.com/littlefs-project/littlefs)

## JSON
- [cJSON](https://github.com/DaveGamble/cJSON)

## math library
- [CMSIS DSP](https://github.com/ARM-software/CMSIS-DSP)

## shell
- [letter shell](https://github.com/NevermindZZT/letter-shell) : 可以让串口对现有函数进行组合以及调用

## button/key
- [MultiButton](https://github.com/0x1abin/MultiButton) : 按键管理

## timer
- [MultiTimer](https://github.com/0x1abin/MultiTimer) : 软件定时器

## checksum
- [libcrc](https://github.com/lammertb/libcrc) : CRC 校验数据完整性

## Tracer
- [CmBacktrace](https://github.com/armink/CmBacktrace)

## oop framework
- [PLOOC](https://github.com/GorgonMeducer/PLOOC)

## test framework
- []()

## runtime
- []()

## dfu
- []()

## bootloader
- [mcuboot](https://www.mcuboot.com/)

## usb
- [tinyusb](https://github.com/hathach/tinyusb)

## bluetooth
- [btstack](https://github.com/bluekitchen/btstack)

## TCP/IP
- [uIP](https://www.wikiwand.com/en/UIP_(micro_IP))

## GUI
- []()

### Menu
- []()

## font
- []()

## mqtt
- []()

## random number generator
- []()

## C++ template
- [Embedded Template Library (ETL)](https://github.com/ETLCPP/etl)

## public domain libraries
- [stb](https://github.com/nothings/stb)

## compression
- [heatshrink](https://github.com/atomicobject/heatshrink)

## code style
- [MaJerle/c-code-style](https://github.com/MaJerle/c-code-style)

## blog
- [interrupt blog](https://interrupt.memfault.com/)
