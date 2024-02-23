##👤🔐 Script de Criação de Usuários do Sistema

Este é um script simples em bash que cria usuários do sistema no Linux utilizando o comando useradd e define senhas para esses usuários usando o comando passwd. Ele foi criado com o objetivo de facilitar a automação da criação de múltiplos usuários em ambientes de teste, desenvolvimento ou administração de sistemas Linux. ✨🐧


##Script de Criação de Diretórios e Usuários 🖥️🔑

Este é um script em bash que automatiza a criação de diretórios, grupos de usuários e usuários no Linux, além de especificar as permissões dos diretórios criados.

Funcionalidades 🚀
Criação de Diretórios: O script cria os diretórios /publico, /adm, /ven e /sec usando o comando mkdir.

Criação de Grupos de Usuários: São criados os grupos GRP_ADM, GRP_VEN e GRP_SEC utilizando o comando groupadd.

Criação de Usuários: São criados vários usuários e adicionados aos grupos correspondentes utilizando o comando useradd. As senhas dos usuários são definidas como Senha123 de forma criptografada.

Especificação de Permissões dos Diretórios: As permissões dos diretórios /adm, /ven e /sec são especificadas para que apenas o usuário root e os grupos correspondentes tenham permissão de leitura, escrita e execução. O diretório /publico recebe permissões mais abertas para permitir acesso público.
