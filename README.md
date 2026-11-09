# 🔥 FLAME V1.2 FREE — Public Beta

Auto Clicker externo para Windows 10/11 com painel local no navegador em `http://127.0.0.1:15700`.

**Status:** pré-lançamento. Ainda faltam testes do instalador em um Windows limpo e de compatibilidade com Lunar Client real.

## Funcionalidades
- Cliques esquerdo (LMB) e direito (RMB) configuráveis separadamente.
- **Legit:** 1–20 CPS com intervalos variáveis.
- **Blatant:** 1–40 CPS com intervalos mais regulares.
- Seleção de janela Minecraft/Java e recuperação após F11 quando o PID continua igual.
- F6 ativa/desativa, F7 pausa o esquerdo, F8 para, F9 vincula a janela em foco.
- Configurações e limpeza local, sem alterar logs de segurança do Windows.

## Como obter o instalador
1. O código original do projeto será enviado no arquivo `Flame_V1_2_GitHub_Ready.zip` (ainda precisa ser anexado ao repositório).
2. Quando o ZIP estiver no repositório, a aba **Actions → Flame Windows Build** executará os testes e criará o instalador.
3. Na execução concluída, abra **Artifacts → Flame-Windows-Beta** para baixar os dois arquivos: `FlameV1_Free.exe` e `Flame_V1_Free_Setup.exe`.
4. **Teste o instalador e faça uma verificação antivírus antes de publicar uma Release.**

A compilação é feita pelo GitHub Actions no Windows; quem usa o instalador não precisa instalar Python. O projeto contém os arquivos .py, HTML/CSS/JS, ícones, scripts, testes e instalador Inno Setup.

## Transparência
- Este projeto automatiza cliques e pode contrariar regras de servidores.
- Os nomes dos perfis não representam garantia de indetectabilidade.
- Esta versão não injeta DLL, não tem Reach ou ESP e não remove logs do Windows.
- Código ainda sem licença de redistribuição definida.

**Importante:** até o ZIP aparecer neste repositório e o Actions gerar os artefatos, **não há download público de instalador pronto**.
