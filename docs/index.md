<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Sistema Falcão Sombrio para Drones&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Aluno 1 Beatriz Aparcida de Mello Barbosa
* Aluno 2 Gabriel Pereira Faravola
* Aluno 3 Guilherme Haddad Borro
* Aluno 4 Henrique Jeam Ferreira Lima

# Descrição do Projeto

*A Securus Dynamics está desenvolvendo o Falcão Sombrio, um novo sistema que permitirá o controle remoto e autônomo de seus drones por meio de uma rede de servidores distribuídos e uma interface avançada. O projeto enfrenta desafios como segurança, concorrência e tempo real nos sistemas operacionais, além de questões de armazenamento distribuído, replicação e auditoria nos bancos de dados. Diante de falhas na arquitetura atual, a empresa contratou a Consultoria Cyber Bullet System (Turma 4G) para reformular toda a estrutura de software e definir um novo modelo de banco de dados que suporte as operações críticas dos drones.*

# Análise de Requisitos Funcionais e Não-Funcionais

 <ins> **Requisitos Funcionais:** </ins>
| ID | RF | Descrição |
|-|-|-|
|RF1| Autenticação de Operadores| O sistema deve permitir a autenticação dos operadores utilizando biometria e autenticação multifator (MFA).|
|RF2| Controle de frotas| O sistema deve possibilitar o gerenciamento remoto e autônomo de múltiplos drones simultaneamente.|  
|RF3| Interface de comando e controle| Deve existir uma interface gráfica para os operadores visualizarem telemetria, status e executar comandos sobre os drones.|
|RF4| Navegação autônoma| Os drones devem ser capazes de realizar missões táticas sem intervenção humana, utilizando sensores como LIDAR, GPS e visão computacional.|
|RF5| Comunicação Segura| A troca de informações entre os drones e o sistema de controle deve ser realizada utilizando criptografia ponta a ponta.|
|RF6| Registro de Missões| O sistema deve registrar dados de cada missão, incluindo logs detalhados das operações realizadas.|
|RF7| Monitoramento em Tempo Real| Os drones devem transmitir dados de telemetria, status e eventos críticos continuamente para o sistema central.|
|RF8| Gerenciamento de Atualizações| O sistema deve permitir a atualização remota de firmware dos drones, garantindo segurança e conformidade operacional.|
|RF9| Failover e Recuperação| Em caso de falha de servidor, o sistema deve permitir o redirecionamento automático das operações para um servidor de backup.|
|RF10| Auditoria de Eventos| Todos os acessos e comandos devem ser armazenados em logs de auditoria imutáveis para fins de segurança e conformidade.|


 <ins> **Requisitos Não Funcionais:** </ins>
|ID | RNF | Descrição |
|-|-|-|
|RNF1| Segurança| O sistema deve implementar criptografia AES-256 para armazenamento de dados e TLS para comunicação.|
|RNF2| Desempenho| A latência da comunicação entre um drone e o sistema não pode ultrapassar 50ms em condições normais.|
|RNF3| Disponibilidade| O sistema deve estar disponível 24/7, com 99,9% de uptime, garantindo operação contínua em missões críticas.|
|RNF4| Escalabilidade| A arquitetura deve permitir a adição de novos drones eservidores sem comprometer a performance e segurança.|
|RNF5| Armazenamento Distribuído| O banco de dados deve ser replicado geograficamente para garantir redundância e integridade dos dados.|
|RNF6 |Conformidade (Boas Práticas)| O sistema deve atender a padrões de segurança como ISO 27001 e NIST 800-53 para segurança cibernética.|
|RNF7| Resiliência| O sistema deve garantir recuperação automática de falhas em até 05 segundos sem perda de dados.|
|RNF8| Tolerância a Falhas| A arquitetura deve suportar balanceamento de carga e replicação para evitar pontos únicos de falha.|
|RNF9| Eficiência Energética| Os drones devem otimizar o consumo de bateria utilizando algoritmos de inteligência artificial para gestão de energia.|
|RNF10| Log e Auditoria| Os logs devem ser armazenados por no mínimo 05 anos e protegidos contra alteração ou exclusão.|

# Diagrama de Atividades

![diagrama](https://github.com/user-attachments/assets/3441ac48-9478-4d90-aee6-326a47ad287d)

# Diagrama de Casos de Uso

*&lt;Diagrama para visualizar o comportamento dos atores&gt;*

# Descrição dos Casos de Uso

*&lt;Descrição do comportamento entre os atores/resquisitos&gt;*

# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
