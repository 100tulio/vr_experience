# vr_experience
VR-Experience
✅ PASSO A PASSO PARA EXECUTAR SUA EXPERIÊNCIA VR
🗂️ 1. Organize os arquivos
Coloque todos os arquivos abaixo na mesma pasta, por exemplo:

makefile
Copiar
Editar
C:\Users\Marco Tulio\Downloads\Teste_VR\vr_template_aframe1
Arquivos obrigatórios:

index.html (código final que te enviei)

grama.jpg (imagem do chão)

ceu-nuvens-360.jpg (imagem do céu 360°)

Slides:

1_Resumo-Geral-das-Principais-IAs-2025.png

2_IA-de-Texto-Multimodal.png

3_IA-de-Imagem.png

4_IA-de-Voz-Audio.png

5_IA-de-Video.png

6_IA-para-Codigo-e-Dados.png

7_IA-para-Apresentacoes.png

🐍 2. Execute um servidor local com Python
Requisitos: Python 3 já instalado no seu computador.

Abra o Prompt de Comando (CMD) ou PowerShell.

Vá até a pasta com os arquivos:

bash
Copiar
Editar
cd "C:\Users\Marco Tulio\Downloads\Teste_VR\vr_template_aframe1"
Rode o servidor local:

bash
Copiar
Editar
python -m http.server 8080
Você verá algo como:

nginx
Copiar
Editar
Serving HTTP on :: port 8080 (http://[::]:8080/) ...
🌐 3. Descubra seu IP local
No mesmo terminal, digite:

bash
Copiar
Editar
ipconfig
Copie o IPv4 Address, por exemplo:

yaml
Copiar
Editar
Endereço IPv4. . . . . . . . . . . . . . : 10.10.101.2
📱 4. Acesse no navegador do celular
O celular e o PC precisam estar na mesma rede Wi-Fi!

Abra o navegador do seu celular (Chrome ou Safari).

Digite na barra de endereços:

cpp
Copiar
Editar
http://10.10.101.2:8080
A página da sua apresentação VR será carregada.

🕶️ 5. Ativar o modo VR no celular
Toque no botão azul: 🕶 Entrar em VR

A tela será dividida automaticamente (modo estereoscópico).

Coloque o celular no Google Cardboard ou VR Box.

Use o movimento da cabeça para olhar em volta (giroscópio ativo).

Use o botão do óculos (ou toque na tela) para clicar nos botões "◀ Anterior" ou "Próximo ▶".
