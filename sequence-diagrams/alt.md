# Alt

Express alternative paths in a sequence diagram by the notation `alt`.

```markdown
alt Describing text
... statements ...
else
... statements ...
end
```

Or, if there is sequence that is optional (if without else).

```markdown
opt Describing text
... statements ...
end
```

Example:

```markdown
sequenceDiagram
    Alice->>John: Hello John, how are you?
    alt is sick
        John->>Alice: Not so good :(
    else is well
        John->>Alice: Feeling fresh like a daisy
    end
    opt Extra response
        John->>Alice: Thanks for asking
    end
```

```{mermaid}
sequenceDiagram
    Alice->>John: Hello John, how are you?
    alt is sick
        John->>Alice: Not so good :(
    else is well
        John->>Alice: Feeling fresh like a daisy
    end
    opt Extra response
        John->>Alice: Thanks for asking
    end
```

