### 2.5 Notes

Add notes to a sequence diagram by the notation `Note`.

```raw
Note [ right of | left of | over ] [Actor]: Text in note content
```

1) Right Side

~~~markdown
sequenceDiagram
    participant John
    Note right of John: Text in note
~~~

<div class="mermaid">
sequenceDiagram
    participant John
    Note right of John: Text in note

</div>

2) Left Side

~~~markdown
sequenceDiagram
    participant John
    Note left of John: Text in note
~~~

<div class="mermaid">
sequenceDiagram
    participant John
    Note left of John: Text in note
</div>

3) Over

~~~markdown
sequenceDiagram
    participant John
    Note over John: Text in note
~~~

<div class="mermaid">
sequenceDiagram
    participant John
    Note over John: Text in note
</div>

4) Create notes spanning two participants

~~~markdown
sequenceDiagram
    Alice->>John: Hello John, how are you?
    Note over Alice,John: A typical interaction
~~~

<div class="mermaid">
sequenceDiagram
    Alice->>John: Hello John, how are you?
    Note over Alice,John: A typical interaction
</div>

