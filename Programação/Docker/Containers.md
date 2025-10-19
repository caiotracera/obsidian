Um container é uma unidade padronizada de software que empacota o código e todas as suas dependências para que um software seja executado de forma rápida e consistente em qualquer ambiente. As suas principais características são:

- **Imutabilidade** - uma vez que um container está em execução, a ideia principal é que ele consiga rodar de forma rápida, eficiente e toda vez que subirmos um novo container, esse seja idêntico aos demais contêineres que já foram executados.

- **Isolamento de recursos computacionais** - todo container, quando executado, trabalha de forma isolada. Ou seja, ele **não afeta** a *máquina host*. Com isso, ele é capaz de isolar os processos, a rede, e todos os recursos computacionais, como memória, CPU e tudo mais.

- **Leveza** - Um container é executado como um **processo** no sistema operacional, e isso permite com que ele seja executado e interrompido com muita rapidez.

- **Utilização dos recursos do Kernel do SO** - apesar de se comportar como um sistema operacional completo, dentro do container são montados diversos volumes, com diferentes sistemas de arquivos, para permitir que o seu container se comunique com os recursos do Kernel do sistema operacional da máquina host. Além disso, a visibilidade dos processos é limitada somente aos processos gerados pelo próprio container.

- **Utilização de imagens** - Similar a um *snapshot*, o container depende de uma **imagem**, que contem todas as informações necessárias para a correta execução do container.