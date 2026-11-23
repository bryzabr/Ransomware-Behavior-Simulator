# Ransomware-Behavior-Simulator
Laboratório em Python para criptografia e descriptografia de arquivos utilizando Fernet, com geração e gerenciamento de chaves.

Criptografia e Descriptografia de Arquivos com Python

Sobre o projeto

Projeto desenvolvido em Python para estudar o processo de criptografia e descriptografia de arquivos utilizando a biblioteca Cryptography e o módulo Fernet.

O laboratório utiliza dois scripts: um responsável por gerar uma chave e criptografar os arquivos de teste, e outro responsável por carregar essa chave e realizar a descriptografia.

Tecnologias utilizadas

- Python
- Cryptography (Fernet)
- OS

Funcionamento

1. Criptografia ("ransoware.py")

- Geração de uma chave utilizando Fernet.
- Armazenamento da chave em um arquivo ".key".
- Busca de arquivos dentro do diretório "test_files".
- Criptografia dos arquivos encontrados.

2. Descriptografia ("descriptografar.py")

- Carregamento da chave criptográfica.
- Busca dos arquivos no diretório "test_files".
- Descriptografia dos arquivos utilizando Fernet.
- Recuperação do conteúdo original.

Estrutura do projeto

Criptografia-de-Arquivos/
│
├── ransoware.py
│
├── descriptografar.py
│
├── test_files/
│   ├── dados_confidenciais
│   ├── senhas.txt
│
└── README.md

O arquivo "chave.key" é gerado durante a execução do script de criptografia e não deve ser enviado ao repositório público.

Objetivo

Praticar conceitos de Python, manipulação de arquivos, criptografia simétrica e gerenciamento de chaves, entendendo na prática como funciona o processo de criptografia e recuperação de dados.

Aviso

Projeto desenvolvido exclusivamente para fins educacionais, com execução em ambiente controlado e utilização de arquivos de teste.
