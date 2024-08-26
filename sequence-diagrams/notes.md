# Notes

Add notes to a sequence diagram by the notation `Note`.

```
Note [ right of | left of | over ] [Actor]: Text in note content
```

1) Right Side

```markdown
sequenceDiagram
    participant John
    Note right of John: Text in note
```

```{mermaid}
sequenceDiagram
    participant John
    Note right of John: Text in note

```

2) Left Side

```markdown
sequenceDiagram
    participant John
    Note left of John: Text in note
```

```{mermaid}
sequenceDiagram
    participant John
    Note left of John: Text in note
```

3) Over

```markdown
sequenceDiagram
    participant John
    Note over John: Text in note
```

```{mermaid}
sequenceDiagram
    participant John
    Note over John: Text in note
```

4) Create notes spanning two participants

```markdown
sequenceDiagram
    Alice->>John: Hello John, how are you?
    Note over Alice,John: A typical interaction
```

```{mermaid}
sequenceDiagram
    Alice->>John: Hello John, how are you?
    Note over Alice,John: A typical interaction
```

