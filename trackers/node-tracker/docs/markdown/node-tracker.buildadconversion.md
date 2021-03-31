<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@snowplow/node-tracker](./node-tracker.md) &gt; [buildAdConversion](./node-tracker.buildadconversion.md)

## buildAdConversion() function

Build a Ad Conversion Event Used to track an advertisement click

 If you provide the cost field, you must also provide one of 'cpa', 'cpc', and 'cpm' for the costModel field.

<b>Signature:</b>

```typescript
declare function buildAdConversion(event: AdConversionEvent): PayloadBuilder;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  event | AdConversionEvent | Contains the properties for the Ad Conversion event  PayloadBuilder to be sent to  |

<b>Returns:</b>

PayloadBuilder
