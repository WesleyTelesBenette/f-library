# Microsserviços

## ✨ Visão Geral
A arquitetura mais popular atualmente, se baseia em dividir as funcionalidades do sistema entre vários componentes completamente independentes, cada um tendo uma única responsabilidade e seu próprio banco de dados.

### Vantagens
- O Software se torna altamente escalável, já que sempre podem ser adicionados novos componentes.
- A manutenção é muito mais fácil, tendo em vista que as funcionalidades estão explicitamente divididas.
- O desenvolvimento pode ser realizado por várias equipes, já que cada componente é basicamente um sistema único e diferente dos outros.
- A segurança com os dados aumenta, pois, cada banco de dados só pode ser acessado por uma única API e não manipulados diretamente.

### Desvantagens
- O nível de dependências é extremo, qualquer componente do sistema com defeito, pode deixar várias partes do software sem funcionamento, mesmo que não quebre o programa.
- Vários componentes dependem da utilização de outros componentes, então modificações bruscas em certos componentes pode ser uma ação bem sensível.
- Como cada componente é essencialmente uma API independente, cada uma deve ser chamada via HTTP, o que pode diminuir um pouco o desempenho.
- Para melhor eficiência de cada sistema individualmente, o ideal seria que cada componentes fosse implementado numa máquina diferente, o que nem sempre é possível para o orçamento da empresa.

### Arquitetura


## 🪄 Exemplo Prático
