📌 Contexto

Este projeto demonstra o uso de TRIGGER em SQL Server para auditoria de alterações, registrando automaticamente toda modificação realizada no campo EMAIL da tabela ALUNO.

Sempre que o e-mail de um aluno é atualizado, a trigger salva o histórico da alteração em uma tabela de log, garantindo rastreabilidade e controle das mudanças.

🎯 Objetivo da Trigger

Monitorar atualizações no campo EMAIL da tabela ALUNO

Registrar o e-mail antigo e o novo

Armazenar dados do aluno afetado

Identificar quem realizou a alteração

Registrar data e hora da operação

Garantir auditoria e integridade das informações

🗄️ Tabelas Envolvidas
🔹 Tabela principal

ALUNO

🔹 Tabela de auditoria

ATZD_EMAIL

A tabela ATZD_EMAIL é responsável por armazenar o histórico das alterações realizadas no campo EMAIL.

⚙️ Funcionamento da Trigger

A trigger TRG_ATUALIZA_EMAIL é executada automaticamente após um UPDATE na tabela ALUNO.
