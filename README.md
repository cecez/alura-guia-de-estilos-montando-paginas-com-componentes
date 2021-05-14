# Notepad

- CSS variables
    ```css
    /* defining */
    :root {
        --black: #000;
    }
    /* usage */
    .class {
        background-color: var(--black);
    }
    ```

- Emmet

    - element.class
    ```html
    <element class="class"></element>
    ```

    - element>child.one+child+two
    ```html
    <element>
        <child class="one"></child>
        <child class="two"></child>
    </element>
    ```

- VS Code plugins
    - ecmel.vscode-html-css (HTML id and class attribute completion)