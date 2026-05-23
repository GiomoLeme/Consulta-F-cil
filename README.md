# Consulta Fácil - Projeto de Letramento Digital para Idosos

## Sobre o projeto

O **Consulta Fácil** é um protótipo desenvolvido no contexto da disciplina/projeto de extensão **Práticas Extensionistas em Letramento Digital - UFABC**.

O objetivo principal do trabalho **não era apenas criar um site**, mas sim desenvolver uma solução a partir de um problema social real: a dificuldade que muitos idosos têm para acessar serviços digitais de saúde, especialmente quando precisam entender como marcar consultas, acessar materiais informativos ou utilizar canais digitais de convênios.

Assim, o site funciona como um **meio de apoio** para organizar e apresentar materiais educativos, como e-books e vídeos, de forma simples, acessível e visualmente clara.

## Site publicado

[Acessar o Consulta Fácil](https://marqueconsultafacil.netlify.app/)

## Apresentação do projeto

Os slides da apresentação estão disponíveis em PDF:

[Abrir apresentação do livreto](./Apresenta%C3%A7%C3%A3o%20livreto.pdf)

## Problema social trabalhado

Muitos idosos enfrentam dificuldades no uso de tecnologias digitais, principalmente quando precisam acessar serviços importantes, como agendamento de consultas, informações de convênios ou orientações de saúde.

Essas dificuldades podem envolver:

- Falta de familiaridade com aplicativos e sites;
- Medo de clicar em algo errado;
- Dificuldade para ler textos pequenos;
- Interfaces confusas;
- Dependência de familiares ou terceiros para realizar tarefas digitais;
- Falta de materiais explicativos com linguagem simples.

A partir disso, o projeto buscou criar uma solução que ajudasse idosos a acessar orientações digitais de forma mais clara e autônoma.

## Ideia central

A proposta do projeto foi criar um ambiente simples onde o idoso pudesse:

1. Escolher seu convênio;
2. Acessar um e-book explicativo;
3. Assistir a um vídeo com passo a passo;
4. Ler as informações com uma interface mais amigável;
5. Usar um botão de aumento de fonte para melhorar a acessibilidade.

O site não foi pensado como uma plataforma oficial de saúde ou de convênios, mas como um **protótipo educacional** para apoiar o letramento digital de idosos.

## Relação com a disciplina

A disciplina trabalhou a ideia de que, antes de propor uma solução tecnológica, é necessário entender o problema, o público e o contexto.

Por isso, o foco do projeto não foi simplesmente "fazer um site", mas sim aplicar uma lógica de:

- Observação de um problema real;
- Identificação de uma dificuldade social;
- Definição de um público-alvo;
- Construção de uma solução simples e adequada;
- Teste informal com usuários;
- Reflexão sobre acessibilidade e inclusão digital.

O site foi o produto final, mas o mais importante foi o processo de pensar uma solução digital voltada para pessoas que podem ter barreiras no uso da tecnologia.

## Público-alvo

O público-alvo do projeto foram **idosos com dificuldade no uso de tecnologias digitais**, especialmente aqueles que precisam acessar informações relacionadas a convênios e marcação de consultas.

A interface foi pensada para ser mais simples, com:

- Textos diretos;
- Botões grandes;
- Organização visual clara;
- Poucas etapas;
- Opção de aumentar o tamanho da fonte;
- Materiais em PDF e vídeo.

## Funcionalidades do site

O protótipo possui:

- Página única com navegação simples;
- Seção inicial explicando o objetivo do site;
- Cards com instruções rápidas;
- Escolha entre diferentes convênios;
- Visualização de e-books em PDF;
- Área para vídeos explicativos;
- Botões para abrir e-book e assistir vídeo;
- Botão **"A+ letra maior"** para acessibilidade;
- Layout responsivo para diferentes tamanhos de tela;
- Linguagem simples e voltada ao público idoso.

## Convênios contemplados no protótipo

O site foi estruturado com materiais para três convênios:

- Prevent Senior;
- Santa Casa de Bragança;
- Notredame.

Cada convênio possui uma área própria para exibir o e-book e o vídeo correspondente.

## Tecnologias utilizadas

O projeto foi desenvolvido com tecnologias simples de front-end:

- **HTML5**: estrutura da página;
- **CSS3**: estilização, layout, responsividade e acessibilidade visual;
- **JavaScript**: interação com os botões, seleção de convênios, troca de materiais e aumento da fonte.

O projeto é um site **estático**, ou seja:

- Não possui back-end;
- Não possui banco de dados;
- Não possui sistema de login;
- Não coleta dados dos usuários;
- Pode ser executado localmente no navegador.

## Estrutura do projeto

```text
consulta-facil/
├── index.html
├── _headers
├── hero-casal.png
├── prevent-senior2.pdf
├── santa-casa-bragaca3.pdf
├── notredame2.pdf
├── Apresentação livreto.pdf
└── README.md
```

## Como executar o projeto

Para abrir o site localmente:

1. Baixe ou clone este repositório;
2. Mantenha o arquivo `index.html` na mesma pasta dos PDFs e imagens;
3. Abra o arquivo `index.html` em qualquer navegador.

Exemplo:

```bash
git clone https://github.com/GiomoLeme/Consulta-F-cil.git
cd Consulta-F-cil
```

Depois, basta abrir o arquivo:

```text
index.html
```

## Teste com usuários

O projeto foi testado informalmente com **3 idosos**, com o objetivo de observar se a proposta era compreensível e se a navegação fazia sentido para o público-alvo.

Durante os testes, foram observados pontos como:

- Clareza dos botões;
- Facilidade para escolher o convênio;
- Compreensão da proposta do site;
- Tamanho da fonte;
- Organização das informações;
- Facilidade para abrir o e-book e o vídeo.

## Feedback recebido

Os feedbacks indicaram a importância de manter a interface simples e direta. Alguns pontos percebidos foram:

- A fonte maior ajuda na leitura;
- Botões grandes facilitam a navegação;
- A linguagem precisa ser objetiva;
- O passo a passo em e-book e vídeo torna o conteúdo mais fácil de entender;
- A separação por convênio ajuda o usuário a encontrar o material correto.

## Ajustes realizados após os testes

Após os testes e discussões do grupo, foram feitos ajustes para melhorar a usabilidade do protótipo, como:

- Organização mais clara das seções;
- Destaque para os botões principais;
- Inclusão do botão para aumentar a fonte;
- Estrutura visual mais limpa;
- Materiais separados por convênio;
- Textos mais simples e diretos.

Também foram feitos ajustes técnicos no repositório, como:

- Remoção de PDFs duplicados que não eram usados pelo site;
- Inclusão de headers de segurança para o deploy na Netlify;
- Ajuste dos headers para permitir que os PDFs sejam exibidos dentro da própria página;
- Organização do README com link para o site publicado e para os slides da apresentação.

## Meu papel no projeto

Minha participação no projeto envolveu principalmente:

- Desenvolvimento da estrutura do site;
- Organização visual da página;
- Implementação em HTML, CSS e JavaScript;
- Criação da navegação entre os convênios;
- Integração dos e-books e vídeos;
- Ajustes de acessibilidade, como o botão de aumento de fonte;
- Apoio na organização da proposta do projeto;
- Participação na discussão sobre o problema social e o público-alvo.

## Grupo

O projeto foi desenvolvido em grupo para a disciplina/projeto de extensão.

Integrantes:

- Eduardo Giomo Leme

> Lista de integrantes a completar com os nomes reais do grupo.

## Aprendizados do projeto

Este projeto permitiu desenvolver aprendizados técnicos e sociais.

Na parte técnica, foi possível praticar:

- Estruturação de páginas com HTML;
- Estilização com CSS;
- Interatividade com JavaScript;
- Organização de materiais digitais;
- Criação de uma interface simples e responsiva.

Na parte social e extensionista, o projeto ajudou a compreender que uma solução digital precisa considerar o público que irá utilizá-la. Para idosos, não basta que a tecnologia funcione tecnicamente; ela precisa ser clara, acessível, compreensível e adequada ao contexto real de uso.

## Limitações

Este projeto é um protótipo acadêmico e possui algumas limitações:

- Não é uma plataforma oficial de nenhum convênio;
- Não realiza marcação real de consultas;
- Não possui integração com sistemas de saúde;
- Não possui back-end ou banco de dados;
- A validação foi informal e com um número reduzido de usuários;
- O conteúdo depende dos materiais adicionados manualmente ao projeto.

## Possíveis melhorias futuras

Algumas melhorias possíveis seriam:

- Adicionar mais convênios;
- Melhorar a acessibilidade para leitores de tela;
- Criar versões com contraste aumentado;
- Adicionar tutoriais mais completos;
- Criar uma área de dúvidas frequentes;
- Testar com um número maior de idosos;
- Coletar feedbacks de forma mais estruturada;
- Adaptar melhor o conteúdo para celulares;
- Criar uma versão com navegação ainda mais simplificada.

## Vínculo institucional

Este projeto foi desenvolvido no contexto da **UFABC**, dentro de uma proposta de extensão voltada ao **letramento digital**.

O projeto não representa oficialmente a UFABC, os convênios citados ou qualquer instituição de saúde. Trata-se de um protótipo acadêmico criado com fins educacionais e extensionistas.

## Licença

Este projeto foi desenvolvido para fins acadêmicos e educacionais.

Caso deseje reutilizar ou adaptar este projeto, recomenda-se citar o contexto original e respeitar os materiais utilizados, especialmente PDFs, imagens e vídeos que possam pertencer a terceiros.

## Resumo final

O **Consulta Fácil** é um protótipo de site voltado ao letramento digital de idosos. Seu objetivo é facilitar o acesso a materiais explicativos sobre convênios e marcação de consultas, usando uma interface simples, acessível e organizada.

Mais do que o site em si, o projeto representa uma tentativa de pensar tecnologia a partir de um problema social real, considerando as dificuldades, necessidades e limitações do público idoso.
