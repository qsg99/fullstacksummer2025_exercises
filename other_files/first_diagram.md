```mermaid
graph TD
  A[Start] --> B{Is it working?}
  B -- Yes --> C[Celebrate!]
  B -- No --> D[Debug]
  D --> B
```