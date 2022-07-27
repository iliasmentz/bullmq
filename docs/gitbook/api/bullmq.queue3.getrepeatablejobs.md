<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [Queue3](./bullmq.queue3.md) &gt; [getRepeatableJobs](./bullmq.queue3.getrepeatablejobs.md)

## Queue3.getRepeatableJobs() method

Returns JobInformation of repeatable jobs (ordered descending). Provide a start and/or an end index to limit the number of results. Start defaults to 0, end to -1 and asc to false.

<b>Signature:</b>

```typescript
getRepeatableJobs(start?: number, end?: number, asc?: boolean): Promise<JobInformation3[]>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  start | number |  |
|  end | number |  |
|  asc | boolean |  |

<b>Returns:</b>

Promise&lt;[JobInformation3](./bullmq.jobinformation3.md)<!-- -->\[\]&gt;
