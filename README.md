# MQTT Client 1.0.2

Simple MQTT Client.


```shell
MQTT Client 1.0.2

Usage:
  mqtt_client publish --host=<host> --topic=<topic> (--payload=<payload> | --interactive) [--username=<username>] [--password=<password>] [--transport=<transport>] [--cert_path=<cert_path>]
  mqtt_client subscribe --host=<host> --topic=<topic> [--username=<username>] [--password=<password>] [--transport=<transport>] [--cert_path=<cert_path>]
  mqtt_client (-h|--help)
  mqtt_client (-v|--version)

Commands:
  publish                   Publish to topic from MQTT Broker.
  subscribe                 Subscribe to topic from MQTT Broker.

Options:
  -h --help                 Show this screen.
  -v --version              Show version.
  --host=<host>             Broker Host. (Example: example.your_broker.com:1883)
  --topic=<topic>           Topic.
  --payload=<payload>       Payload to send.
  -i --interactive          Interactive mode.
  --username=<username>     Username.
  --password=<password>     Password.
  --transport=<transport>   TCP, TCP-TLS, WS, WS-TLS (Default: TCP)
  --cert_path=<cert_path>   Path cert (Default: ./mqtt_broker_cert.pem)
```