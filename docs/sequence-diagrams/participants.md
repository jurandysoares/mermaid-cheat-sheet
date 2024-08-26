# Participants

The participants or actors are rendered in order of appearance in the diagram source text.

```markdown
sequenceDiagram
    participant Alice
    participant John
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
```

```{mermaid}
sequenceDiagram
    participant Alice
    participant John
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
```

You can specify the actor's order of appearance to show the participants in a different order.

```markdown
sequenceDiagram
    participant John
    participant Alice
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
```

```{mermaid}
sequenceDiagram
    participant John
    participant Alice
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
```

The participants can be defined implicitly without specifying them with the `participant` keyword.

```markdown
sequenceDiagram
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
```

```{mermaid}
sequenceDiagram
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
```

