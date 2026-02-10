# STM8_AV2026
Library to control the AV2026 satellite tuner from Airoha, that can be be found in some satellite receivers, although digital and mainly for DVB-S, it can be used for FM signal reception also for example. I also put IF offset into the library, so you can set the IF offset directly. The range I tested is from 600 to 2500 MHz, so good for some RF experiments.
# Usage
This library was made for cosmic compiler, so you can just directly paste source and header files into your project folder src and inc.
# External references
- https://github.com/glinuz/hi3798mv100/tree/12aa0504880d518a9fa15800d4f7a305a1f94dc6/HiSTBLinuxV100R005C00SPC041B020/source/msp/drv/frontend/tuner/AV2026 - Original library, that I used to get the data about registers
- https://www.elektromys.eu/knihovny.php - Libraries for STM8, not only for I2C
