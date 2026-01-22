idf_component_register(
    SRCS "hello_world_main.c"
    INCLUDE_DIRS "."       # Your header files, "." means the current folder
    REQUIRES driver esp_timer log spi_flash   # All the dependencies
)