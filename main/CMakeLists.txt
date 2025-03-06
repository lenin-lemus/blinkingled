idf_component_register(SRCS "main.c"
                    INCLUDE_DIRS "."
                    REQUIRES esp_http_server esp_wifi 
                    REQUIRES spiffs nvs_flash driver log spi_flash 
                    )