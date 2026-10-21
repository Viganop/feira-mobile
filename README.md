# 📱 Feira de Profissões — Desenvolvedor Mobile

Material de estudo para apresentar o projeto **"Monte seu app"** na feira.
Versão completa (com mais detalhes) no PDF: [Guia_Apresentacao_Feira_Mobile.pdf](Guia_Apresentacao_Feira_Mobile.pdf).

---

## 📂 Arquivos do projeto

| Arquivo | Para que serve |
|---|---|
| `Monte seu app vertical v3.html` | Versão mais recente para **tela em pé** (totem / monitor vertical) |
| `Monte seu app horizontal v3.html` | Versão mais recente para **tela deitada** (monitor comum / TV) |
| `Monte seu app v2.html` / `Monte seu app vertical.html` | Versões anteriores (backup) |
| `Guia_Apresentacao_Feira_Mobile.pdf` | Guia completo de apresentação |

👉 Para abrir: dois cliques no `.html` (abre no navegador). Não precisa de internet nem instalar nada.
Dica: aperte **F11** para tela cheia.

---

## ⚡ Resumo em 30 segundos (decore isto!)

- **O que é:** quem cria os apps do celular (WhatsApp, banco, iFood) e publica na **Play Store** e **App Store**.
- **Ferramentas:** Android = **Kotlin** · iPhone = **Swift** · os dois de uma vez = **React Native** (Meta) ou **Flutter** (Google).
- **Como chegar lá:** curso de **ADS** (Análise e Desenvolvimento de Sistemas, 2,5 a 3 anos).
- **Salário (Robert Half 2026):** Júnior ~**R$ 6.850** · Pleno ~**R$ 11.750** · Sênior ~**R$ 16.950**.
- **Mito:** não precisa ser craque em matemática — precisa de **lógica, curiosidade e paciência**.

---

## 🖥️ As duas abas da demonstração

1. **📖 Apresentação** — um celular gigante; cada "app" da tela inicial explica uma parte da carreira.
2. **🚀 Monte seu app** — o visitante monta um app arrastando (ou tocando) blocos, e o **código React Native real** aparece ao lado em tempo real.

### Na aba "Monte seu app" tem

- **5 apps prontos** para começar: 🍔 Lanchonete · 💬 Rede social · 🎵 Música · 👟 Loja · ✅ Tarefas
- **14 blocos:** Título, Texto, Imagem, Campo de texto, Botão, Lista, Cabeçalho, Tela de login, Produto à venda, Botão de curtir, WhatsApp, Mapa, Galeria de fotos, Lista de tarefas
- Botão **🌙 Modo Escuro**, botão **Limpar** e controles de largura/altura do celular e do código
- Rodapé com os códigos **CBO 2124-05** e **CBO 3171-10** (a profissão no Cadastro Brasileiro de Ocupações)

---

## 🎁 Truques para impressionar ("easter eggs")

| Truque | Como fazer |
|---|---|
| **Emoji muda sozinho** | No bloco *Produto à venda*, escreva Pizza, Café, Sorvete, Bolo, Camisa, Celular, Fone, Livro, Mochila... o ícone troca! |
| **Vírgula separa as coisas** | Produto: `Pizza Calabresa, R$ 45` (nome, preço). Lista/Tarefas: `Acordar, Estudar ADS, Programar` (cada vírgula = um item) |
| **Curtir funciona** | Clique no ❤️ dentro do celular: o coração enche/esvazia |
| **Tarefas funcionam** | Clique num item da lista de tarefas: ele é riscado como concluído |
| **Arrastar para fora apaga** | Arraste um bloco para fora do celular e ele some |
| **Reset automático** | 2 minutos sem ninguém tocar → limpa tudo e volta para a Apresentação |

---

## 🧠 Os 7 ícones da aba "Apresentação"

> Não leia a tela! Use ela de apoio e **fale com suas palavras**.

### 💡 1. O que é
- Cria apps para dispositivos **móveis** (celular, tablet, relógio).
- O app usa recursos do aparelho que um site comum não usa bem: **câmera, GPS, biometria, notificações, Bluetooth, NFC** (pagamento por aproximação).
- No final, publica nas lojas: **Google Play** (Android) e **App Store** (iPhone).

### 🧑‍💻 2. Dia a dia
Trabalha em equipe:
1. **UI/UX Designer** → desenha as telas (ex.: no Figma).
2. **Back-end** → cuida do servidor e do banco de dados.
3. **Dev Mobile** → transforma o desenho em tela de verdade e conecta com o back-end (via **API**).

Um app nunca fica "pronto": sempre tem correção de bug, celular novo e função nova.

### 🏢 3. Onde atua
- Bancos (Nubank, Inter), delivery (iFood), transporte (Uber), saúde, agronegócio, indústria, startups.
- Muito **trabalho remoto** — dá até para trabalhar para fora do Brasil ganhando em dólar/euro.
- Ou ser **freelancer** / ter os próprios apps.

### 🛠️ 4. Ferramentas
- **Nativo:** um projeto para Android (**Kotlin**) e outro para iPhone (**Swift**).
- **Multiplataforma:** **um código só** gera os dois apps.
- A demo usa **React Native** (da Meta, em JavaScript/TypeScript). Outra famosa: **Flutter** (Google).

### 🎓 5. Como chegar lá — curso de ADS
- **Lógica de programação** → ensinar o computador a pensar passo a passo.
- **Web (HTML, CSS, JavaScript)** → já é ~70% do caminho para o React Native.
- **Banco de dados e APIs** → salvar dados e falar com servidores.
- **Engenharia de software** → planejar antes de programar.

### 💰 6. Remuneração (Guia Salarial Robert Half 2026)

| Nível | Experiência | Mediana | Faixa |
|---|---|---|---|
| Júnior | até ~2 anos | **R$ 6.850** | R$ 6.050 – 8.750 |
| Pleno | ~2 a 5 anos | **R$ 11.750** | R$ 8.950 – 15.050 |
| Sênior | +5 anos | **R$ 16.950** | R$ 12.950 – 21.800 |

Normalmente começa como **estagiário/trainee** durante a faculdade.

### ⭐ 7. O que ajuda
- Curiosidade, vontade de aprender, paciência para achar erros.
- **Não precisa ser gênio da matemática**: programar é mais parecido com **montar LEGO** ou escrever uma **receita** detalhada.

---

## 💻 Explicando o código React Native (aponte para a coluna da direita!)

| Parte do código | Explicação simples |
|---|---|
| `import { View, Text, ... }` | **Caixa de ferramentas** — a cada bloco novo, aparece uma peça nova no import |
| `<View>` | Caixa invisível que organiza os elementos |
| `<Text>` | Qualquer texto |
| `<Image>` | Foto/ilustração |
| `<TextInput>` | Campo para digitar (e-mail, senha) |
| `<TouchableOpacity>` | Botão que "pisca" quando toca |
| `<FlatList>` | Lista com rolagem (blocos Lista e Tarefas) |
| `useState(false)` | **Memória do app (estado)**. Curtir começa `false`; tocou → vira `true` e o coração fica vermelho |
| `Linking.openURL('https://wa.me/...')` | Bloco WhatsApp: o app **abre outro app** |
| `<MapView latitude: -22.0087 ...>` | Bloco Mapa: coordenadas de **São Carlos/SP** |
| `StyleSheet.create({...})` | **Aparência**: tamanho da letra, cantos arredondados, espaçamento, cor |

> Frase-chave: *"Lá em cima o código diz **o que** existe na tela. Aqui embaixo, no StyleSheet, diz **como** ele se parece."*

---

## 🎤 Roteiro do pitch (2 a 3 minutos)

**1. Gancho (15 s)** — comece com pergunta, não com teoria:
> "Quantos apps vocês já abriram hoje desde que acordaram? WhatsApp, Instagram, banco, iFood? Tudo isso é feito por um **Desenvolvedor Mobile**!"

**2. Passeio pela Apresentação (1 min)**
- 💡 O que é + 🧑‍💻 Dia a dia → transforma ideia em app, junto com design e back-end.
- 🛠️ Ferramentas → Kotlin, Swift, e React Native faz os dois.
- 🎓 + 💰 + ⭐ → curso de ADS, salários, não precisa ser gênio da matemática.

**3. Desafio prático no "Monte seu app" (1 min)**
- Convide: *"Agora é sua vez de ser dev mobile por 1 minuto! Quer começar pela Lanchonete, Rede social, Música, Loja, Tarefas ou do zero?"*
- **Momento "Uau":**
  1. Clique no **X-Burger** e troque para `Pizza, R$ 40` → o ícone muda sozinho.
  2. Troque a **cor** nas bolinhas → aponte o código mudando ao vivo.
  3. Adicione **❤️ Curtir** ou **✅ Tarefas**, clique dentro do celular → mostre o `useState` no código.

---

## ❓ Perguntas frequentes — respostas rápidas

**"Preciso de computador caro?"**
Não. Um computador comum serve para começar. Com o **Expo** dá para testar o app no próprio celular lendo um QR Code.

**"Sem Mac consigo fazer app de iPhone?"**
Sim! Com React Native programa no Windows/Linux. O Mac (ou serviço na nuvem) só é necessário para publicar na App Store.

**"Quanto tempo para aprender?"**
Em poucas semanas de lógica + JavaScript já faz telas simples como as da demo. O ADS (2,5 a 3 anos) dá a base profissional completa.

**"Qual a diferença entre site e app?"**
O site roda no navegador e depende de internet. O app é instalado, é mais rápido e acessa câmera, GPS, notificações e sensores.

**"A IA vai substituir programadores?"**
Não — a IA é a **assistente** do programador. Ela acelera o código repetitivo, mas o dev entende a necessidade das pessoas, planeja, cuida da segurança e junta as peças.

**"Esse site é um programa baixado?"**
Não! É **um único arquivo HTML** com CSS e JavaScript puro, que simula um celular (com Dynamic Island!) e gera código React Native de verdade enquanto você mexe.

---

## ✅ Checklist antes da feira

- [ ] Abrir a versão certa (vertical ou horizontal) e deixar em **tela cheia (F11)**
- [ ] Testar os 5 apps prontos e o botão **Limpar**
- [ ] Testar o truque do emoji (`Pizza, R$ 40`)
- [ ] Testar curtir ❤️ e tarefas ✅ dentro do celular
- [ ] Saber os **3 salários** e as **3 linguagens** (Kotlin, Swift, React Native) de cabeça
- [ ] Treinar o gancho em voz alta pelo menos 3 vezes
