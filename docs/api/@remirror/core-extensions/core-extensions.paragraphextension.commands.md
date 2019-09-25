<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@remirror/core-extensions](./core-extensions.md) &gt; [ParagraphExtension](./core-extensions.paragraphextension.md) &gt; [commands](./core-extensions.paragraphextension.commands.md)

## ParagraphExtension.commands() method

Provides the commands that this extension uses.

<b>Signature:</b>

```typescript
commands({ type }: CommandNodeTypeParams): {
        createParagraph: (attrs?: import("@remirror/core").Attrs<{
            align?: "left" | "right" | "center" | "justify" | null | undefined;
            indent?: number | null | undefined;
            lineSpacing?: string | null | undefined;
            id?: string | null | undefined;
        }> | undefined) => (state: import("prosemirror-state").EditorState<import("prosemirror-model").Schema<string, string>>, dispatch?: ((tr: import("prosemirror-state").Transaction<import("prosemirror-model").Schema<string, string>>) => void) | undefined) => boolean;
    };
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  { type } | <code>CommandNodeTypeParams</code> |  |

<b>Returns:</b>

`{
        createParagraph: (attrs?: import("@remirror/core").Attrs<{
            align?: "left" | "right" | "center" | "justify" | null | undefined;
            indent?: number | null | undefined;
            lineSpacing?: string | null | undefined;
            id?: string | null | undefined;
        }> | undefined) => (state: import("prosemirror-state").EditorState<import("prosemirror-model").Schema<string, string>>, dispatch?: ((tr: import("prosemirror-state").Transaction<import("prosemirror-model").Schema<string, string>>) => void) | undefined) => boolean;
    }`
