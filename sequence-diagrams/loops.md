### 2.6 Loops

Express loops in a sequence diagram by the notation `loop`.

```raw
loop Loop text
... statements ...
end
```

~~~markdown
sequenceDiagram
    Alice->John: Hello John, how are you?
    loop Every minute
        John-->Alice: Great!
    end
~~~

<div class="mermaid">
sequenceDiagram
    Alice->John: Hello John, how are you?
    loop Every minute
        John-->Alice: Great!
    end
</div>

