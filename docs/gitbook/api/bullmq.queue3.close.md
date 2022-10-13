<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [Queue3](./bullmq.queue3.md) &gt; [close](./bullmq.queue3.close.md)

## Queue3.close() method

Closes the underlying redis client. Use this to perform a graceful shutdown.

`close` can be called from anywhere, with one caveat: if called from within a job handler the queue won't close until after the job has been processed

<b>Signature:</b>

```typescript
close(): Promise<any>;
```
<b>Returns:</b>

Promise&lt;any&gt;
