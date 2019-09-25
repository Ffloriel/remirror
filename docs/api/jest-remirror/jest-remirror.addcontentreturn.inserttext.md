<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [jest-remirror](./jest-remirror.md) &gt; [AddContentReturn](./jest-remirror.addcontentreturn.md) &gt; [insertText](./jest-remirror.addcontentreturn.inserttext.md)

## AddContentReturn.insertText() method

Insert text at the current starting point for the cursor. Text will be typed out with keys each firing a keyboard event.

! This doesn't currently support the use of tags and cursors. ! Also adding multiple strings which create nodes also creates an out of position error

<b>Signature:</b>

```typescript
insertText(text: string): AddContentReturn<GExtension>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  text | <code>string</code> |  |

<b>Returns:</b>

`AddContentReturn<GExtension>`
