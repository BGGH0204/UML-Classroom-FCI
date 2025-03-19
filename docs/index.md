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

* Aluno 1 Beatris Barboza
* Aluno 2 Gabriel Pereira Faravola
* Aluno 3 Guilherme Haddad Borro
* Aluno 4 Henrique Jeam

# Descrição do Projeto

*A Securus Dynamics está desenvolvendo o Falcão Sombrio, um novo sistema que permitirá o controle remoto e autônomo de seus drones por meio de uma rede de servidores distribuídos e uma interface avançada. O projeto enfrenta desafios como segurança, concorrência e tempo real nos sistemas operacionais, além de questões de armazenamento distribuído, replicação e auditoria nos bancos de dados. Diante de falhas na arquitetura atual, a empresa contratou a Consultoria Cyber Bullet System (Turma 4G) para reformular toda a estrutura de software e definir um novo modelo de banco de dados que suporte as operações críticas dos drones.*

# Análise de Requisitos Funcionais e Não-Funcionais
Requisitos Funcionais:

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

Requisitos Não Funcionais:

1. <ins>Desempenho e Escalabilidade</ins>

    RNF1: O sistema deve garantir baixa latência na comunicação com os drones.

    RNF2: Deve suportar o controle simultâneo de múltiplos drones sem degradação de desempenho.

    RNF3: O sistema deve suportar failover automático para garantir disponibilidade contínua.

2. <ins>Segurança</ins>

    RNF4: O sistema deve garantir criptografia robusta para proteger os dados e as comunicações.

    RNF5: Os logs de auditoria devem ser imutáveis e armazenados com alta disponibilidade.

    RNF6: O sistema deve ser capaz de resistir a tentativas de invasão e controle não autorizado.

3. <ins>Integridade e Confiabilidade</ins>

    RNF7: Os dados dos drones devem ser sincronizados em tempo real para evitar inconsistências.

    RNF8: O histórico de missões deve ser armazenado de forma segura para auditorias e análises preditivas.

    RNF9: O banco de dados distribuído deve garantir a replicação automática dos dados.

4. <ins>Concorrência e Sistemas Operacionais</ins>

    RNF10: O sistema operacional embarcado deve suportar múltiplas threads para sensores, navegação e IA.

    RNF11: O sistema deve priorizar processos conforme o status crítico da missão.*

# Diagrama de Atividades

*&lt;Diagrama para visualizer as pessoas das áreas de negócios e de desenvolvimento de uma organização para entender o processo e comportamento.&gt;*

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
