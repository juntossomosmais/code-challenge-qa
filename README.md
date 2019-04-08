# Code Challenge QA Juntos Somos+

Primeiramente, não se preocupe em entregar algo perfeito, sério, não é isso que queremos neste desafio. O propósito dele é simples: queremos conhecer suas abordagens para entender regras de negócios, coletar cenários de testes, fluxos e afins.

Topa?

# O desafio

Trabalhamos com APIs (REST e GraphQL), temos Apps (Android e iOS) e portais web. Contudo para este desafio pedimos o foco em duas situações apenas:

- Levantamento de cenários e automatizações de testes em portais web;
- Validação de APIs.

## 1. Levantamento de cenários e automatizações de testes e portais web

Queremos que você acesse a página da Juntos Somos+, mapeie e automatize os testes das principais funcionalidades dessa página.

- https://www.juntossomosmais.com.br/

Algumas funcionalidades:

* A landing page possui a função `fale conosco` na parte superior direita. Ao ser carregada é mostrado um formulário para preenchimento e posterior envio da mensagem;
* Cadastros para os fomentadores (donos de lojas) e executores (profissionais do mercado como por exemplo pedreiros) de obras.

## 2. Validação de APIs

O site `StackExchange` possui uma documentação de suas APIs disponível no link abaixo:

- https://api.stackexchange.com/docs

Veja por exemplo a parte de [users](https://api.stackexchange.com/docs/users). O que você vê como passível de teste? Quais são os cenários? Tente nos mostrar como testar uma API validando seu contrato e afins.

## Dicas

Abaixo seguem algumas dicas falando de tecnologia e tals que podem endossar ou não a sua resposta ao desafio:

- [Selenium](https://www.seleniumhq.org/) como ferramenta de automatização;
- Embora o teste não tenha algo voltado para Apps (por enquanto), [Appium](https://appium.io/) é uma ferramente bastante utilizada no mercado;
- Uso do [Gherkin](https://docs.cucumber.io/gherkin/) para a criação dos cenários com o auxílio do [Cucumber](https://cucumber.io/);
- Não precisa se prender a ferramentas dedicadas para Java, [Capybara](https://github.com/teamcapybara/capybara) ou qualquer outra ferramenta de mercado (como [Golem](https://github.com/golemhq/golem)) é bem-vinda;
- O teste deve ser executado no Google Chrome. Se preferir, pode ser headless, tanto faz;
- É possível baixar o executável do WebDriver automaticamente por exemplo com a ajuda do [WebDriverManager](https://github.com/bonigarcia/webdrivermanager);
- Evidências que comprovam o funcionamento;
- Uma conhecida ferramenta para avaliar endpoints é o [Rest Assured](https://github.com/rest-assured/rest-assured). [PyRestTest](https://github.com/svanoort/pyresttest) é legal também, mas lembrando: fique a vontade para escolher uma que prefira;
- Uso de conteinerização (por exemplo via [Docker](https://www.docker.com/)).

# Como entregar

Você deve disponibilizar seu código em algum serviço de hospedagem como Bitbucket, GitLab ou GitHub e manter o repositório como privado.

É obrigatório ter um  **README**  com todas as instruções sobre o seu desafio.

Assim que finalizar, nos avise para enviarmos os usuários que devem ter acesso para avaliação.