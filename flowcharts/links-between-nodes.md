### 1.3 Links Between Nodes

<table>
  <thead>
    <tr>
      <th>Feature</th>
      <th>Diagram</th>
      <th>Definition</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Link with Arrow Head</td>
      <td><div class="mermaid">graph LR;A-->B</div></td>
      <td>
        <pre class="highlight">graph LR;<br/>    A-->B</pre>
      </td>
    </tr>
    <tr>
      <td>Open Link</td>
      <td><div class="mermaid">graph LR;A---B</div></td>
      <td>
        <pre class="highlight">graph LR;<br/>    A---B</pre>
      </td>
    </tr>
    <tr>
      <td>Text on Links(1)</td>
      <td><div class="mermaid">graph LR;A-- This is the text ---B</div></td>
      <td>
        <pre class="highlight">graph LR;<br/>    A-- This is the text ---B</pre>
      </td>
    </tr>
    <tr>
      <td>Text on Links(2)</td>
      <td><div class="mermaid">graph LR;A---|This is the text|B</div></td>
      <td>
        <pre class="highlight">graph LR;<br/>    A---|This is the text|B</pre>
      </td>
    </tr>
    <tr>
      <td>Link with Arrow Head and Text(1)</td>
      <td><div class="mermaid">graph LR;A-->|text|B</div></td>
      <td>
        <pre class="highlight">graph LR;<br/>    A-->|text|B</pre>
      </td>
    </tr>
    <tr>
      <td>Link with Arrow Head and Text(2)</td>
      <td><div class="mermaid">graph LR;A-- text -->B</div></td>
      <td>
        <pre class="highlight">graph LR;<br/>    A-- text -->B</pre>
      </td>
    </tr>
    <tr>
      <td>Dotted Link</td>
      <td><div class="mermaid">graph LR;A-.->B;</div></td>
      <td>
        <pre class="highlight">graph LR;<br/>    A-.->B;</pre>
      </td>
    </tr>
    <tr>
      <td>Dotted Link with Text</td>
      <td><div class="mermaid">graph LR;A-. text .-> B</div></td>
      <td>
        <pre class="highlight">graph LR;<br/>    A-. text .-> B</pre>
      </td>
    </tr>
    <tr>
      <td>Thick Link</td>
      <td><div class="mermaid">graph LR;A ==> B</div></td>
      <td>
        <pre class="highlight">graph LR;<br/>    A ==> B</pre>
      </td>
    </tr>
    <tr>
      <td>Thick link with text</td>
      <td><div class="mermaid">graph LR;A == text ==> B</div></td>
      <td>
        <pre class="highlight">graph LR;<br/>    A == text ==> B</pre>
      </td>
    </tr>
  </tbody>
</table>

