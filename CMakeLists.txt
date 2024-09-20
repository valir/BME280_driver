
if(CONFIG_USE_SENSOR_BME280)
idf_component_register(
  SRCS
    bme280.c
  INCLUDE_DIRS
    .
  REQUIRES arduino)
endif()
