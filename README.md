# servidor-http-nativo

3)Se você remover a linha res.end() de um servidor HTTP em Node.js, a resposta nunca será finalizada. O navegador ficará carregando a página de forma infinita, esperando os dados finais, até que ocorra um tempo limite (timeout) e a conexão seja fechada à força.
