# Patos COVID-19
Esta é uma simples aplicação escrita em Vuejs para exibir dados sobre o coronavírus na cidade de Patos - PB. Os dados apresentados são: número de casos confirmados, número de mortes, população estimada e taxa de mortalidade (mortes / confirmados).

Você pode adaptar para a sua cidade! É muito simples!

Link da aplicação: https://romulorodrigues.github.io/patos-covid-19/

# Uso

- Baixe o repositório como arquivo zip ou faça um clone;
- Instale as dependências (npm install);
- No método getData do componente Home, altere o "state" na url para o seu estado. No meu caso, usei PB (Paraíba);
- Ex: https://brasil.io/api/dataset/covid19/caso/data?is_last=True&state=PB.
```
getData(){
      axios.get("https://brasil.io/api/dataset/covid19/caso/data?is_last=True&state=SEU_ESTADO")
      ...
}
```
- Altere as imagens e o layout do projeto para a sua realidade.

# Dados

Mais informações sobre a API: https://github.com/turicas/covid19-br/blob/master/api.md

Fonte dos dados: Secretarias de Saúde das Unidades Federativas, dados tratados por Álvaro Justen e colaboradores/Brasil.IO.

Brasil.IO: boletins epidemiológicos da COVID-19 por município por dia, disponível em: https://brasil.io/dataset/covid19/ (última atualização: 12-05-2020, acesso em 13-05-2020).

# Licença

The MIT License (MIT)

Copyright (c) [2020] [Rômulo Rodrigues de Morais Bezerra]

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# Dúvidas?
Em caso de dúvidas mande um e-mail para romulorodrigue@gmail.com

# Contribuições

Achou e corrigiu um bug ou tem alguma feature em mente e deseja contribuir?

- Faça um fork.
- Adicione sua feature ou correção de bug.
- Envie um pull request no GitHub.

