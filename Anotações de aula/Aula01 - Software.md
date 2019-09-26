### Aula01 - Software
> É um produto projetado e construído para resolver um dado problema cuja solução precisa ser automatizada e é composto
> por um conjunto de **programas, procedimentos, dados e documentação** associados.

`Desenvolver software é complexo.`
A complexidade deriva de várias fontes:
* Complexidade do problema;
* Relacionamento com diferentes stakeholders (clientes, usuários, especialistas, desenvolvedores, etc.);
* Dependência de diferentes tecnologias (linguagens, BD, redes, etc.);
* Restrições de tempo e dinheiro;
* Constantes modificações nos negócios e na sociedade.

O desenvolvimento de um produto de software deve minimizar *falhas*.

Falhas:
* Podem causar apenas aborrecimento;
* Ou, podem custar bastante tempo e dinheiro;
* Ou, podem ameaçar a vida das pessoas.

Exemplo de Falha:
* Therac-25 (Anos 80)
 * Máquina de radioterapia, controlada por computador, utilizada para aplicação de doses de radiação em pacientes;
 * Controle de segurança, antes feito por travas mecânicas, passou a ser realizado por software;
 * Foram reportados pelo menos 15 acidentes (morte e sequelas).
 * Os Acidentes de Therac-25
 * http://sunnyday.mit.edu/papers/therac.pdf

* Ariane 5 (1996)

### Como minimizar as falhas em software?

* A resposta é multifacetada;
* Pressupõe o desenvolvimento profissional de software;
* Atendimento as orientações da Engenharia de Software.

### Engenharia de Software
```
O foco da engenharia de software está em todos os aspectos da produção de software, desde os estágios iniciais da especificação do sistema até sua manutenção, quando o sistema já está em uso.
```

#### Área de Conhecimento da Engenharia de Software:

* Requisitos

```
Aquisição, análise, especificação e gestão de requisitos de software.
```

* Design

```
Trata de questões relacionadas a solução do problema: definição da arquitetura, componentes, interfaces e outras características do software.
```

* Construção
```
Trata das questões relacionadas a implementação do software, levando em
consideração as linguagens de programação, testes, reuso, debugging, qualidade da implementação e integração.
```

* Teste
```
Verificação dinâmica do comportamento do programa através do uso de um conjunto finito de casos de teste.
```

* Manutenção

```
Trata do planejamento, coordenação, medição, monitoração e controle do projeto, levando em consideração aspectos como cronograma, riscos e recursos humanos.
```

* Gerência de Configuração

```
Trata de questões relacionadas a definição, implementação, avaliação, medição, gerenciamento, mudança e melhoria do processo de software.
```

* Gerência de Projeto

```
Trata do planejamento, coordenação, medição, monitoração e controle do projeto, levando em consideração aspectos como cronograma, riscos e recursos humanos.
```

* Processo

```
Trata de questões relacionadas a definição, implementação, avaliação, medição, gerenciamento, mudança e melhoria do processo de software.
```

* Ferramentas e Métodos

```
Trata sobre estratégias, ferramentas e métodos que aumentem a produtividade dos desenvolvedores enquanto reduzem a
ocorrência de falhas no desenvolvimento.
```

* Qualidade

```
Trata de um conjunto de atividades relacionadas com a garantia da qualidade de software, tais como, requisitos de qualidade, caracterização de defeito, métricas de qualidade, verificação e validação e técnicas para gerenciamento da qualidade.
```

Leitura
- Básica
  - Livro: Engenharia de Software de Ian Sommerville. 9ª. Ed. São Paulo: Pearson, 2011.
  - Capítulo 1
- Complementar
  - Artigo: A View of 20th and 21st Century Software Engineering de Barry Boehm. Disponível em: http://goo.gl/fgf8Gr

## EXERCÍCIO PRÁTICO - [01]

**01. Processo de negócio e processo de desenvolvimento de software significam a mesma coisa? Justifique sua resposta.**
```
R: Não. Processos de negócio estão relacionados ao fluxo das atividades para atingir um fim específico dentro da empresa.Ex: Processo de negócio para aquisição de material de consumo. Processo de desenvolvimento de software está relacionado a confecção do software que resolve algum problema.
```

**02. Observe a afirmação: “Modelo de Processo de Software e Processo de Software são denominações diferentes, no entanto possuem o mesmo significado”. Esta afirmação é verdadeira ou falsa? Justifique sua resposta.**
```
R: Essa afirmação é falsa, pois o modelo é uma abstração do processo, uma representação simplificada do processo utilizadas para explicar diferentes abordagens de desenvolvimento.O processo em si são as diversas execuções baseadas no modelo.
```

**03. Quais as diferenças entre o modelo cascata e o espiral.**
```
R: No modelo em cascata as atividades são feitas em sequência, já no modelo espiral, cada volta na espiral representa uma fase do processo de software.
```

**04. Existem muitas maneiras de os desenvolvedores decidirem como organizar odesenvolvimento em versões. As duas abordagens mais populares são o desenvolvimento incremental e o desenvolvimento iterativo. Explique cada um
deles.**
```
R: No desenvolvimento incremental alguns dos incrementos desenvolvidos são entregues ao cliente e implantados para uso em um ambiente operacional. No desenvolvimento iterativo o cliente só terá o resultado final do software.
```

**05. Observe a afirmação: “Adotar um modelo de processo pautado numa abordagem incremental é melhor que uma abordagem tradicional (em cascata, por exemplo) para sistemas pessoais e e-commerce”. Esta afirmação é verdadeira ou falsa?
Justifique sua resposta.**
```
R: Acredito que sim, pois os requisitos nesses tipos de sistemas são pouco conhecidos e  irão variar bastante e o software deve ser flexível a mudanças para atender as necessidades do cliente.
```

**06. Em quais tipos de sistemas ou contextos o desenvolvimento e entrega incrementais não são a melhor abordagem?**
```
R: Em sistemas críticos ou formais onde as partes do sistema são bem compreendidas e só fazem sentido quando entregues por completo.
```

**07. Cite algumas situações nas quais a utilização de protótipos é adequada.**
```
R: Para validar um conceito ou funcionalidade nova, para validar uma versão inicial do sistema, para descobrir mais sobre o problema e suas soluções e para ajudar a antecipar mudanças.
```

 ## Capítulo 2 - Processos de Software
Um processo de software é um conjunto de atividades relacionadas que levam à produção de um produto de software.
### Atividades fundamentais para a engenharia de software.
* Especificação de sofwate, Projeto e implementação de software, Validação de software, Evolução de software.

## Modelo de processo de software
Um modelo de processo de software é uma representação simplificada de um processo de software. São abstrações que podem ser utilizadas para explicar diferentes abordagens de desenvolvimento de software.Um modelo possui fases.

### Modelo em Cascata (Processo dirigido a planos)
Principais estágios do modelo em cascata = Análise e definição de requisitos, Projeto de sistema e software, Implementação e teste unitário, integração e teste de sistema, Operação e manutenção(fase mais longa).
Atividades fundamentais = Processo de especificação, desenvolvimento, validação e evolução.
Fases = Especificação de requisitos, projeto de software, implementação, teste.
O planejamento e a programação das atividades do processo começam antes.
O estaǵio seguinte só inicia com a conclusão do estágio atual.

### Desenvolvimento Incremental
Essa abordagem intercala as atividades de modo que cada versão adiciona funcionalidade à anterior.

### Engenharia de Software Orientado a Reuso.
Essa abordagem é baseada na existência de um número significativo de componentes reusáveis.