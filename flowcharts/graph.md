### 1.1 Graph

Possible directions are:

* `TB` - top bottom
* `BT` - bottom top
* `RL` - right left
* `LR` - left right
* `TD` - same as TB

<table>
  <thead>
    <tr>
      <th>Direction</th>
      <th>Diagram</th>
      <th>Definition</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TB</td>
      <td><div class="mermaid">graph TB;A-->B;</div></td>
      <td>
        <pre class="highlight">graph TB;<br/>    A-->B;</pre>
      </td>
    </tr>
    <tr>
      <td>BT</td>
      <td><div class="mermaid">graph BT;A-->B;</div></td>
      <td>
        <pre class="highlight">graph BT;<br/>    A-->B;</pre>
      </td>
    </tr>
    <tr>
      <td>RL</td>
      <td><div class="mermaid">graph RL;A-->B;</div></td>
      <td>
        <pre class="highlight">graph RL;<br/>    A-->B;</pre>
      </td>
    </tr>
    <tr>
      <td>LR</td>
      <td><div class="mermaid">graph LR;A-->B;</div></td>
      <td>
        <pre class="highlight">graph LR;<br/>    A-->B;</pre>
      </td>
    </tr>
    <tr>
      <td>TD</td>
      <td><div class="mermaid">graph TD;A-->B;</div></td>
      <td>
        <pre class="highlight">graph TD;<br/>    A-->B;</pre>
      </td>
    </tr>
  </tbody>
</table>

