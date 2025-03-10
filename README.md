# Tokens
<html>
    <head>
        <title>Tokens in C</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                background-color: #f3f3f3;
                color: #333;
                margin: 0;
                padding: 0;
                line-height: 1.6;
            }
            .code-container {
                background-color: #282c34;
                color: #61dafb;
                padding: 16px;
                border-radius: 8px;
                font-family: Consolas, "Courier New", monospace;
            }
            .code-container span.keyword {
                color: #d19a66;
                font-weight: bold;
            }
            .code-container span.string {
                color: #98c379;
            }
            .code-container span.identifier {
                color: #61dafb;
            }
            .code-container span.constant {
                color: #d19a66;
            }
            .code-container span.operator {
                color: #c678dd;
            }
            .code-container span.special-symbol {
                color: #56b6c2;
            }
        </style>
    </head>
    <body>
        <div class="code-container">
            <h2>Program displaying various tokens of C</h2>
            <pre>
    #include<<span class="keyword">stdio</span>.h&gt;
    <span class="keyword">int</span><span class="function"> main</span>() {
        <span class="keyword">int</span> <span class="identifier">number</span> = <span class="constant">10</span>; <span class="comment">// int is a keyword</span>
        <span class="keyword">float</span> <span class="identifier">pi</span> = <span class="constant">3.14</span>; <span class="comment">// float is a keyword</span>
        <span class="keyword">char</span> <span class="identifier">character</span> = <span class="string">'A'</span>; <span class="comment">// character is an identifier</span>
        <span class="keyword">const</span> <span class="keyword">int</span> <span class="identifier">constantValue</span> = <span class="constant">100</span>; <span class="comment">// 100 is a constant</span>
        <span class="keyword">char</span> <span class="identifier">string</span>[20] = <span class="string">"Hello, World!"</span>; <span class="comment">// "Hello, World!" is a string</span>
        <span class="keyword">int</span> <span class="identifier">sum</span> = <span class="identifier">number</span> <span class="operator">+</span> <span class="identifier">constantValue</span>; <span class="comment">// + is an operator</span>
        <span class="identifier">printf</span>(<span class="string">"Number: %d\n"</span>, <span class="identifier">number</span>); <span class="comment">// ; and () are special symbols</span>
        <span class="identifier">printf</span>(<span class="string">"Pi: %f\n"</span>, <span class="identifier">pi</span>);
        <span class="identifier">printf</span>(<span class="string">"Character: %c\n"</span>, <span class="identifier">character</span>);
        <span class="identifier">printf</span>(<span class="string">"Constant Value: %d\n"</span>, <span class="identifier">constantValue</span>);
        <span class="identifier">printf</span>(<span class="string">"String: %s\n"</span>, <span class="identifier">string</span>);
        <span class="identifier">printf</span>(<span class="string">"Sum: %d\n"</span>, <span class="identifier">sum</span>);
        <span class="keyword">return</span> <span class="constant">0</span>;
    }
            </pre>
        </div>
    </body>
</html>
