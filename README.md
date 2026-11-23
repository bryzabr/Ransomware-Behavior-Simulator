# Projeto de Criptografia e Descriptografia de Arquivos

## Sobre o projeto

Este projeto tem como objetivo demonstrar, em um laboratório controlado, o funcionamento da criptografia e descriptografia de arquivos utilizando Python e a biblioteca Cryptography.

A atividade envolve geração e armazenamento de chaves criptográficas, leitura e escrita de arquivos e recuperação dos dados por meio da descriptografia.

## Ferramentas utilizadas

- Python
- Cryptography
- Fernet
- Módulo OS

## Atividades realizadas

### 1. Geração de chave criptográfica

- Utilização do Fernet para gerar uma chave criptográfica.
- Armazenamento da chave em um arquivo `.key`.
- Carregamento da chave para utilização nas operações.

### 2. Criptografia de arquivos

- Localização dos arquivos presentes no diretório de testes.
- Leitura dos arquivos em modo binário.
- Criptografia dos dados utilizando Fernet.
- Gravação dos dados criptografados.

### 3. Descriptografia de arquivos

- Carregamento da chave criptográfica.
- Localização dos arquivos de teste.
- Descriptografia dos dados utilizando Fernet.
- Recuperação do conteúdo original dos arquivos.

## Estrutura do projeto

    criptografia-de-arquivos/
    │
    ├── README.md
    ├── ransoware.py
    ├── descriptografar.py
    │
    └── test_files/
        ├── senhas.txt
        └── dados_confidenciais

## Considerações de segurança

O projeto utiliza criptografia simétrica por meio do Fernet, que oferece confidencialidade e autenticação dos dados.

A chave criptográfica é necessária para realizar a recuperação dos arquivos. Por isso, seu armazenamento deve ser feito com segurança.

## Aviso

Este projeto possui finalidade exclusivamente educacional. Os testes devem ser realizados somente em ambientes controlados, utilizando arquivos próprios e de teste.
