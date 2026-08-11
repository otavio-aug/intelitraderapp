# Anotações de desenvolvimento
As mensagens são salvas na tabela "message", banco msgstore.db. Tem de tomar MUITO cuidado quando for abrir o banco, pois as mensagens ficam primeiro em um arquivo de snapshot (wal), e depois vão para o banco. Sendo assim, é necessário primeiro parar a aplicação para depois ter acesso a estas informações no banco.

(Primeira vez utilizando android studio)
Os emuladores podem ser acessados via terminal, os arquivos de todo o sistema podem ser copiados, inclusive. 
Escrever e compilar C++ ainda é um mistério por aqui. 
