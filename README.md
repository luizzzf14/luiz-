<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Como Programar em HTML - Guia Criativo</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(120deg, #6a11cb, #2575fc);
            color: #fff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }

        header {
            text-align: center;
            margin-bottom: 30px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.5);
        }

        header p {
            font-size: 1.2rem;
            font-style: italic;
        }

        main {
            background-color: rgba(255, 255, 255, 0.15);
            border-radius: 15px;
            max-width: 900px;
            padding: 30px;
            box-shadow: 0 0 15px rgba(0,0,0,0.3);
        }

        section {
            margin-bottom: 40px;
        }

        h2 {
            border-bottom: 3px solid #fff;
            padding-bottom: 10px;
            margin-bottom: 20px;
            font-size: 2rem;
        }

        p {
            font-size: 1.1rem;
            line-height: 1.6;
            margin-bottom: 15px;
        }

        code {
            background: #222;
            padding: 3px 6px;
            border-radius: 5px;
            font-family: 'Courier New', Courier, monospace;
            font-weight: bold;
            color: #9cff9c;
        }

        /* Botão estiloso */
        .btn {
            background: #fff;
            color: #2575fc;
            font-weight: bold;
            padding: 12px 20px;
            border: none;
            border-radius: 30px;
            cursor: pointer;
            box-shadow: 0 4px 12px rgba(255,255,255,0.5);
            transition: 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }

        .btn:hover {
            background: #e0e0e0;
            color: #1a52d8;
        }

        /* Imagens centralizadas e responsivas */
        .imagem {
            display: block;
            margin: 15px auto;
            max-width: 100%;
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
        }

        /* Lista estilizada */
        ul {
            list-style: inside disc;
            margin-left: 20px;
            font-size: 1.1rem;
        }

        /* Rodapé */
        footer {
            margin-top: auto;
            padding: 20px;
            text-align: center;
            font-size: 0.9rem;
            color: #ccc;
        }

    </style>
</head>
<body>

    <header>
        <h1>Aprenda a Programar em HTML</h1>
        <p>Um guia simples, visual e divertido para começar</p>
    </header>

    <main>
        <section>
            <h2>O que é HTML?</h2>
            <p>HTML (HyperText Markup Language) é a linguagem básica da web. Ela serve para estruturar o conteúdo das páginas que você vê na internet.</p>
            <img class="imagem" src="https://cdn.pixabay.com/photo/2017/05/10/20/28/code-2303055_1280.png" alt="Código HTML" />
        </section>

        <section>
            <h2>Elementos Básicos</h2>
            <p>O HTML usa <strong>tags</strong> para organizar o conteúdo. Por exemplo:</p>
            <ul>
                <li><code>&lt;h1&gt;</code> para títulos grandes;</li>
                <li><code>&lt;p&gt;</code> para parágrafos;</li>
                <li><code>&lt;a&gt;</code> para links;</li>
                <li><code>&lt;img&gt;</code> para imagens.</li>
            </ul>
            <img class="imagem" src="https://cdn.pixabay.com/photo/2016/11/19/14/00/code-1839406_1280.png" alt="Exemplo de código HTML" />
        </section>

        <section>
            <h2>Exemplo Prático</h2>
            <p>Veja um exemplo simples de HTML que cria uma página básica:</p>
            <pre style="background:#222; padding:15px; border-radius:10px; overflow-x:auto;">
&lt;!DOCTYPE html&gt;
&lt;html&gt;
  &lt;head&gt;
    &lt;title&gt;Minha Primeira Página&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;h1&gt;Olá, Mundo!&lt;/h1&gt;
    &lt;p&gt;Este é meu primeiro site em HTML.&lt;/p&gt;
  &lt;/body&gt;
&lt;/html&gt;
            </pre>
        </section>

        <section>
            <h2>Quer experimentar?</h2>
            <p>Você pode criar seu próprio arquivo HTML no seu computador e abrir no navegador para ver funcionando.</p>
            <a href="https://codepen.io/pen/" target="_blank" class="btn">Testar Online no CodePen</a>
        </section>
    </main>

    <footer>
        <p>Feito com 💜 por Felipe</p>
    </footer>

</body>
</html>
