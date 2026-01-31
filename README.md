# 99 Noites na Floresta – Script

### 🚀 Carregador rápido
Copie e cole um dos códigos abaixo no seu executor de Roblox:

### 🌟 Versão estável
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/shiftz99nights/99-Nights-in-the-Forest-Script/main/99%20Days%20Scirpt%20By%20Raygull.lua"))()
```

### 🧪 Versão beta
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/shiftz99nights/99-Nights-in-the-Forest-Script/main/99%20Days%20Scirpt%20By%20Raygull%20Beta%201.0.lua"))()
```

**Se não funcionar:**  
1. Confirme que o repositório existe no GitHub: **shiftz99nights/99-Nights-in-the-Forest-Script** (ou troque `shiftz99nights` pelo seu usuário).  
2. Os arquivos `.lua` precisam estar na **branch main** do repositório.  
3. Se o executor bloquear GitHub, use um paste (ex.: pastebin) ou carregue o script localmente.

### ✨ Recursos (50+ opções)

**Proteção (Indetectável / Antiban)**  
- **Indetectável / Antiban:** Delays aleatórios e menos ações para reduzir detecção  
- **Modo seguro:** Menos ações por minuto (antiban)  
- **Tecla de pânico (END):** Desativa todas as opções na hora  

**Início**  
- **Teletransporte:** Fogueira, moedor ou qualquer item  
- **ESP de itens e NPCs:** Ver itens e inimigos através das paredes  
- **Aimbot:** Clique direito para travar no alvo  
- **Voar:** WASD + Espaço/Shift (Q para ligar/desligar)  
- **Vida infinita:** Vida sempre no máximo  
- **Auto kill mobs:** Mata inimigos ao redor (ajuste o raio em studs)  

**Movimento**  
- **Sem dano de queda:** Não toma dano ao cair  
- **No clip:** Atravessar paredes  
- **Pulo infinito:** Pular várias vezes no ar  
- **Sprint sempre:** Correr o tempo todo  
- **Velocidade do voar:** Slider 20–200  
- **Força do pulo:** Slider  
- **Gravidade:** Slider 0–300  

**Visão**  
- **Fullbright:** Luz máxima no mapa  
- **Visão noturna:** Ver melhor no escuro  
- **FOV:** Campo de visão (slider 60–120)  
- **Sem efeitos de tela:** Desativa blur  
- **Câmera livre (freecam):** Mover câmera com WASD  

**Extras**  
- **Auto coletar:** Pega itens perto (tecla E)  
- **Anti-AFK:** Evita kick por inatividade  
- **Durabilidade infinita:** Ferramentas não quebram  
- **Oxigênio infinito:** Respiração infinita debaixo d’água  
- **Personagem invisível:** Transparência total  
- **Mostrar coordenadas:** X, Y, Z na tela  
- **Mostrar FPS:** Contador de FPS  
- **Notificação quando mob perto:** Aviso de inimigo a menos de 25 studs  
- **Ímã de itens (client):** Atração de itens (client-side)  
- **Andar na água (experimental):** Mantém o personagem em cima da água  
- **Sem recuo (armas):** Menos recuo ao atirar  

**Outros (Beta)**  
- **Anti-morte:** Teletransporte para fogueira quando inimigo perto  
- **Sem neblina:** Céu limpo  
- **Speedhack:** Velocidade de caminhada (slider)  
- **Farm automático:** Árvores e troncos  
- **Aba Anti-morte:** Raio e lista de NPCs a evitar  
- **Farm de troncos:** Saco velho (5) / saco bom (15)

### ⚠️ Aviso
Apenas para fins educacionais e de teste.

O uso de scripts no Roblox pode resultar em banimento. Use por sua conta e risco.

### 🙏 Créditos
Script e GUI por shiftz99nights

---

## 📤 Como colocar no GitHub

### 1. Criar conta e repositório
1. Acesse [github.com](https://github.com) e crie uma conta (se ainda não tiver).
2. Clique em **New** (Novo repositório).
3. Dê um nome, por exemplo: `99-Nights-in-the-Forest-Script`.
4. Escolha **Public** e clique em **Create repository**.

### 2. Enviar os arquivos pelo Git
Abra o **PowerShell** ou **Prompt de Comando** na pasta do projeto e rode:

```bash
git init
git add .
git commit -m "Primeira versão do script"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/99-Nights-in-the-Forest-Script.git
git push -u origin main
```

**Troque** `SEU_USUARIO` pelo seu nome de usuário do GitHub.

### 3. Links no README
Depois do push, os links do `loadstring` no README passam a funcionar assim:
- Troque `SEU_USUARIO` pelo **seu** nome de usuário do GitHub (ex: shiftz99nights).
- A URL deve usar o **branch** (ex.: `main`), não `refs/heads/main`:
  `https://raw.githubusercontent.com/SEU_USUARIO/99-Nights-in-the-Forest-Script/main/99%20Days%20Scirpt%20By%20Raygull.lua`

### 4. Se pedir login no `git push`
O GitHub não aceita mais senha comum. Use:
- **GitHub CLI:** instale e use `gh auth login`, ou  
- **Token de acesso:** em GitHub → Settings → Developer settings → Personal access tokens, crie um token e use no lugar da senha quando o Git pedir.

Pronto: o projeto estará no GitHub e os links do README (ajustados com seu usuário) poderão ser usados no executor.
