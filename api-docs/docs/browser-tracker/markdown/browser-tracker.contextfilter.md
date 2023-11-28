<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@snowplow/browser-tracker](./browser-tracker.md) &gt; [ContextFilter](./browser-tracker.contextfilter.md)

## ContextFilter type

A context filter is a user-supplied callback that is evaluated for each event to determine if the context associated with the filter should be attached to the event

<b>Signature:</b>

```typescript
type ContextFilter = (args?: ContextEvent) => boolean;
```