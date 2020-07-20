### RUN MQTT BROKER on port 8087 [assuming mosquitto is installed in your system]:
`mosquitto -v -p 8087`

[Install nodejs & npm in your system](https://nodejs.org/en/download/)

[Install nosde-red in your system](https://nodered.org/docs/getting-started/windows)

## Launch the project
`node-red -v -u <Absolute path to this folder, where ever you downloaded it>/`

## Access the Configuration Web UI:
you can browse to `127.0.0.1:2025/ui`

Now the broker is running locally on your network, from your machine.
This configuration UI is talking to that MQTT broker, on this machine. 

## You need to now Update the Arduino Settings: 
In the Arduino IDE, change the BROKER: to your machine's IP address.
And the Broker PORT to 8087.