<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [QueueEventsDeclaration](./bullmq.queueeventsdeclaration.md) &gt; [on](./bullmq.queueeventsdeclaration.on_10.md)

## QueueEventsDeclaration.on() method

Listen to 'waiting' event.

This event is triggered when a job enters the 'waiting' state.

<b>Signature:</b>

```typescript
on(event: 'waiting', listener: (args: {
        jobId: string;
    }, id: string) => void): this;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  event | 'waiting' |  listener |
|  listener | (args: { jobId: string; }, id: string) =&gt; void |  |

<b>Returns:</b>

this
