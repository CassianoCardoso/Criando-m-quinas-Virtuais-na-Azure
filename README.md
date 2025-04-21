# 🖥️ Guia: Criando uma Máquina Virtual na Microsoft Azure

## ✅ Pré-requisitos

Antes de iniciar, é necessário:

- Ter uma conta no [Azure](https://azure.microsoft.com/)
- Estar logado no [portal Azure](https://portal.azure.com/)
- Ter um recurso chamado **"grupo de recursos"** (você pode criar durante o processo)

---

## 🔹 Passo 1: Criar uma Conta no Azure

1. Acesse o site do [Azure](https://azure.microsoft.com/)
2. Clique em **"Iniciar gratuitamente"** e siga as instruções para criar sua conta.
3. Faça login no [Portal do Azure](https://portal.azure.com/)

---

## 🔹 Passo 2: Criar uma Máquina Virtual

1. No painel lateral esquerdo do portal, clique em **Máquinas Virtuais**.
2. Clique no botão **+ Criar** e selecione **Máquina Virtual**.

---

## 🔹 Passo 3: Configurar os Detalhes da Máquina

### 🧩 Seção: Básico

- **Assinatura:** Selecione sua assinatura do Azure.
- **Grupo de recursos:** Crie ou selecione um grupo de recursos.
- **Nome da VM:** Dê um nome para sua máquina virtual.
- **Região:** Escolha a região onde a máquina será criada.
- **Imagem:** Selecione o sistema operacional (ex: Ubuntu, Windows Server).
- **Tamanho:** Escolha o tamanho da máquina virtual (CPU, RAM).

### 🔐 Seção: Credenciais

Escolha o método de autenticação:

- **Senha:** Crie um nome de usuário e uma senha.
- **Chave SSH:** Gere ou forneça uma chave SSH para acessar a VM.

---

## 🔹 Passo 4: Configurações Adicionais

### 💾 Seção: Disco

- Escolha o tipo e tamanho de disco.

### 🌐 Seção: Rede

- Use as configurações de rede padrão ou ajuste conforme necessário.

### ⚙️ Seção: Gerenciamento

- Ative ou desative opções como monitoramento e reinicializações automáticas.

---

## 🔹 Passo 5: Revisar e Criar

1. Revise todas as configurações.
2. Clique em **Criar** para iniciar a criação da máquina virtual.

---

📌 Após a criação, você poderá acessar sua VM pelo IP público usando SSH (Linux) ou RDP (Windows), dependendo do sistema operacional escolhido.
