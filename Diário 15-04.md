<h3>
Problema
</h3>

um grupo de alunos precisam de material X, para lazer ou para um fim didático necessitam de empréstimos 
orientações via fichários, para controlar o desgastes dos bens do institutos engloba todos os matérias da sala ,não há limitação para pegar material 
Para livros didáticos existe um laudo para validar a integridade assinado via gov
maiores dificuldades:
não devolviam e acabam ficando sem materiais 

<h3>
Solução
</h3>
Desenvolver um sistema para o controle de estoque de materias de emprestimo / consumo dentro do campus para os alunos e servidores



| ID      | Descrição                                        | Prioridade | Origem      | Critérios de Aceitação                                                                          |
|---------|--------------------------------------------------|------------|-------------|--------------------------------------------------------------------------------------------------|
| REQ-001 | O sistema fará a gestão de materiais duráveis    | Alta       | Stakeholder | O administrador fará a gestão de materiais duráveis para alunos, servidores ou terceiros         |
| REQ-002 | O sistema fará a gestão de materiais de consumo  | Alta       | Stakeholder | O administrador fará a gestão de materiais duráveis para alunos, servidores ou terceiros         |
| REQ-003 | O sistema deverá alertar os usuários envolvidos no empréstimo quando um bem durável expirar o prazo de devolução  | Alta       | Stakeholder |O sistema encaminhará uma notificação(pelo próprio sistema), para os envolvidos no empréstimo(administador e usuário) quando um item expirar o prazo 

<h2> Realizar a gestão de materiais duráveis e consumivéis fornecido pelo campus </h2>
<h3> REQ-001  realizar a gestão de bens duráveis dentro do sistema </h3>

| ID      | Descrição                                        | Prioridade | Origem      | Critérios de Aceitação                                                                          |
|---------|--------------------------------------------------|------------|-------------|--------------------------------------------------------------------------------------------------|
| ARP001| Manutenir bens duráveis dentro do sistema    | Alta       | Stakeholder | Cadastrar, excluir, consultar e adicionar itens no sistema         |

<h3> REQ-002 realizar a gestão de bens de consumo dentro do sistema </h3>

| ID      | Descrição                                        | Prioridade | Origem      | Critérios de Aceitação                                                                          |
|---------|--------------------------------------------------|------------|-------------|--------------------------------------------------------------------------------------------------|
| ARP001 | Manutenir bens de consumo dentro do sistema    | Alta       | Stakeholder | Cadastrar, excluir, consultar e adicionar itens no sistema         |

<h3> realizar a gestão de bens de consumo dentro do sistema </h3>

<h2> Realizar o envio de alertas aos usuários</h2>
<h3> REQ-003 realizar disparos de alertas quando os bens duráveis chegarem ao prazo limite  </h3>

| ID      | Descrição                                        | Prioridade | Origem      | Critérios de Aceitação                                                                          |
|---------|--------------------------------------------------|------------|-------------|--------------------------------------------------------------------------------------------------|
| ARP003 | Disparar notificação aos usuários envolvidos em um empréstimo de bem durável    | Alta       | Stakeholder | O sistema deverá enviar uma mensagem via pop-up quando o usuário acessar o sistema, avisando que o item está  |



fichário contem:
item / Material, seja ele consumível ou durável
Identificação de quem empresta 
Identificação do aluno quanto aluno/professor/servidor/outra autorizado:
Caso seja professor, necessita da turma
caso Aluno, necessita de serie e turma, junto a horário de retirada para todos
