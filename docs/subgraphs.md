# Subgraphs
You can partition complex graphs into subgraphs.  For example here are three separate subgraphs from the healthcare domain.


```mermaid
graph TD
    subgraph Financial
        id1((Provider))
        id2((Claim))
        id3((Patient))
    end
    subgraph Clinical
        id4((Patient))
        id5((Diagnosis))
        id6((Condition))
    end
    subgraph Insurance
        id7((Company))
        id8((Plan))
        id9((Enrollment))
        id10((Member))
    end
```

Here is the code to render this graph:

```
graph TD
    subgraph Financial
        id1((Provider))
        id2((Claim))
        id3((Patient))
    end
    subgraph Clinical
        id4((Patient))
        id5((Diagnosis))
        id6((Condition))
    end
    subgraph Insurance
        id7((Company))
        id8((Plan))
        id9((Enrollment))
        id10((Member))
    end
```

```mermaid
graph RL
    subgraph financial
        id1((Provider))
        -- SUBMITS -->
        id2((Claim))
        -- FOR_SERVICES_ON -->
        id3((Patient))
    end
    subgraph clinical
        id3((Patient))
        -- HAS_CONDITION -->
        id4((Condition))
    end
```

