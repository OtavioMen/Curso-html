# Curso-html
Curso de formação da Dio de Html basico
"""###
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aula de html basico</title>
</head>

<body>
    <h1 id="voltar"> HTML BASICO </h1>
    <hr />
    <ul>
        <li><a href="#Estrutura-basica">Estrutura basica</a></li>
        <li><a href="#Doctype">Doctype</a></li>
        <li><a href="#Head">Head</a></li>
        <li><a href="#Body">Body</a></li>
    </ul>

    <h2 id="Estrutura-basica">Estrutura básica</h2>
    <h3>Iniciando o código básico de HTML</h3>
    <p>O documento HTML sempre inicia com o que chamamos de estrutura básica. Esta estrutura é quase que imutável.
        Sempre será dessa forma e você sempre, sempre começará seu HTML começando por esse código. Geralmente os
        editores como o Sublime Text já tem atalhos para iniciar os documentos HTMLs com essa estrutura, logo, você não
        precisa se preocupar em decorá-la, mas é bom que faça. Veja abaixo como ela se inicia:</p>
    <ol>
        <li>
            < !DOCTYPE html>
        </li>
        <li>
            < html lang="pt-br">
        </li>
        <li>
            < head>
                < /li>
        <li>
            < title>Título da página< /title>
                    < /li>
        <li>
            < meta charset="utf-8">
                < /li>
        <li>
            < /head>
                < /li>
        <li>
            < body>
                < /li>
        <li> Aqui vai o código HTML que fará seu site aparecer.</li>
        <li>
            < /body>
                < /li>
        <li>
            < /html>
                < /li>
    </ol>
    <p>É possível compreender o documento em HTML de uma maneira muito simples, através de uma divisão de blocos das
        tags essenciais, conforme a a seguinte estrutura:</p>
    <ul>
        <li>Definição do documento (doctype)</li>
        <li>Cabeça (head)</li>
        <li>Corpo (body)</li>
    </ul>
    <a href="#voltar">voltar</a>
    <h2 id="Doctype">Doctype - Definindo o documento</h2>
    <p>Uma coisa importante: SEMPRE deve existir o doctype, que é este código < !DOCTYPE html>.</p>
    <br>
    <p>O doctype não é uma tag HTML, mas uma instrução para o navegador e outros programas que podem ler seu site, que o
        código encontrado ali é um código HTML. Assim eles sabem o que fazer para mostrar seu site da melhor forma
        possível. Lembre-se: o doctype é OBRIGATÓRIO e deve ser sempre a PRIMEIRA LINHA do seu documento.</p>
        <a href="#voltar">voltar</a>
        <br>
    <h2 id="Head">HEAD</h2>
    <p>Contém informações que não são transpostas visivelmente para o usuário/leitor do documento. São dados implícitos,
        de uso e controle do documento: vinculação com outros arquivos, aplicação de lógica de programação de scripts e
        metadados. Na prática, todo o conteúdo do cabeçalho fica delimitado entre a abertura e fechamento tag
        <strong>head</strong>.</p>
        <a href="#voltar">voltar</a>
    <br>
    <h2 id="Body">BODY</h2>
    <p>Trata-se do documento em si, ou seja, a informação legível para o usuário/leitor do documento. É todo e qualquer
        texto que se deseja apresentar, assim como toda e qualquer forma de mídia de saída (imagens, sons,
        miniaplicativos embutidos, conteúdo multimídia, etc). Além disso, toda a apresentação de entrada de dados
        (formulários) também se aplica neste seção do documento. Na prática, o corpo do documento é delimitado pelo par
        de tags <b>
            < body>
        </b> e <b>
            < /body>
        </b>.</p>
    <br>
    <p>Este é o preceito básico que deve estar muito bem claro para você: onde as marcações se aplicam, e quais são os
        resultados deste modelo. Por exemplo: se vocês deseja informar conteúdo textual para saída legível ao usuário do
        seu sistema web, esta marcação deverá obrigatoriamente estar no bloco do corpo da página. Ainda: para definir
        qual o tipo de codificação da página (uma meta informação do documento), esta deve obrigatoriamente estar
        marcada no cabeçalho do mesmo documento.</p>
    <br>
    """###
    <p>Dentro do elemento BODY sua estrutura de página terá os elementos semânticos da construção da sua página, onde
        serão declarados e identificados cabeçalhos, rodapé, conteúdo principal, etc.</p>
        <a href="#voltar">voltar</a>
</body>

</html>
