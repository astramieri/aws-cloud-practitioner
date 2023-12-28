# EventBridge Basics (formerly CloudWatch Events)

With AWS EventBridge you can react to events happening within your AWS accounts.

Use cases:
- Schedule: Cron Jobs (scheduled scripts)
    - e.g. You can create a rule that says: *every one hour you should have an event created and that event will trigger a script running on a Lambda function* (serverless cron job)
- Event Pattern: Event rules to react to a service doing something
    - e.g. You wanted to give alerts to your security team whenever someone is going to log in using the root user

Destinations:
- Trigger Lambda functions
- Send SQS/SNS messages
- etc.

![EventBridge](../../images/monitoring/eventbridge.png)


## EventBridge Capabilities

- **Default Event Bus** (AWS Services)
- **Partner Event Bus** (AWS SaaS Partners)
- **Custom Event Bus** (Custom Apps)
- **Schema Registry**: model event schema
- Ability to **archive events** (all/filter) sent to an event bus (indefinitely or set period)
- Ability to **replay archived events**

![EventBridge Event Bus](../../images/monitoring/eventbridge_event_bus.png)