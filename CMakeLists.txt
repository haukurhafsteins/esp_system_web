idf_component_register(SRCS "esp_system_web.c"
                    INCLUDE_DIRS "include"
                    PRIV_REQUIRES "esp_http_server" "esp_ethernet" "nvsstorage" "nvs_flash")
                    
