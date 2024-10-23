<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic Layout</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, nav, section, article, aside, footer {
            border: 1px solid #000;
            padding: 10px;
            margin: 5px;
        }
        header, footer {
            background-color: #f4f4f4;
            text-align: center;
        }
        nav {
            background-color: #ddd;
        }
        section {
            float: left;
            width: 60%;
        }
        aside {
            float: right;
            width: 35%;
        }
        article {
            clear: both;
        }
        footer {
            clear: both;
        }
    </style>
</head>
<body>

    <header>
        <h1>Header</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <section>
        <h2>Section</h2>
        <p>This is a section area.</p>
    </section>

    <aside>
        <h2>Aside</h2>
        <p>This is an aside area.</p>
    </aside>

    <article>
        <h2>Article</h2>
        <p>This is an article area.</p>
    </article>

    <footer>
        <p>Footer</p>
    </footer>

</body>
</html>
