Uma **Máquina Virtual (VM)** é um ambiente computacional completo que simula um sistema operacional inteiro sobre um hardware virtualizado. Ela empacota não só a aplicação e suas dependências, mas também o próprio sistema operacional, garantindo isolamento total e flexibilidade entre diferentes plataformas. As suas principais características são:

- **Sistema operacional completo** - cada máquina virtual possui seu próprio kernel e sistema operacional, independentemente do sistema da máquina host. Isso permite executar diferentes sistemas operacionais simultaneamente no mesmo hardware físico.

- **Isolamento forte e segurança elevada** - como cada VM tem seu próprio ambiente isolado, uma falha ou ataque em uma VM não compromete as demais, nem o host. Esse isolamento é feito via hypervisor, garantindo a separação total de memória, processos, rede e disco;

- **Independência de hardware** - uma VM simula recursos como CPU, memória, disco e interfaces de rede. Isso permite mover, restaurar ou replicar máquinas virtuais com facilidade, sem depender do hardware físico original;

- **Flexibilidade para aplicações legadas ou específicas** - VMs permitem manter aplicações que precisam de versões específicas de sistema operacional, bibliotecas ou configurações, sem interferir em outros ambientes.

- **Snapshots e imagens completas** - assim como [[Containers]] usam imagens, VMs utilizam arquivos de disco e snapshots que armazenam o estado completo da máquina (SO, configurações, aplicativos e dados), facilitando backup, migração e restauração.

- **Maior consumo de recursos** - por executarem um sistema operacional completo, VMs utilizam mais CPU, memória e armazenamento, além de terem um tempo de inicialização maior em comparação a containers;