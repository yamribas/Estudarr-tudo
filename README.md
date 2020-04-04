<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <title>Gerenciador de gastos</title>
    <link rel="stylesheet" href="style1.css">
</head>

<body>
    <header>
        <h1>Quanto você gastou de compras no mês</h1>

    </header>

    <section>
        <div>
            Digite os preços:
            <input type="number" name="quad" id="quad" placeholder="Digite aqui">
            <input type="button" value="Adicionar" id="bt1" onclick="add()">
            <br><select name="list" id="list" size="6"></select>
            <br><br><input type="button" value="Finalizar" id="bt2" onclick="end()">
        </div>

        <div id="result">



        </div>



    </section>

    <footer>

        <p>&copy; Yam Ribas</p>

    </footer>

    <script src="script.js"></script>
</body>

</html>
