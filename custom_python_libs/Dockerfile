ARG BUILD_FROM
FROM $BUILD_FROM

# Add the library installation command
RUN pip install azure-iot-device

# Dummy service to keep the container running
CMD ["tail", "-f", "/dev/null"]
