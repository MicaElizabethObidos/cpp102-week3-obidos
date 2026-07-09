```mermaid
flowchart TD
    A{START} --> B[weekly budget]
    A{START} --> C[total expenses]
    B --> D[weekly budget - total expenses]
  C --> D[weekly budget - total expenses]
  D --> E[remaining balance]
  E --> F[=output]
  F --> G{END}
  ```
