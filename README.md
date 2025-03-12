# Web RCON

**Web RCON** é uma interface web para controlar um servidor de jogos (como Minecraft) utilizando **RCON** (Remote Console). Com esta aplicação, você pode enviar comandos diretamente do navegador para o servidor, gerenciar jogadores, modificar o ambiente do jogo e muito mais.

Este projeto usa **Node.js**, **WebSocket** e a biblioteca **GameDig** para monitorar o servidor em tempo real e fornecer uma interface intuitiva para comandos administrativos.

---

## 🚀 **Funcionalidades**

- **Envio de comandos RCON via WebSocket**: 
  Envie comandos administrativos para o servidor de jogos em tempo real.
  
- **Interface amigável**:
  - Selecione comandos pré-definidos do **Minecraft** ou **Outros jogos**.
  - Escolha jogadores conectados e personalize comandos com facilidade.
  
- **Monitoramento de jogadores**:
  - Obtenha a lista de jogadores online no servidor.
  
- **Console de saída**:
  - Visualize a resposta do servidor diretamente no navegador.

---

## 🛠️ **Tecnologias utilizadas**

- **Node.js**: Backend para gerenciar a comunicação WebSocket e RCON.
- **WebSocket**: Comunicação em tempo real entre o servidor e o cliente.
- **RCON**: Protocolo para enviar comandos administrativos para servidores de jogos.
- **GameDig**: Biblioteca para obter dados sobre jogadores e status do servidor de jogo.
- **HTML5, CSS3 e JavaScript**: Frontend para criar a interface do usuário.

---

## 📦 **Como rodar o projeto localmente**

Siga as instruções abaixo para rodar o projeto no seu ambiente local:

### 1. **Clone o repositório**
```bash
git clone https://github.com/seu-usuario/web-rcon.git
cd web-rcon
```
