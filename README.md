<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Command Line Tool Commands</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f0f0f0;
        }
        h2 {
            color: #333;
            border-bottom: 1px solid #ccc;
            padding-bottom: 5px;
        }
        h3 {
            color: #444;
            margin-top: 20px;
        }
        p {
            margin-bottom: 10px;
        }
        pre {
            background-color: #f5f5f5;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        pre code {
            font-family: Consolas, Monaco, 'Andale Mono', monospace;
        }
        pre.example {
            background-color: #fff;
        }
    </style>
</head>
<body>
    <h2>Commands:</h2>

    <h3>cli</h3>

    <p>Enters the interactive mode of the command-line tool.</p>

    <h4>Usage:</h4>

    <pre><code>cli</code></pre>

    ---

    <h3>project-types ls</h3>

    <p>Lists available project types.</p>

    <h4>Usage:</h4>

    <pre><code>project-types ls</code></pre>

    <h4>Example:</h4>

    <pre class="example"><code>project-types ls</code></pre>

    ---

    <h3>conf-items ls</h3>

    <p>Lists available configuration items.</p>

    <h4>Usage:</h4>

    <pre><code>conf-items ls</code></pre>

    <h4>Example:</h4>

    <pre class="example"><code>conf-items ls</code></pre>

    ---

    <h3>help</h3>

    <p>Displays help information for various commands.</p>

    <h4>Usage:</h4>

    <pre><code>help</code></pre>

    ---

    <h3>help new</h3>

    <p>Displays help information for the new command.</p>

    <h4>Usage:</h4>

    <pre><code>help new</code></pre>

    ---

    <h3>help conf</h3>

    <p>Displays help information for the conf command.</p>

    <h4>Usage:</h4>

    <pre><code>help conf</code></pre>

    ---

    <h3>new</h3>

    <p>Creates a new project with the specified name and type. Optionally, the location can be specified.</p>

    <h4>Usage:</h4>

    <pre><code>new $PROJECT_NAME $PROJECT_TYPE [-loc $DIRECTORY_PATH]</code></pre>

    <h4>Examples:</h4>

    <pre class="example"><code>new MyProject TypeA</code></pre>
    <pre class="example"><code>new MyProject TypeA -loc /path/to/directory</code></pre>

    ---

    <h3>conf</h3>

    <p>Configures an item with the specified name and type. Optionally, the location can be specified.</p>

    <h4>Usage:</h4>

    <pre><code>conf $ITEM $ITEM_TYPE [-loc $DIRECTORY_PATH]</code></pre>

    <h4>Examples:</h4>

    <pre class="example"><code>conf MyItem TypeB</code></pre>
    <pre class="example"><code>conf MyItem TypeB -loc /path/to/directory</code></pre>

    ---

    <h3>exit or quit</h3>

    <p>Exits the command-line tool.</p>

    <h4>Usage:</h4>

    <pre><code>exit</code></pre>
    <pre><code>quit</code></pre>

    ---

    <h3>cls or clear</h3>

    <p>Clears the console screen.</p>

    <h4>Usage:</h4>

    <pre><code>cls</code></pre>
    <pre><code>clear</code></pre>

</body>
</html>
