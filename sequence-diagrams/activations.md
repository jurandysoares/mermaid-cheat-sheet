### 2.4 Activations

Activate and deactivate an actor.

~~~markdown
sequenceDiagram
    Alice->>John: Hello John, how are you?
    activate John
    John-->>Alice: Great!
    deactivate John
~~~

<div class="mermaid">
sequenceDiagram
    Alice->>John: Hello John, how are you?
    activate John
    John-->>Alice: Great!
    deactivate John
</div>

Shortcut notation by appending `+/-` suffix to the message arrow.

~~~markdown
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    John-->>-Alice: Great!
~~~

<div class="mermaid">
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    John-->>-Alice: Great!
</div>

Activations can be stacked for same actor:

~~~markdown
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
~~~

<div class="mermaid">
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
</div>

