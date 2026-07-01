idf_component_register(SRCS "main.c" "oled.c"
                       PRIV_REQUIRES esp_adc esp_lcd
                       INCLUDE_DIRS ".")
