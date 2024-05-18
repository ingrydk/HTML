<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>
    <h1>Primeiros Passos no HTML</h1>
    <h2>Uma Breve Introdução</h2>
    <p>A seguir será apresentado algumas noções básicas do HTML que foram apresentadas no primeiro módulo do curso iniciante de HTML desenvolvido pela Dio:</p>
    <ul>
        <li><a href="#tags">Tags</a></li>
        <li><a href="#atributos">Atributos</a></li>
        <li><a href="#textos">Textos</a></li>
        <li><a href="#listas">Listas</a></li>
        <li><a href="#links">Links</a></li>
    </ul>
    <h3 id="tags">Tags</h3>
    <ul>
        <li>< html ></li>
            <p>
                Essa tag define que tudo que esta em seu interior é HTML. 
            </p>
        <li>< head ></li>
            <p>Essa tag pré-carrega antes de exibir para o usuário. A tag < title >, utilizada em seu interior, determina o nome da página, ou seja, o título que irá ser apresentado na aba da página.</title></p>    
        <li>< body ></li>
            <p>Tudo que estiver entre esta tag é o que de fato será apresentado ao usuário quando navegar pela página</p>    
        <li>< i ></li>
            <p>É utilizada para tornar o texto ou palvra escolhida em <i>itálico</i>.</p>
        <li>< strong ></li>
            <p>Torna o texto ou palavra selecionada em <strong>negrito</strong>.</p>        
        <li>< u ></li>
            <p>Utilizada para <u>sublinhar</u> uma palavra ou texto.</p>
        <li>< input ></li>
            <p>Essa tag cria um campo para digitação.</p>
            <input type="text"/>            
        <li>< img ></li>
            <p>Utilizada para a adição de imagens.</p>
            <img width="150px" src="https://i.pinimg.com/originals/93/27/e7/9327e7da553a3111959de04fdf2e2eb4.jpg"/>    
    </ul>
    <h3 id="atributos">Atributos</h3>
        <p>Atributos são propriedades que uma <b>tag</b> pode ter.</p>
        <ul>
            <li><i>Atributos Genéricos</i></li>
                <ul>
                    <li><b>id</b></li>
                        <p>É um identificador</p>
                    <li><b>Style</b></li>
                        <p>É voltado para CSS, para que seja formatado da forma que esta sendo definido. </p>
                    <li><b>Class</b></li>
                        <p>É utilizado para padronizar elementos. </p>
                </ul>
            <li><i>Atributos Específicos</i></li>
                <ul>
                    <li><b>Type</b></li>
                        <p>Específico do <i>input</i>. Pode receber valor number, text, color...</p>
                    <li><b>src</b></li>
                        <p>Utilizado para caminho <i>img</i></p>
                    <li><b>Width</b></li>
                        <p>Utilizado para determinar o tamanho de uma imagem, por exemplo.</p>
                </ul>                    
        </ul>
    <h3 id="textos">Textos</h3>
        <p>Tipografias HTML</p>
        <ul>
            <li>h1, h2, h3, h4, h5, h6</li>
                <p>São relacionados aos níveis de texto. O nível h1 seria o maior nível, onde é o título e o h2 seria o substítulo e por ai vai...</p>
                <p><h1>testando</h1></p>
                <p><h2>testando</h2></p>
                <p><h3>testando</h3></p>
                <p><h4>testando</h4></p>            
            <li>< p ></li>
                <p>Corpo do texto. Utilizado para definir parágrafos.</p>
            <li>< blockquote ></li>
                <p>Utilizado para inserir citações</p>
            <li>< mark ></li>
                <p>Realiza a marcação de <mark>texto</mark>.</p>
            <li>< sup ></li>
                <p>Eleve a letra/número tipo isso aqui<sup>2</sup>.</p>
            <li>< sub ></li>
                <p>Essa aqui já faz o contrário<sub>3</sub>.</p>
        </ul>
    <h3 id="listas">Listas</h3>
        <ul>
            <li>< ul ></li>
                <p>Utilizado para listas não ordenadas, como essas que estou fazendo</p>
            <li>< ol ></li>
                <p>Utiliza-se para ordenar listas, como esta abaixo:</p>
                    <ol>
                        <li>Maçã</li>
                        <li>Banana</li>
                        <li>Uva</li>
                    </ol>
            <li>< li ></li>
                <p>Isso é utilizado para determinar os itens das listas.</p>
        </ul>
    <h3 id="links">Links</h3>
        <p>Utiliza-se a tag < a href="ENDEREÇO"> TEXTO < / a > para tornar uma palavra ou frase (no exemplo, seria a "TEXTO") em link.</p> 


</body>
</html>
