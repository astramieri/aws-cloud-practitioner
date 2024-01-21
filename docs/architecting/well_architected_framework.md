# AWS Well Architected Framework

## General Guiding Principles

- Stop guessing your capacity needs
- Test systems at production scale
- Automate to make architectural experimentation easier
- Allow for evolutionary architectures
    - Design based on changing requirements
- Drive architecture using data
- Improve through game days
    - Simulate application for flash sale days
    - E.g. *Netflix Chaos Monkey*

## AWS Cloud Best Practices - Design Principles

- **Scalability**
    - Vertical & Horizontal
- **Disposable Resources**
    - Servers should be disposable & easily configured
- **Automation**
    - Serverless, Infrasctructure as a Service, Auto Scaling, etc.
- **Loose Coupling**
    - Monolith are applications that do more and more over time, become bigger, difficult to maintain and difficult to scale
    - Break it down into smaller loosely coupled components
    - A change or a failure in one component should not cascade to other components
- **Services, not Servers**
    - Don't use just EC2
    - Use managed services, databases, serverless, etc.

## Well Architected Frameworks - 6 Pillars

1. Operational Excellence
2. Security
3. Reliability
4. Performance Efficiency
5. Cost Optimization
6. Sustainability

They are not something to balance, or trade-offs, **there are a synergy**.