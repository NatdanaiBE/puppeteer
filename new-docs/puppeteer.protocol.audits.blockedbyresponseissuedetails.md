<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Audits](./puppeteer.protocol.audits.md) &gt; [BlockedByResponseIssueDetails](./puppeteer.protocol.audits.blockedbyresponseissuedetails.md)

## Protocol.Audits.BlockedByResponseIssueDetails interface

Details for a request that has been blocked with the BLOCKED\_BY\_RESPONSE code. Currently only used for COEP/COOP, but may be extended to include some CSP errors in the future.

<b>Signature:</b>

```typescript
export interface BlockedByResponseIssueDetails 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [blockedFrame](./puppeteer.protocol.audits.blockedbyresponseissuedetails.blockedframe.md) | [AffectedFrame](./puppeteer.protocol.audits.affectedframe.md) |  |
|  [parentFrame](./puppeteer.protocol.audits.blockedbyresponseissuedetails.parentframe.md) | [AffectedFrame](./puppeteer.protocol.audits.affectedframe.md) |  |
|  [reason](./puppeteer.protocol.audits.blockedbyresponseissuedetails.reason.md) | [BlockedByResponseReason](./puppeteer.protocol.audits.blockedbyresponsereason.md) |  |
|  [request](./puppeteer.protocol.audits.blockedbyresponseissuedetails.request.md) | [AffectedRequest](./puppeteer.protocol.audits.affectedrequest.md) |  |

