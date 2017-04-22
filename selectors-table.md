<table>
  <thead>
    <th>#</th>
    <th>CSS Selector</th>
    <th>Explanation</th>
    <th>Purpose</th>
    <th>HTML element(s) selected</th>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td><code>div.tabComponent input</code></td>
      <td>The type selector <code>div</code> is combined with the class selector <code>.tabComponent</code> to select the outermost div with <code>class="tabComponent"</code>. This composite selector is then combined with another type selector <code>input</code> to select all the input type elements.</td>
      <td>To apply style rules to the radio button input type elements</td>
      <td>Elements selected by this rule are the radio buttons with <code>id="tab1"</code>, <code>id="tab2"</code> and <code>id="tab3"</code>.</td>
    </tr>
    <tr>
      <td>2</td>
      <td><code>div.tabComponent label</code></td>
      <td>The type selector <code>div</code> is combined with the class selector <code>.tabComponent</code> to select the outermost div with <code>class="tabComponent"</code>. This composite selector is then combined with another type selector <code>label</code> to select all the label type elements.</td>
      <td>To apply style rules to the label elemets</td>
      <td>All the labels that will act as the clickable tab's</td>
    </tr>
    <tr>
      <td>3</td>
      <td><code>div.tabComponent input[type="radio"]:checked + label </code></td>
      <td>The type selector <code>div</code> is combined with the class selector <code>.tabComponent</code> to select the outermost div with <code>class="tabComponent"</code>. This composite selector is then combined with an attribute equals selector <code>input[type="radio"]:checked</code> with the pseudo class <code>:checked</code> to select the radio button that is checked. Finally, the previoius selector is combined with an adjacent sibling selector to select only the label for the checked radio button.</td>
      <td>To apply style rules to the label of the current tab.</td>
      <td>The label of the currently checked radio button.</td>
    </tr>
    <tr>
      <td>4</td>
      <td><code>div.tabComponent div.tab-content</code></td>
      <td>The type selector <code>div</code> is combined with the class selector <code>.tabComponent</code> to select the outermost div with <code>class="tabComponent"</code>. This composite selector is then combined with another composite selector, <code>div.tab-content</code> to select all the div elements with <code>class="tab-content"</code>.</td>
      <td>To apply style rules to all the tab contents.</td>
      <td>All the tabs' contents.</td>
    </tr>
    <tr>
      <td>5</td>
      <td><code>div.tabComponent input[type="radio"]:checked + label + div.tab-content</code></td>
      <td>Works like selector #3 plus it adds another adjacent sibling selector to select the tab content of the currently selected tab.</td>
      <td>To apply style rules to the currently selected tab's content</td>
      <td>The element that hold the contents of the currently selected tab.</td>
    </tr>
  </tbody>
</table>
