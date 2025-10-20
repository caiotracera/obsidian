O Docker é um [[Container Runtimes|container runtime]] que foi criado em 2013 para uso interno de uma empresa chamada dotCloud, que funcionava como uma Platform as a Service. Com a popularização do Docker, a Docker Engine passou a ser Open Source e a dotCloud foi renomeada para Docker Inc.

- **Ferramenta 360** - gerenciamento de containers, rede e disco, além da criação e build de imagens;

- **Formato client-server**:
	- Daemon (**dockerd**) que faz o gerencimento de todos os containers;
	- Client que faz chamadas para o daemon;
	- Daemon acaba se tornando um ponto único de falha (SPoF);