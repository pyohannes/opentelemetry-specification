# Rabbit MQ

**Status**: [Experimental](../../document-status.md)

## Attributes

In RabbitMQ, the destination is defined by an *exchange* and a *routing key*.
`messaging.destination.name` MUST be set to the name of the exchange. This will be an empty string if the default exchange is used.

<!-- semconv messaging.rabbitmq -->
| Attribute  | Type | Description  | Examples  | Requirement Level |
|---|---|---|---|---|
| `messaging.rabbitmq.destination.routing_key` | string | RabbitMQ message routing key. | `myKey` | Conditionally Required: If not empty. |
<!-- endsemconv -->
