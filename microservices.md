# Microservices - Martin Fowler & James Lewis

O artigo "Microservices" de Martin Fowler e James Lewis aborda uma arquitetura de software que vem ganhando destaque nos últimos anos: os microserviços. Essa abordagem propõe o desenvolvimento de aplicações como um conjunto de pequenos serviços independentes, cada um executando em seu próprio processo e comunicando-se através de mecanismos leves, frequentemente APIs HTTP.​

Os autores iniciam contrastando os microserviços com a arquitetura monolítica tradicional, onde uma aplicação é construída como uma única unidade. Nessa estrutura monolítica, qualquer alteração requer a reconstrução e redistribuição de toda a aplicação, o que pode ser um desafio à medida que o sistema cresce em complexidade. Em contrapartida, os microserviços permitem que cada componente seja desenvolvido, implantado e escalado de forma independente, proporcionando maior flexibilidade e agilidade.​

O artigo destaca várias características essenciais dos microserviços:​

- Componentização via Serviços: Diferentemente dos componentes tradicionais que são bibliotecas vinculadas ao tempo de compilação, os microserviços são serviços independentes que se comunicam através de chamadas de rede.​

- Organização em Torno de Capacidades de Negócio: Cada serviço é construído em torno de uma capacidade específica de negócio, permitindo que equipes multifuncionais gerenciem todo o ciclo de vida do serviço, desde a interface do usuário até o armazenamento de dados.​

- Produtos, Não Projetos: A ênfase está em tratar os serviços como produtos completos, com equipes responsáveis por todo o ciclo de vida, em vez de projetos com início e fim definidos.​

- Endpoints Inteligentes e Pipes Simples: Os microserviços enfatizam a inteligência nas extremidades (serviços) e utilizam mecanismos de comunicação simples, como mensagens leves ou APIs RESTful, evitando a complexidade de sistemas de comunicação sofisticados.​

- Governança Descentralizada: As decisões tecnológicas são descentralizadas, permitindo que cada equipe escolha as ferramentas e tecnologias que melhor atendam às necessidades específicas de seu serviço.​

- Gerenciamento de Dados Descentralizado: Cada serviço gerencia seu próprio banco de dados, promovendo a autonomia e a independência entre os serviços.​

- Automação de Infraestrutura: A automação é fundamental para gerenciar a complexidade dos microserviços, desde a construção até a implantação e monitoramento.​

- Projeto para Falhas: Os sistemas devem ser projetados para tolerar falhas, garantindo que a falha de um serviço não comprometa todo o sistema.​

- Projeto Evolutivo: A arquitetura de microserviços suporta a evolução contínua, permitindo que novos serviços sejam adicionados ou modificados sem impactar significativamente o sistema como um todo.​

Na seção final do artigo, Fowler e Lewis discutem o potencial dos microserviços como a direção futura para a arquitetura de software. Eles observam que, embora essa abordagem tenha ganhado destaque e mostrado resultados positivos em várias organizações, é essencial reconhecer que nem todas as empresas possuem a maturidade necessária para adotar essa arquitetura com sucesso. A implementação eficaz de microserviços requer uma cultura organizacional que suporte automação extensiva, integração contínua e entrega contínua. Além disso, é fundamental que as equipes de desenvolvimento tenham autonomia e sejam multifuncionais, alinhando-se à estrutura organizacional que os microserviços promovem. Sem essa base cultural e técnica, a adoção de microserviços pode não resultar nos benefícios esperados e, possivelmente, introduzir complexidades adicionais.​

Ao refletir sobre o artigo e relacioná-lo às disciplinas que cursei até então (4º semestre), percebo que os microserviços exemplificam a aplicação prática de muitos conceitos teóricos que estudamos. Por exemplo, em Programação Modular, aprendemos a importância de dividir sistemas complexos em módulos menores e gerenciáveis, conceito central nos microserviços. Na Engenharia de Requisitos, destacamos a importância de entender e segmentar as necessidades do negócio, alinhando-se à organização dos microserviços em torno de capacidades de negócio. Acho que também é possível dizer que conhecimentos de Sistemas Operacionais e Bancos de Dados são essenciais para compreender a independência de processos e a gestão descentralizada de dados nos microserviços.

Além disso, este é o primeiro artigo totalmente em inglês das tarefas de resenha da disciplina de Projeto de Software. Acabei optando por lê-lo no idioma original e isso não só facilitou a compreensão direta dos conceitos apresentados, mas também enriqueceu meu vocabulário técnico e acadêmico, uma vez que textos científicos frequentemente introduzem termos específicos que não são comuns na linguagem do inglês cotidiano, sob o qual já tenho bastante domínio. Acredito que essa prática de leitura em inglês é essencial para o desenvolvimento acadêmico e profissional pois amplia o acesso a informações atualizadas e especializadas, e portanto acho importante abraçar qualquer oportunidade de praticá-la.

Em suma, o artigo de Fowler e Lewis oferece uma visão abrangente sobre a arquitetura de microserviços, destacando tanto suas vantagens quanto os desafios e pré-requisitos para sua adoção bem-sucedida. Como estudante de Engenharia de Software, reconheço a importância de compreender essa abordagem, especialmente diante da crescente demanda por sistemas escaláveis e flexíveis no mercado atual. No entanto, também é evidente que a adoção de microserviços não é uma solução universal e deve ser considerada cuidadosamente, levando em conta a maturidade organizacional e a prontidão para enfrentar as complexidades associadas a essa arquitetura.