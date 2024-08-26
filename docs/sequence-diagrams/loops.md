# Loops

Express loops in a sequence diagram by the notation `loop`.

```
loop Loop text
... statements ...
end
```

```markdown
sequenceDiagram
    Alice->John: Hello John, how are you?
    loop Every minute
        John-->Alice: Great!
    end
```

```{mermaid}
sequenceDiagram
    Alice->John: Hello John, how are you?
    loop Every minute
        John-->Alice: Great!
    end
```

