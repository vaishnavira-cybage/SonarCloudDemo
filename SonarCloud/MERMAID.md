# Example of embedding Mermaid diagrams

Using the [Mermaid Viewer extension](https://marketplace.visualstudio.com/items?itemName=DanieleCas.azure-devops-mermaid-viewer) to render some Mermaid diagrams. [GitHub repo](https://github.com/daniecas/azure-devops-mermaid-viewer)

Extension requires using `::mermaid` and `:::` as delimiters (instead of the usual ` ``` ` fences)

:::mermaid
flowchart TD
  A[Start] --> B{Decision}
  B -->|Option A| C[Process A]
  B -->|Option B| D[Process B]
  C --> E[End]
  D --> E
:::
