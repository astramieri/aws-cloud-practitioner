# Cloud Integrations

The are two patterns of application communication:
1. Synchronous Communication 
    - application to application
2. Asynchronous Communication (or Event Based)
    - application to queue to application
    - applications are *decoupled*

Synchronous between application can be problematic if there are sudden spikes of traffic. 

It is better to **decouple applications** using:
- **AWS SQS**: queue model (producer/consumer)
- **AWS SNS**: publish/subscribe model
- **AWS Kinesis**: real-time data streaming model

Decoupled services **can scale indipendently** from our application.

