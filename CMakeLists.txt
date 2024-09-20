if(CONFIG_USE_SENSOR_BME280)
  set(BME280_SRCS bme280.c)
endif()

idf_component_register(
  SRCS
    ${BME280_SRCS}
  INCLUDE_DIRS
    .
  REQUIRES arduino)
