# Gerador de QRCode e password para e-commerce com node.js

## Sobre o projeto

**projeto-qrcode** é uma ferramenta em Node.js para gerar QR Codes e senhas seguras.  
O gerador de senhas é totalmente configurável via variáveis de ambiente, permitindo ativar ou desativar conjuntos de caracteres (maiúsculas, minúsculas, números e símbolos) e definir o comprimento da senha. O projeto é modular, com serviços separados para QR Code e password, facilitando manutenção e extensão.

## Funcionalidades
-  Gerar QR Code a partir de texto ou URL
-  Gerar senhas aleatórias
-  Configurar caracteres permitidos via `.env`
-  Definir tamanho da senha
-  Estrutura modular e escalável

## Tecnologias
- Node.js
- JavaScript (ESModules)
- Chalk
- Prompt
- Dotenv
- QRCode Terminal

---
##  Pré-requisitos

Antes de começar, você precisa ter instalado:

- Node.js (versão 18 ou superior)
- npm

---

##  Instalação

Clone o repositório:

```bash
git clone https://github.com/luankgf/gerador-qrcode-password.git
```

Entre na pasta do projeto:

```bash
cd projeto-qrcode
```

Instale as dependências:

```bash
npm install
```

---

## Configuração do `.env`

Crie um arquivo `.env` na raiz do projeto:

```env
UPPERCASE_LETTERS=false
LOWERCASE_LETTERS=true
NUMBERS=true
SPECIAL_CHARACTERS=true
PASSWORD_LENGTH=8
```

### Variáveis disponíveis

| Variável | Descrição |
|---|---|
| `UPPERCASE_LETTERS` | Ativa letras maiúsculas |
| `LOWERCASE_LETTERS` | Ativa letras minúsculas |
| `NUMBERS` | Ativa números |
| `SPECIAL_CHARACTERS` | Ativa símbolos especiais |
| `PASSWORD_LENGTH` | Define tamanho da senha |

---

## Como usar

Execute o projeto:

```bash
npm run start
```

Depois escolha:

```bash
1 - QRCODE
2 - PASSWORD
```

---

## Exemplo de senha gerada

```bash
h#cy4hok
```

---





