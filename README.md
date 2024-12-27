# LeetCode 55: Jump Game 運算流程

```mermaid
graph LR
    Step_1["Step 1: 初始化"]
    A1["2"]:::current --> A2["3"]:::reachable --> A3["1"]:::reachable --> A4["1"] --> A5["4"]

    Step_2["Step 2: 移動到第二個元素"]
    B1["2"]:::visited --> B2["3"]:::current --> B3["1"]:::reachable --> B4["1"]:::reachable --> B5["4"]:::reachable

    classDef current fill:#FFF8DC,stroke:#000,stroke-width:1px,color:#000,padding:5px,border-radius:5px;
    classDef reachable fill:#E0FFE0,stroke:#000,stroke-width:1px,color:#000,padding:5px,border-radius:5px;
    classDef visited fill:#F0F0F0,stroke:#000,stroke-width:1px,color:#000,padding:5px,border-radius:5px;

