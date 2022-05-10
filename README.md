# docker-kafka

- [Português](###Português)
- [English](###English)

---

### Português

Configurações docker para subir com apenas um comando todas as tecnologias necessárias para um ambiente local com Kafka.

Os serviços que este docker-compose monta, são:

- `Kafka:` Serviço de Streaming, responsável pelos disparos e consumo dos eventos.
- `Zookeper:` Armazena informações como variáveis de ambiente.
- `Schema Registry:` Contrato entre as comunicasões, ele que garante que os dados salvos vão ser sempre a mesma estrutura dos dados que se consome.
- `AKHQ:` Interface gráfica para visualizar tudo que está acontecendo no seu Kafka local.

## Configuração

Monte o seu ambiente Kafka com apenas um único comando:

```bash
docker-compose up -d
```

---

<!-- ## Kafka -->

<!-- ## Zookeeper

O Apache ZooKeeper é um projeto Apache de código aberto que permite que os clusters distribuam informações como configuração, nomeação e serviços de grupo em grandes clusters. O projeto era originalmente um subprojeto do Apache Hadoop, mas tornou-se um projeto importante por si só, gerenciado pela Apache Software Foundation.

O Apache ZooKeeper é um serviço para fornecer informações de configuração, nomeação, sincronização e serviços de grupo em sistemas distribuídos, incluindo o Hadoop. A lógica do projeto é facilitar o gerenciamento de sistemas distribuídos, já que muitos aplicativos economizam nos serviços que tornam as mudanças de propagação confiáveis. O ZooKeeper usa um armazenamento de valores-chave de maneira hierárquica. É usado para ambientes de alta disponibilidade.

## Schema Registry

## AKHQ -->

### English

Docker configurations to go up with just one command all the technologies that Kafka covers.
The services that this docker-compose raises are:

- Kafka: Streaming Service, responsible for triggering and consuming events.
- Zookeper: Stores information as environment variables.
- Schema Registry = Contract between communications, which guarantees that the saved data will always have the same structure as the data consumed.
- AKHQ = Graphical interface to visualize everything that is happening in your local Kafka.

## Setup

Build your Kafka environment with just a single command:

```bash
docker-compose up -d
```

> Run with docker-compose
