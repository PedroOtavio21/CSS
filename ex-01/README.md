# Exercício 1 - Primeira página estilidada
Crie a página abaixo utilizando as propriedades de background e border:

<img src="https://assets-v2.circle.so/bwabuzjcrj32lzuop1boom2pmbdy">

## Dicas
Link da imagem utilizada:
<img src="https://www.viagenspossiveis.com.br/wp-content/uploads/2013/02/C360_2012-11-19-17-59-02.jpg?_gl=1*1qj459a*_ga*MTMzNTYzODYxMy4xNzA2MDIxODE5*_ga_37GXT4VGQK*MTcyOTAwMjM5OC45NDQuMS4xNzI5MDA2MzI4LjAuMC4w*_fplc*VzJ0OUolMkZsMnZoaGN4QW5nb3RIWTk0cDlySSUyQnlESU4lMkZWZzJESmN4S0JKJTJGUDdaY3QxQ0U5Z2R1UDBjcnVta0dwMXZRdG16bnRsQm1oeTRlMXRlNVdUc0NmWWk2RGdmb1daMXduOHVIY2tVcSUyQkZKNjRpVmFVSmpnMElrclpwQSUzRCUzRA..">

Cores utilizadas:
- #248030
- #ffff8c

Código html
``` html
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercício 1</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <h1>Bem-vindo a Fernando de Noronha</h1>
        <p>Descubra o paraíso das praias intocadas e águas cristalinas.</p>
    </header>

    <main>
        <section>
            <h2>Explore as Maravilhosas Praias</h2>
            <p>Visite as praias de Fernando de Noronha e mergulhe nas águas azul-turquesa.</p>
            <a href="#contact">Reserve sua Viagem</a>
        </section>

        <section id="contact">
            <h2>Fale Conosco</h2>
            <p>Entre em contato para mais informações sobre sua viagem.</p>
            <form>
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>

    <footer>
        <p>© 2023 Fernando de Noronha Turismo</p>
    </footer>
</body>

</html>
```