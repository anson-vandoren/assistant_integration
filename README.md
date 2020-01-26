# Notes

- Local devices communicate with local RPi over MQTT, with RPi as the MQTT broker
- Ngrok (for now) tunnel to provide public endpoint into RPi
  - Future: mirrored MQTT broker on public endpoint <-> RPi
- RPi running Google Assistant server that translates to MQTT commands and returns response
