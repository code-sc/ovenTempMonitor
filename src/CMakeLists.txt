pico_sdk_init()

add_executable(ovenTempMeasure main.c)

target_link_libraries(ovenTempMeasure pico_stdlib hardware_adc)

pico_enable_stdio_usb(ovenTempMeasure 1)

pico_add_extra_outputs(ovenTempMeasure)
