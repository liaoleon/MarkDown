# LeetCode 55: Jump Game 運算流程

```mermaid
graph TD
    subgraph Step_1["Step 1: 初始化"]
        A["<span>2</span>"]:::current
        B["<span>3</span>"]:::reachable
        C["<span>1</span>"]:::reachable
        D["<span>1</span>"]
        E["<span>4</span>"]
    end

    subgraph Step_2["Step 2: 移動到第二個元素"]
        A["<span>2</span>"]:::visited
        B["<span>3</span>"]:::current
        C["<span>1</span>"]:::reachable
        D["<span>1</span>"]:::reachable
        E["<span>4</span>"]:::reachable
    end

    classDef current fill:#FFF8DC,stroke:#000,stroke-width:1px,color:#000,padding:5px,border-radius:5px;
    classDef reachable fill:#E0FFE0,stroke:#000,stroke-width:1px,color:#000,padding:5px,border-radius:5px;
    classDef visited fill:#F0F0F0,stroke:#000,stroke-width:1px,color:#000,padding:5px,border-radius:5px;
