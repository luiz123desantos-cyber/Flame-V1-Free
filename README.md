# 🔥 FLAME V1.2 FREE — Public Beta

Auto Clicker externo para Windows 10/11 (64 bits), com painel local pelo navegador em **http://127.0.0.1:15700**.

**Status:** Beta. Há testes automatizados do motor, mas o instalador precisa ser validado em um PC limpo antes de um lançamento final.

## 🎮 Como usar no Minecraft

1. Abra Minecraft Java, entre em um mundo e inicie o Flame.
2. Na janela Flame, clique em **INICIAR / ABRIR PAINEL**.
3. No Chrome, escolha **Janela do Minecraft**. Se não aparecer, volte ao jogo, pressione **F9**, retorne ao painel e atualize.
4. Ajuste LMB/RMB, CPS e perfil **Legit** (1–20 CPS) ou **Blatant** (1–40 CPS).
5. Escolha **Windows SendInput**, clique em **PRONTO — ATIVAR**, volte ao jogo e **segure o botão físico do mouse**.
6. O Flame só envia cliques enquanto o jogo selecionado está em foco.

**Atalhos:** F6 liga/desliga, F7 pausa apenas LMB, F8 para, F9 vincula janela em foco. Após F11, tenta recuperar a janela se ela permanecer no mesmo processo.

📘 **[Guia completo de instalação e uso no Minecraft e Lunar Client](COMO_USAR_NO_MINECRAFT.md)**

## Funcionalidades

- LMB e RMB independentes com CPS configuráveis.
- Perfis Legit (variação de ritmo) e Blatant (velocidades maiores).
- Detecção de janela do jogo e recuperação após F11 no mesmo PID.
- Painel Chrome local e atalhos de teclado.
- Limpeza restrita às configurações próprias do Flame.

O Flame **não injeta DLL**, não possui Reach/ESP, não limpa logs de segurança e não identifica automaticamente o inventário ou menu de pausa.

## Downloads

Na **[Release FLAME V1.2 FREE](https://github.com/luiz123desantos-cyber/Flame-V1-Free/releases/tag/FLAME)** há o ZIP do projeto. **O Setup Windows ainda não foi confirmado como publicado.**

Para compilar via GitHub, abra **[Actions](https://github.com/luiz123desantos-cyber/Flame-V1-Free/actions)**, selecione **Build Flame V1.2 Free (Windows)** e clique em **Run workflow**. Se passar, baixe o artefato **Flame-V1-Free-Public-Beta-Windows**, teste o executável e só então anexe o Setup à Release.

Para compilar localmente, baixe e extraia o ZIP do projeto e execute GERAR_EXE.cmd e CRIAR_INSTALADOR.cmd. O PC que usa um Setup compilado não precisa instalar Python; somente o PC que compila precisa das ferramentas de desenvolvimento.

**Limites:** alguns clientes usam Raw Input e podem ignorar cliques sintéticos. Os perfis não garantem indetectabilidade. O uso pode contrariar regras de servidores. A licença de redistribuição do código ainda não foi definida.
