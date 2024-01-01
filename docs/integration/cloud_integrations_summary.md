# Cloud Integration Summary

- **SQS**
    - Queue service in AWS
    - Multiple producers, message are kept up for 14 days
    - Multiple consumers share (i.e split) the read and delete message when done
    - Used to decouple applications in AWS
- **SNS**
    - Notification service in AWS
    - Subscribers: Email, Lambda, SQS, HTTP, Mobile
    - Multiple subscribers, send all messages to all of them
    - No message retention
- **Kinesis**
    - Real-time data streaming, persistence and analysis
- **MQ**
    - Managed message broker for ActiveMQ and RabbitMQ in the cloud
    - Protocols: MQTT, AMQP, STOMP, OpenWire, WSS