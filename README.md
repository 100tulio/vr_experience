# 🕶️ Experiência VR com Slides — Apresentação Interativa em Realidade Virtual

Este projeto proporciona uma experiência de realidade virtual (VR) com slides, acessível via navegadores compatíveis com **WebXR**. A aplicação foi desenvolvida com **A-Frame**, exibindo um telão de slides em um ambiente 3D com céu e chão realistas, e controle de slides interativo por botões. Compatível com Google Cardboard, VR Box e outros óculos que utilizam o celular.

---

## ✅ Requisitos

- Python 3 instalado
- Celular com giroscópio e navegador compatível com WebXR (ex: Chrome no Android)
- Óculos VR (Google Cardboard, VR Box, etc.)
- Conexão Wi-Fi compartilhada entre o computador e o celular

---

## 🗂️ Estrutura da pasta do projeto

Certifique-se de que todos os arquivos abaixo estão na **mesma pasta**, por exemplo:  
`C:\Users\Marco Tulio\Downloads\Teste_VR\vr_template_aframe1`

vr_template_aframe1/
├── index.html
├── grama.jpg
├── ceu-nuvens-360.jpg
├── 1_Resumo-Geral-das-Principais-IAs-2025.png
├── 2_IA-de-Texto-Multimodal.png
├── 3_IA-de-Imagem.png
├── 4_IA-de-Voz-Audio.png
├── 5_IA-de-Video.png
├── 6_IA-para-Codigo-e-Dados.png
└── 7_IA-para-Apresentacoes.png




---

## ⚙️ Como executar o projeto localmente

### 1. Acesse a pasta do projeto via terminal

```bash
cd "C:\Users\Marco Tulio\Downloads\Teste_VR\vr_template_aframe1"



2. Inicie um servidor local com Python

python -m http.server 8080

Você verá algo como:

yaml
Copiar
Editar
Serving HTTP on :: port 8080 ...

📲 Acessar via celular
1. Descubra o IP local do seu computador
Execute o comando no terminal:

bash
Copiar
Editar
ipconfig
Procure por algo como:

yaml
Copiar
Editar
Endereço IPv4. . . . . . . . . : 10.10.101.2
2. No navegador do celular (conectado na mesma rede Wi-Fi), acesse:
cpp
Copiar
Editar
http://10.10.101.2:8080
🕶️ Ativar modo VR no celular
Toque no botão azul flutuante: 🕶 Entrar em VR

A tela será dividida automaticamente (modo estereoscópico)

Coloque o celular no óculos VR (ex: Google Cardboard)

Use o botão do Cardboard (ou toque com o dedo) para:

Navegar entre os slides usando os botões: ◀ Anterior e Próximo ▶

🧠 Recursos implementados
Navegação por slides interativos

Botão flutuante para ativar modo VR

Ambiente 3D com:

Chão com textura de grama

Céu 360° com nuvens

Controle de câmera por giroscópio no celular

Compatível com Google Cardboard e navegadores com WebXR
