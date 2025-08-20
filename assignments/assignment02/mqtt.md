# Exploring MQTT QoS Levels

Experiment with QoS 0, 1, and 2.
Observe how message delivery changes based on QoS settings.

## Publisher_qos.py output

```
c:\Users\kamph\OneDrive\Desktop\IOT\Iot-class-2025-gateway\app\publisher_qos.py:20: DeprecationWarning: Callback API version 1 is deprecated, update to latest version
  client = mqtt.Client()
[15:11:15] DEBUG | Sending CONNECT (u0, p0, wr0, wq0, wf0, c1, k60) client_id=b''
Enter message to publish: [15:11:15] DEBUG | Received CONNACK (0, 0)
hi 
Enter QoS level (0, 1, 2): [15:12:16] DEBUG | Sending PINGREQ
[15:12:16] DEBUG | Received PINGRESP
2
[15:13:00] DEBUG | Sending PUBLISH (d0, q2, r0, m1), 'b'test/qos/6510301025/temperature'', ... (3 bytes)
[15:13:00] PUBLISH REQUESTED | QoS=2 | Message='hi ' | msgid=1
Enter message to publish: [15:13:00] DEBUG | Received PUBREC (Mid: 1)
[15:13:00] DEBUG | Sending PUBREL (Mid: 1)
[15:13:00] DEBUG | Received PUBCOMP (Mid: 1)
[15:13:00] PUBLISHED | msgid=1
[15:13:16] DEBUG | Sending PINGREQ
[15:13:16] DEBUG | Received PINGRESP
```

## Subscriber_qos.py Output

```
c:\Users\kamph\OneDrive\Desktop\IOT\Iot-class-2025-gateway\app\subscriber_qos.py:25: DeprecationWarning: Callback API version 1 is deprecated, update to latest version
  client = mqtt.Client()
[15:08:16] DEBUG | Sending CONNECT (u0, p0, wr0, wq0, wf0, c1, k60) client_id=b''
[15:08:16] DEBUG | Received CONNACK (0, 0)
[15:08:16] Connected with result code 0
[15:08:16] DEBUG | Sending SUBSCRIBE (d0, m1) [(b'test/qos/6510301025', 2)]
[15:08:16] DEBUG | Received SUBACK
```