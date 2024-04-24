idf_component_register(
    SRCS "src/SoftwareSerial.cpp"
    INCLUDE_DIRS "./src" "./src/circular_queue"
    REQUIRES arduino-esp32
)