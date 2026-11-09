# 🎮 Flame V1.2 Free — Guia para Minecraft

**Requisitos:** Windows 10/11 x64, Minecraft Java (Vanilla, Lunar ou outro cliente), mouse. O Flame é um Auto Clicker externo: não precisa de Forge, não injeta DLL nem altera a memória do jogo.

## Usando no Minecraft

1. Abra o Minecraft e entre num mundo.
2. Inicie Flame V1 Free pelo atalho, Setup instalado ou executável portátil.
3. Clique em **INICIAR** ou **ABRIR PAINEL**. O Chrome deve abrir http://127.0.0.1:15700 (endereço local no próprio PC).
4. Em **Janela do Minecraft**, selecione a janela do jogo. Se o Lunar não aparecer, deixe o jogo em foco e pressione **F9**; volte ao painel, atualize a lista e selecione a janela.
5. Escolha LMB (botão esquerdo), RMB (botão direito) ou ambos; ajuste o CPS dos dois separadamente.
6. Selecione **Legit** (1–20 CPS, com intervalos variáveis) ou **Blatant** (1–40 CPS, intervalos mais estáveis).
7. Deixe **Windows SendInput** como método inicial. O método **Mensagens para janela** é experimental.
8. Clique em **PRONTO — ATIVAR**.
9. Retorne ao Minecraft e **segure fisicamente o botão do mouse habilitado**. Os cliques automáticos são enviados somente enquanto a janela escolhida está em foco.

## Atalhos

| Tecla | Efeito |
|---|---|
| F6 | Liga/desliga o Auto Clicker |
| F7 | Pausa ou retoma apenas o clique esquerdo |
| F8 | Para todos os cliques |
| F9 | Vincula a janela que estiver em primeiro plano; depois clique novamente em PRONTO |
| F11 no Minecraft | Alterna tela cheia; o Flame tenta recuperar a janela no mesmo processo |

**Atenção:** o Flame V1.2 não detecta automaticamente inventário ou menu de pausa. Se você continuar segurando o botão com o jogo em foco, poderá haver cliques nesses menus. Use F8 quando necessário.

## Instalação e distribuição

Na página [Releases](https://github.com/luiz123desantos-cyber/Flame-V1-Free/releases/tag/FLAME), verifique se já existe **Flame_V1_Free_Setup.exe**. Caso apareça apenas o ZIP do projeto, o instalador ainda não foi disponibilizado.

Para construir no Windows: extraia todo o ZIP do projeto, execute GERAR_EXE.cmd (produz dist/FlameV1_Free.exe) e CRIAR_INSTALADOR.cmd (produz installer/Flame_V1_Free_Setup.exe). Python e Inno Setup são necessários na máquina que compila, não no computador que utiliza o Setup final.

Pelo GitHub: **Actions → Build Flame V1.2 Free (Windows) → Run workflow → main**. Se a execução terminar com sucesso, baixe o artefato **Flame-V1-Free-Public-Beta-Windows**. O artefato não é publicado automaticamente em Releases.

## Resolução de problemas

- **Não abre localhost:15700:** encerre versões antigas de Flame ou Love157 e reinicie o Flame; a porta pode estar ocupada.
- **Janela em foco: Não:** retorne ao jogo; tente F9 para vincular novamente.
- **Parou após F11:** aguarde a janela voltar. A recuperação automática depende do mesmo PID; se o processo mudar, use F9 e PRONTO novamente.
- **Contador não aumenta:** confirme que clicou em PRONTO, habilitou LMB/RMB e está segurando o botão físico no jogo em foco.
- **Contador sobe, mas Minecraft ignora:** clientes podem usar Raw Input ou rejeitar eventos sintéticos. Nem todo cliente é compatível.
- **Windows impede recompilar (WinError 5):** feche todas as instâncias do executável antes de gerar uma nova.
- **Duas instâncias abertas:** feche a anterior antes de iniciar novamente.

O modo Legit não garante comportamento humano ou indetectabilidade. Alguns servidores proíbem automação de cliques. A opção de limpeza do Flame apaga apenas preferências próprias e não modifica logs do Windows.
