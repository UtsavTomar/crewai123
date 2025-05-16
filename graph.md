# Sample Graph in Markdown

This is a simple flowchart rendered using [Mermaid](https://mermaid-js.github.io/mermaid/#/).

## Flowchart

```mermaid
graph TD
    A[Start] --> B{Is it working?}
    B -- Yes --> C[Keep it running]
    B -- No --> D[Fix it]
    D --> B
