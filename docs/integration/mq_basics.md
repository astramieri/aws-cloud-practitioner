# MQ Basics

- SQS and SNS are *cloud-native* services (proprietary protocols from AWS)
- Traditional applications running from on-premises may use open protocols such as MQTT, AMQP, STOMP, Openwire, WSS
- When **migrating to the cloud**, **instead of re-engineering** the application to use SQS and SNS, you can use Amazon MQ
- Amazon MQ is a managed message broker service for **RabbitMQ** and **ActiveMQ**
- Amazon MQ does not scale as much as SQS or SNS
- Amazon MQ runs on servers, can run in Multi-AZ with failover
- Amazon MQ has both queue features (~SQS) and topic features (~SNS)