# Miniguia de Estudo — arquitetura de software

> Este projeto reúne uma pesquisa feita com apoio do NotebookLM sobre Arquitetura de software com ia.

## 1. Contexto e objetivos

### Qual é o assunto?

Escolhi estudar arquitetura de software por conta do avanço da IA, muitas empresas já espera que o desenvolvedor mesmo iniciante tenha experiencia com ia.

### O que quero aprender?

- [ ] Entender o que é Spec Driven Development(SDD).
- [ ] Identificar os conceitos mais importantes sobre arquitetura de software + IA.
- [ ] Comparar SDD com Vibe coding.
- [ ] Conseguir explicar o tema com minhas próprias palavras.

## 2. Curadoria de fontes

Estas foram as fontes abertas selecionadas e enviadas ao NotebookLM:

## Texto

1.link: <https://www.softdesign.com.br/blog/desenvolvimento-ou-consultoria-em-arquitetura-de-software-como-escolher/>

2.link: <https://pt.wikipedia.org/wiki/Arquitetura_de_software>

3.link: <https://www.reddit.com/r/softwarearchitecture/comments/1apbndt/does_software_architecture_knowledge_make_someone/?tl=pt-br>

## Video

1.link: <https://www.youtube.com/watch?v=4svHZWR-_OE>
2.link: <https://www.youtube.com/watch?v=jIfc-mNj-6M>
3.link: <https://www.youtube.com/watch?v=XtECLGkGrmM>
4.link: <https://www.youtube.com/watch?v=ZM8WW8_HEeE>
5.link: <https://www.youtube.com/watch?v=SWgCLOW1bCE>

## 3. Engenharia de prompts e cicatrizes

### Perguntas estratégicas

1. O que é Arquitetura de software? Explique para uma pessoa iniciante.
2. Quais são os 5 conceitos mais importantes nas fontes?
3. Faça um resumo em etapas, sem inventar informações e citando as fontes.
4. Compare Hexagonal e Monolítico em uma tabela.
5. Crie 5 perguntas para testar se eu entendi o assunto.

### Registro de uma resposta

> Prompt usado:O que é Arquitetura de software? Explique para uma pessoa iniciante

Resposta obtida: Para quem está a começar, a arquitetura de software é a visão macro de um sistema. Enquanto a programação foca-se em escrever código para funcionalidades específicas, a arquitetura define a estrutura global: como as partes se ligam, como os dados são armazenados e como o sistema se comporta perante exigências de crescimento.

O seu principal objetivo é garantir que o software seja fácil de entender, de manter e de implementar. Sem uma arquitetura definida, o sistema pode tornar-se uma "Grande Bola de Lama" (Big Ball of Mud), onde todos os componentes estão misturados de tal forma que é quase impossível fazer alterações sem quebrar algo.

Existem três pilares fundamentais que deves conhecer:
Decisões e Trade-offs: Na arquitetura, quase nunca há uma solução perfeita, mas sim escolhas equilibradas. Por exemplo, uma tecnologia pode ser muito rápida para o utilizador, mas muito cara para a empresa manter.

Requisitos: Ela deve responder tanto a necessidades técnicas (como segurança e performance) quanto a necessidades do negócio (o que a empresa precisa de entregar).

Separação de Responsabilidades: Uma boa arquitetura isola as regras do negócio das ferramentas técnicas (como bases de dados ou frameworks)
. Assim, se precisares de mudar de base de dados, não tens de reescrever toda a lógica da aplicação.

> Fontes citadas pela IA:
> Definições e Fundamentos: A visão macro sobre estrutura, requisitos e a importância da comunicação veio do vídeo da Alura e da explicação da Fernanda Kipper sobre manutenção e deploy

Trade-offs e Decisões: O conceito de que não há "bala de prata" e o equilíbrio entre custos e benefícios baseou-se nos vídeos da Alura e no trabalho acadêmico da PUC Goiás

Padrões (Monolítico, Hexagonal e Camadas): A comparação detalhada e as definições técnicas destes estilos foram retiradas do trabalho de Liandra Oliveira

IA e Spec Driven Development (SDD): Todo o fluxo de 6 etapas, o uso de especificações como contratos e o combate ao "VibeCoding" basearam-se nos vídeos de O Novo Programador e da Cod3r

## 4. Miniguia final

### Resumo em uma frase

Arquitetura de Software é como um dev projeta sua construnção, igual como um arquiteto projeta a casa que vai sair do papel.

### Resumo estruturado

#### 4.1 Conceito principal

O seu principal conceito é garantir que o software seja fácil de entender, de manter e de implementar.

#### 4.2 Como funciona

1. Decisões e Trade-offs — Na arquitetura, quase nunca há uma solução perfeita, mas sim escolhas equilibradas. Por exemplo, uma tecnologia pode ser muito rápida para o utilizador, mas muito cara para a empresa manter.

2. Requisitos — Ela deve responder tanto a necessidades técnicas (como segurança e performance) quanto a necessidades do negócio (o que a empresa precisa de entregar).

3. Separação de Responsabilidades — Uma boa arquitetura isola as regras do negócio das ferramentas técnicas (como bases de dados ou frameworks). Assim, se precisar de mudar de base de dados, não tem que reescrever toda a lógica da aplicação.

### Glossário

| Termo                   | Explicação simples                                                                                                                                  |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Arquitetura de Software | Organização global de um sistema incluindo a relação entre subsistemas, componentes e a definição de padrões técnicos para segurança e performance. |
| Trade-off               | Situação de escolha conflituosa onde se perde algo em troca de um ganho em outra área (ex: performance vs. custo). |
| Monolito                | Padrão onde o aplicativo é construído como uma unidade única e indivisível, compartilhando o mesmo espaço de memória e recursos. |
| Microsserviços          | Coleção de serviços pequenos e autônomos que implementam funcionalidades específicas e comunicam-se via APIs bem definidas. |
| Escalabilidade          | Capacidade de um sistema lidar com o aumento de demanda ou carga de forma sustentável e eficiente. |

### Prompts reutilizáveis

```text
Explique Arquitetura de software para uma pessoa iniciante usando apenas as fontes anexadas. Defina os termos técnicos e dê um exemplo cotidiano.
```

```text
Resuma arquitetura de software em 5 tópicos. Para cada tópico, informe qual fonte sustenta a explicação. Não invente informações e sinalize o que não estiver nas fontes.
```

```text
Crie uma tabela comparando Spec Driven Development (SDD) e Arquitetura de Software, incluindo definição, objetivo, vantagens, limitações e um exemplo de uso.
```

```text
Faça um quiz com 10 perguntas sobre arquitetura de software, misturando questões fáceis e médias. Mostre o gabarito somente depois das perguntas e explique cada resposta.
```
