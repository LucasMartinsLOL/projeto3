# projeto3



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="wisear.css">
</head>
<body>
    <header>
        <h1> site legal</h1>
        <nav>
            <ul>
                <li><a href="witesobre.html">sobre</a></li>
                <li><a href="wiseservicos.html">serviços</a></li>
                <li><a href="wisecontato.html">contato</a></li>
            </ul>
        </nav>
    </header>
<main>
    <section id="home">
        <h1>Bem-vindo ao nosso site!</h1>
        <p>Este é um site de exemplo para demonstrar a estrutura HTML.</p>
    </section>
   <h1> isso é um TESTE</h1>
   <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tenetur adipisci et itaque unde. Nesciunt consequuntur odio alias est ut ad quisquam dignissimos ipsam placeat, dolores officiis deserunt a dolor adipisci!</p>
</body>
</html>

<--comentario, o sobre>



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <main>
<section id="sobre">
        <h1>Sobre</h1>
        <p>Este é um site de exemplo para demonstrar a estrutura HTML.</p>
    </section>
    </main>
</body>
</html>



<-- serviços>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <main>
        <section id="servicos">
            <h1>Serviços</h1>
            <p>Este é um site de exemplo para demonstrar a estrutura HTML.</p>
        </section>
    </main>
</body>
</html>

(-- contato)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <main>
        <section id="contato">
            <h1>Contato</h1>
            <p>Este é um site de exemplo para demonstrar a estrutura HTML.</p>
        </section>
    </main>
</body>
</html>


(CSS)



* style {
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: Arial, sans-serif;
}

body {

    background-color: rgb(99, 112, 179);
    color: black;
    line-height: 1.6;
}

header {
    background-color: #529ac7;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: bold;


}

main {
    color: aqua;
}

section {
    padding: 20px;
    background: white;
    margin: 20px auto;
    max-width: 800px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);


}

article {
    background: white;
    padding: 20px;
    margin-top: 15px;
    border-radius: 5px;
}
aside {
    background: white;
    padding: 20px;
    margin: 15px;
    border-radius: 5px;

}

footer {
    text-align: center;
    background: black;
    color: white;
    padding: 10px 0;
    position: relative;
    bottom: 0;
    width: 100%;
}








