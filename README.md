# Универсальная доска для esp32 или esp32s3 
 
## Питание 5-19в
 ------- Опционально -------
- 5 силовых ключей коммутации
- INMP441 - микрофон
   * пины для esp32-s3
     * #define I2S_WS 16
     * #define I2S_SD 15
     * #define I2S_SCK 37
- Экранчик  80x160
   * пины для esp32-s3
     * #define TFT_SCL 19
     * #define TFT_SDA 9
     * #define TFT_RS  20
     * #define TFT_CS  47
     * #define TFT_RES 48
     * #define TFT_BLK 35
- Динамик пищалка
- LORAWAN (Отдельный DC-DC)
     * #define LORA_NSS 38
     * #define LORA_DIO0 42
     * #define LORA_RST 36
     * #define LORA_SCK 39
     * #define LORA_MISO 40
     * #define LORA_MOSI 1
     * #define LORA_DIO1 2
 
SPI.begin(LORA_SCK, LORA_MISO, LORA_MOSI, LORA_NSS);

main2.cpp

<img src="img\setTxPower.png" alt="" width="643">
<img src="img\img1.jpg" alt="" width="643">
<img src="img\img2.jpg" alt="" width="643">
<img src="img\img3.jpg" alt="" width="643">
