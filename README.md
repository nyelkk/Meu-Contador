# Entre datas — contador de dias

Site estático, sem dependências. Registros ficam salvos no `localStorage` do navegador.

## Publicar na Vercel
1. Crie um repositório no GitHub e envie o arquivo `index.html` (na raiz).
2. Na Vercel, escolha **Add New → Project** e importe o repositório.
3. Para um site estático simples, deixe o framework como **Other** e não configure build command. O arquivo `index.html` na raiz será servido diretamente.
4. Clique em **Deploy**.

Também é possível testar localmente abrindo `index.html` no navegador.

## Observação
Os dados são armazenados apenas naquele navegador/dispositivo. Limpar os dados do site/navegador pode apagá-los. Para usar em outro dispositivo, seria necessário adicionar sincronização com banco de dados.
