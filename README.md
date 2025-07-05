# 🐉 Repelidor de Dragões - RPG

Um jogo de RPG simples e divertido desenvolvido em HTML, CSS e JavaScript onde você deve derrotar um dragão que está impedindo as pessoas de saírem da cidade!

## 🎮 Sobre o Jogo

**Repelidor de Dragões** é um jogo de aventura baseado em texto onde você assume o papel de um herói que deve salvar a cidade de um dragão temível. Explore diferentes locais, lute contra monstros, compre equipamentos e ganhe experiência para se tornar forte o suficiente para enfrentar o dragão final.

## 🎯 Objetivo

Derrotar o dragão que está bloqueando a saída da cidade! Para isso, você precisará:
- Ganhar experiência lutando contra monstros
- Coletar ouro para comprar equipamentos
- Melhorar suas armas e vida
- Se tornar forte o suficiente para enfrentar o dragão

## 🗺️ Locais do Jogo

### 🏘️ **Praça da Cidade**
- Centro da cidade onde você pode acessar outros locais
- Ponto de partida e retorno após aventuras

### 🏪 **Loja**
- Compre vida (10 ouro por 10 pontos de vida)
- Compre armas mais poderosas (30 ouro cada)
- Venda armas antigas (15 ouro cada)

### 🕳️ **Caverna**
- Enfrente monstros para ganhar experiência e ouro
- Monstros disponíveis:
  - **Slime** (Nível 2, 15 de vida)
  - **Fera com Presas** (Nível 8, 60 de vida)

### 🐉 **Dragão**
- Chefe final do jogo
- Nível 20 com 300 de vida
- Só deve ser enfrentado quando você estiver bem equipado!

## ⚔️ Sistema de Combate

### **Ações Disponíveis:**
- **Atacar:** Causa dano ao monstro (baseado na arma + XP)
- **Esquivar:** Evita o ataque do monstro
- **Fugir:** Volta para a praça da cidade

### **Mecânicas:**
- Seu dano = Poder da arma + XP + número aleatório
- Dano do monstro = (Nível × 5) - XP
- Armas podem quebrar durante o combate (10% de chance)
- Quanto mais XP você tem, mais forte fica

## 🛡️ Sistema de Equipamentos

### **Armas Disponíveis:**
1. **Pau** (Poder: 5) - Arma inicial
2. **Adaga** (Poder: 30) - 30 ouro
3. **Martelo de Garra** (Poder: 50) - 30 ouro
4. **Espada** (Poder: 100) - 30 ouro

### **Sistema de Inventário:**
- Você pode carregar múltiplas armas
- Armas podem quebrar durante o combate
- Venda armas antigas para ganhar ouro

## 🎲 Jogo Secreto (Easter Egg)

Encontre o jogo secreto! Escolha entre os números 2 ou 8:
- **Acertar:** Ganha 20 ouro
- **Errar:** Perde 10 pontos de vida

## 🚀 Como Jogar

### **Instalação:**
1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/repelidor-de-dragoes.git
cd repelidor-de-dragoes
```

2. Abra o arquivo `index.html` no seu navegador

### **Controles:**
- Use os botões na tela para navegar
- Clique nos botões para realizar ações
- Monitore seus stats (XP, Vida, Ouro) no topo da tela

## 🎯 Estratégias de Jogo

### **Para Iniciantes:**
1. Comece lutando contra slimes na caverna
2. Colete ouro e XP
3. Compre vida quando necessário
4. Melhore suas armas gradualmente

### **Para Avançados:**
1. Farme feras com presas para XP rápido
2. Mantenha múltiplas armas no inventário
3. Use o jogo secreto para ganhar ouro extra
4. Só enfrente o dragão com espada e vida alta

## 🏆 Condições de Vitória/Derrota

### **🎉 Vitória:**
- Derrote o dragão final
- Você salva a cidade!

### **💀 Derrota:**
- Sua vida chega a 0
- Você morre e precisa recomeçar

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **CSS3** - Estilização e layout
- **JavaScript** - Lógica do jogo e interatividade

## 📁 Estrutura do Projeto

```
repelidor-de-dragoes/
├── index.html      # Página principal do jogo
├── styles.css      # Estilos e layout
├── script.js       # Lógica do jogo
└── README.md       # Este arquivo
```

## 🎨 Características do Jogo

- ✅ Interface simples e intuitiva
- ✅ Sistema de progressão claro
- ✅ Múltiplas estratégias de jogo
- ✅ Easter egg secreto
- ✅ Sistema de combate baseado em RPG
- ✅ Gerenciamento de recursos (ouro, vida, XP)

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar bugs
- Sugerir melhorias
- Adicionar novas funcionalidades
- Melhorar a documentação

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

---

**Divirta-se salvando a cidade do dragão! 🐉⚔️** 
