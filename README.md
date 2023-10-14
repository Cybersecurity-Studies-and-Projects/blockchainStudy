# Estudos sobre Blockchain - Etapa 1 - Teoria e Fundamentos

## Estudar os fundamentos sobre Blockchain

### Conceitos da tecnologia Blockchain

Blockchain é um livro-razão seguro, compartilhado e distribuído que facilita o processo de gravação e rastreamento de recursos sem a necessidade de confiança em uma autoridade central. Blockchain é o nome de uma tecnologia de informação relacionada à moeda virtual bitcoin e nas negociações das criptomoedas. O significado de blockchain em português é “corrente de blocos”, por causa da junção das palavras “bloco” (block) e “corrente” (chain).

O que distingue esse livro-razão dos bancos de dados ou softwares tradicionais é a sua natureza de resistência à adulteração, pois a alteração dos dados de um bloco requer a manipulação de todos os outros blocos anteriores. Cada bloco contém um conjunto de transações validadas por um algoritmo de consenso, um identificador único chamado hash e o hash do bloco anterior, criando uma ligação criptográfica entre eles. A ordem dos blocos é mantida por uma rede peer-to-peer, onde cada nó possui uma cópia do livro-razão e participa do processo de validação.

Blockchain é uma tecnologia que permite a criação de aplicações descentralizadas, que não dependem de intermediários para funcionar. Essas aplicações podem envolver diferentes tipos de recursos, como dinheiro, propriedade, identidade, informação, etc. Alguns exemplos de aplicações baseadas em blockchain são: criptomoedas, contratos inteligentes, plataformas de financiamento coletivo, sistemas de votação, registros de propriedade intelectual, etc.

### Fundamentos tecnológicos e de criptografia

Blockchain é uma tecnologia que combina conceitos e ferramentas de diferentes áreas da computação, como bancos de dados distribuídos, redes peer-to-peer e criptografia. A seguir, serão apresentados alguns dos fundamentos tecnológicos e de criptografia que sustentam o funcionamento do blockchain.

#### Bancos de dados distribuídos

Um banco de dados distribuído é um sistema que armazena e gerencia dados em vários nós conectados por uma rede. Cada nó pode ter uma cópia completa ou parcial dos dados, dependendo do modelo de distribuição. O objetivo de um banco de dados distribuído é garantir a disponibilidade, a consistência e a tolerância a falhas dos dados.

Um banco de dados distribuído pode ser classificado em dois tipos: homogêneo ou heterogêneo. Um banco de dados homogêneo é aquele em que todos os nós usam o mesmo software e o mesmo esquema de dados. Um banco de dados heterogêneo é aquele em que os nós podem usar softwares ou esquemas diferentes.

Um banco de dados distribuído também pode ser classificado em dois tipos: centralizado ou descentralizado. Um banco de dados centralizado é aquele em que existe um nó mestre que coordena as operações dos outros nós. Um banco de dados descentralizado é aquele em que não existe um nó mestre e todos os nós são iguais.

Blockchain é um tipo especial de banco de dados distribuído descentralizado e homogêneo, onde cada nó possui uma cópia idêntica do livro-razão e segue as mesmas regras para validar as transações.

#### Redes peer-to-peer

Uma rede peer-to-peer (P2P) é uma rede onde cada nó pode se comunicar diretamente com qualquer outro nó sem a necessidade de um servidor central. Cada nó pode atuar como cliente ou servidor, dependendo da situação. Uma rede P2P pode ser estruturada ou não estruturada. Uma rede estruturada é aquela em que os nós são organizados em uma topologia específica, como anel, árvore, grade, etc. Uma rede não estruturada é aquela em que os nós se conectam de forma aleatória.

Uma rede P2P pode ser classificada em dois tipos: pura ou híbrida. Uma rede pura é aquela em que todos os nós são iguais e não há nenhum nó especial. Uma rede híbrida é aquela em que existem alguns nós especiais que desempenham funções específicas, como indexação, roteamento, cache, etc.

Blockchain é um tipo de rede P2P pura e não estruturada, onde cada nó pode se conectar a qualquer outro nó e não há nenhum nó especial. Cada nó possui uma cópia do livro-razão e participa do processo de validação das transações.

#### Criptografia

Criptografia é a ciência que estuda os métodos de proteção da informação contra acessos não autorizados ou alterações indevidas. A criptografia usa técnicas matemáticas para transformar a informação em um formato ilegível para quem não possui a chave secreta para decifrá-la. A criptografia pode ser classificada em dois tipos: simétrica ou assimétrica. A criptografia simétrica é aquela em que a mesma chave é usada para cifrar e decifrar a informação. A criptografia assimétrica é aquela em que existem duas chaves diferentes: uma pública e uma privada. A chave pública pode ser usada para cifrar a informação, mas somente a chave privada pode decifrá-la.

Blockchain usa criptografia para garantir a segurança, a integridade e a autenticidade das transações e dos blocos. Algumas das técnicas criptográficas usadas pelo blockchain são:

- Hash: uma função matemática que transforma qualquer dado em um valor fixo e único, chamado hash ou digest. O hash tem as propriedades de ser irreversível (não é possível obter o dado original a partir do hash) e resistente a colisões (é muito improvável que dois dados diferentes gerem o mesmo hash). Blockchain usa hash para identificar os blocos e as transações, bem como para verificar a integridade dos dados.

- Assinatura digital: um mecanismo que permite ao remetente de uma mensagem provar sua identidade e sua autoria, bem como ao destinatário verificar a integridade e a origem da mensagem. A assinatura digital usa criptografia assimétrica para gerar um valor único, chamado assinatura, a partir da mensagem e da chave privada do remetente. O destinatário pode verificar a validade da assinatura usando a mensagem e a chave pública do remetente.

- Prova de trabalho: um protocolo que exige que o emissor de uma mensagem realize um trabalho computacional difícil, mas verificável, para provar seu comprometimento com a rede. O trabalho consiste em encontrar um valor que satisfaça uma condição matemática envolvendo o hash da mensagem. O receptor pode verificar facilmente se o valor encontrado é válido. Blockchain usa prova de trabalho para garantir o consenso entre os nós sobre a ordem dos blocos e evitar ataques à rede.

### Tokens e Criptomoedas

#### Tokens

Tokens são recursos digitais que representam algo além de si mesmos, como direitos, propriedades, serviços, etc. Tokens podem ser emitidos por qualquer entidade na rede, sem a necessidade de uma autoridade central. Tokens podem ser classificados em dois tipos: fungíveis ou não fungíveis. Tokens fungíveis são aqueles que possuem as mesmas características e podem ser substituídos entre si. Tokens não fungíveis são aqueles que possuem características únicas e não podem ser substituídos entre si.

Tokens podem ser implementados por meio de contratos inteligentes, que são programas executados na blockchain que definem as regras de criação, distribuição e transferência dos tokens. Existem alguns padrões de contratos inteligentes para tokens, como o ERC-20 e o ERC-721, que facilitam a interoperabilidade entre diferentes aplicações baseadas em blockchain. Alguns exemplos de tokens são: Tether (USDT), um token que representa o dólar americano; CryptoKitties, um token não fungível que representa um gato digital colecionável; e Decentraland (MANA), um token que permite aos usuários comprar e vender terras virtuais em uma plataforma de realidade virtual.

#### Criptomoedas

Criptomoedas são recursos digitais que representam unidades de valor intrínseco, como moedas ou commodities. Criptomoedas são emitidas por um protocolo da rede, sem a necessidade de uma entidade emissora. Criptomoedas podem ser classificadas em dois tipos: nativas ou derivadas. Criptomoedas nativas são aquelas que possuem sua própria blockchain, como Bitcoin, Ethereum e Litecoin. Criptomoedas derivadas são aquelas que dependem de outra blockchain para existir, como Dai, Maker e Wrapped Bitcoin.

Criptomoedas podem ser implementadas por meio de um algoritmo de consenso, que é um conjunto de regras que determina como os nós da rede validam as transações e criam novos blocos. Existem vários tipos de algoritmos de consenso, como prova de trabalho (PoW), prova de participação (PoS), prova de autoridade (PoA), etc. Alguns exemplos de criptomoedas são: Bitcoin (BTC), a primeira e mais popular criptomoeda, que usa PoW para garantir a segurança da rede; Ethereum (ETH), a segunda maior criptomoeda, que usa PoW e PoS para suportar contratos inteligentes e aplicações descentralizadas; e Ripple (XRP), uma criptomoeda que usa um protocolo de consenso distribuído para facilitar transações internacionais.

### Hyperledger Foundation

Hyperledger é um projeto de código aberto iniciado pela Fundação Linux em 2015 para desenvolver a colaboração global de tecnologias de blockchain. Hyperledger visa criar plataformas e ferramentas padronizadas, interoperáveis e confiáveis para apoiar o desenvolvimento de aplicações baseadas em blockchain para diversos setores e casos de uso. Hyperledger é composto por vários projetos, cada um com seu próprio foco e objetivo. Alguns dos principais projetos do Hyperledger são:

- **Hyperledger Besu**: uma plataforma DLT permissionada e pública baseada no Ethereum, que suporta contratos inteligentes escritos em Solidity e Vyper. Hyperledger Besu é compatível com as redes Ethereum Mainnet, Ropsten, Rinkeby e Goerli. Hyperledger Besu também permite a criação de redes privadas com diferentes configurações de consenso, privacidade e permissão.

- **Hyperledger Cactus**: uma plataforma de interoperabilidade multifacetada que se baseia nas características técnicas de ponta do Hyperledger Cactus e do Weaver, um Laboratório Hyperledger. Hyperledger Cactus permite aos usuários integrar diferentes blockchains em uma única rede, permitindo a transferência segura e consistente de ativos entre elas. Hyperledger Cactus usa plugins para conectar diferentes blockchains, como Bitcoin, Ethereum, Fabric, Corda, etc. Hyperledger Cactus também fornece uma interface gráfica para monitorar e gerenciar as transações entre as blockchains.

- **Hyperledger Fabric**: uma plataforma DLT permissionada, modular, configurável e de código aberto, desenvolvida pela IBM e pela Digital Asset. Hyperledger Fabric implementa o conceito de contratos inteligentes, chamados chaincodes, que podem ser escritos em Go, Java ou Node.js. Hyperledger Fabric também permite a criação de canais privados entre os participantes da rede, garantindo a confidencialidade das transações.

### Arquitetura de redes Blockchain

Uma rede blockchain é composta por vários elementos que interagem entre si para garantir o funcionamento da tecnologia. A seguir, serão apresentados alguns dos principais elementos da arquitetura de redes blockchain:

- **Nó**: é uma entidade que possui uma cópia do livro-razão e participa do processo de validação das transações. Um nó pode ser classificado em dois tipos: completo ou leve. Um nó completo é aquele que possui todo o histórico de transações e blocos da rede. Um nó leve é aquele que possui apenas uma parte do livro-razão ou um resumo dos blocos.

- **Transação**: é uma operação que modifica o estado do livro-razão, como a transferência de recursos entre os participantes da rede. Uma transação é composta por vários campos, como remetente, destinatário, valor, assinatura, etc.

- **Bloco**: é uma estrutura que contém um conjunto de transações validadas por um algoritmo de consenso. Um bloco é composto por vários campos, como hash, número, timestamp, nonce, etc.

- **Cadeia**: é uma sequência de blocos ligados entre si por hashes, formando um registro imutável e cronológico das transações. A cadeia mais longa e válida é considerada a versão oficial do livro-razão.

- **Consenso**: é um mecanismo que permite aos nós da rede concordarem sobre a ordem e a validade dos blocos e das transações. O consenso garante a segurança, a consistência e a finalidade do livro-razão. Existem vários tipos de algoritmos de consenso, como prova de trabalho (PoW), prova de participação (PoS), prova de autoridade (PoA), etc.

- **Contrato inteligente**: é um programa executado na blockchain que define as regras de negócio e a lógica das transações. Um contrato inteligente pode ser invocado por uma transação ou por outro contrato inteligente. Um contrato inteligente pode ser escrito em diferentes linguagens, dependendo da plataforma blockchain.

### Blockchain para negócios

Blockchain é uma tecnologia que pode trazer benefícios para diversos setores e casos de uso de negócios, como finanças, logística, saúde, educação, governo, etc. Alguns dos benefícios do blockchain para negócios são:

- **Transparência**: blockchain permite que todos os participantes da rede tenham acesso às mesmas informações sobre as transações e os recursos, aumentando a confiança e a colaboração entre eles.

- **Eficiência**: blockchain elimina a necessidade de intermediários e processos burocráticos para validar e executar as transações, reduzindo os custos e o tempo envolvidos.

- **Segurança**: blockchain usa criptografia e consenso para garantir a integridade, a autenticidade e a imutabilidade dos dados, evitando fraudes, erros e ataques à rede.

- **Inovação**: blockchain possibilita a criação de novos modelos de negócio e aplicações baseadas em contratos inteligentes, tokens e criptomoedas, gerando novas oportunidades e vantagens competitivas.

### Casos de uso Blockchain

Blockchain pode ser aplicado em diversos cenários e problemas reais, demonstrando seu potencial e sua versatilidade. A seguir, serão apresentados alguns exemplos de casos de uso blockchain:

- **Pagamentos internacionais**: blockchain pode facilitar o envio e o recebimento de dinheiro entre países, sem a necessidade de intermediários financeiros ou taxas elevadas. Blockchain pode usar criptomoedas ou tokens para representar diferentes moedas ou ativos, permitindo a conversão instantânea e transparente entre eles. Alguns exemplos de projetos que usam blockchain para pagamentos internacionais são: Ripple (XRP), Stellar (XLM) e Libra (LBR).

- **Rastreabilidade de produtos**: blockchain pode melhorar o controle e a visibilidade da cadeia de suprimentos de produtos, desde a origem até o destino final. Blockchain pode registrar todas as etapas do processo produtivo, como fabricação, transporte, armazenamento, distribuição, etc., garantindo a qualidade, a segurança e a autenticidade dos produtos. Alguns exemplos de projetos que usam blockchain para rastreabilidade de produtos são: IBM Food Trust, VeChain (VET) e OriginTrail (TRAC).

- **Identidade digital**: blockchain pode criar uma forma segura e descentralizada de gerenciar as identidades digitais dos usuários na internet. Blockchain pode armazenar os dados pessoais dos usuários em um formato criptografado e auto-soberano, permitindo que eles controlem o acesso e o compartilhamento desses dados com terceiros. Alguns exemplos de projetos que usam blockchain para identidade digital são: uPort, Civic (CVC) e SelfKey (KEY).