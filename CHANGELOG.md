# Changelog

Todas as mudanças relevantes do Nexus X são documentadas aqui.

O formato segue [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/) e o projeto adota [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [2.5.0] - 2026-07-23

### Adicionado
- Otimização dedicada para VALORANT: perfis Máximo FPS/Competitivo/Balanceado, prioridade de processo, overlays desativados e ajuste do GameUserSettings.ini com backup e restauração — sem tocar em nada relacionado ao Riot Vanguard (Secure Boot, TPM, VBS/HVCI, serviços do anti-cheat).
- Otimização para mais 5 jogos: Minecraft Java Edition (memória e coletor de lixo da JVM, options.txt), Minecraft Bedrock Edition, EA Sports FC 26, GTA V (Legacy e Enhanced) e Roblox — cada um com o nível de automação compatível com o anti-cheat do próprio jogo.
- Busca por nome e filtro por categoria (FPS, MOBA, Sandbox, Esportes, Mundo Aberto) na tela de Otimizar Jogos.
- Dois novos ajustes no Modo Extremo: núcleos da CPU sempre ativos (sem estacionamento) e USB sempre ativo (sem suspensão seletiva).

### Corrigido
- Lista de otimizações do Modo Extremo agora rola só dentro do próprio quadro, sem rolar a página inteira.
- Animação de entrada dos cards de jogos: antes só o segundo card da grade animava; agora todos entram em cascata.

## [2.4.0] - 2026-07-06

### Adicionado
- Tela de carregamento nova a cada abertura do app: logo, barra de progresso e leitura dos módulos, com transição suave até a interface. Também aparece ao restaurar o app da bandeja.
- Troca de email e de senha direto em Configurações, no novo bloco "Conta e acesso". As duas ações exigem a senha atual, e a troca de email só conclui após confirmar pelo link enviado.

### Melhorado
- Tela inicial da Verificação de Segurança redesenhada: lista das 15 frentes verificadas e painel de varredura com radar animado.
- Lista de apps de inicialização agora entra com animação em cascata e rola apenas dentro do quadro, sem rolar a página.

### Corrigido
- Configurações abria com um "flash" de conteúdo vazio antes de carregar perfil e opções; agora exibe o estado de carregamento até os dados estarem prontos.

## [2.3.0] - 2026-07-06

### Adicionado
- Exclusão opcional da pasta do Nexus X no Windows Defender, para reduzir alertas causados pelas otimizações do app. Pede consentimento explícito na primeira execução e também pode ser ativada depois em Configurações; nunca mexe em nada fora da própria pasta do app nem desliga qualquer proteção do Windows.

### Corrigido
- Limpeza de cache: o espaço "recuperável" mostrado na tela agora reflete o que realmente será apagado. Antes, arquivos protegidos por terem sido usados recentemente entravam no total exibido mas não eram removidos, dando a impressão de que a limpeza não funcionava.

## [2.2.0] - 2026-07-05
- Módulo de Verificação de Segurança (Windows Defender, firewall, processos, persistência, acesso remoto, integridade do sistema e mais).
- RAM e cache de disco turbinados, com mais fontes de limpeza detalhadas.
- Nova lista de itens de inicialização do Windows.

## [2.1.0] - 2026-07-05
- Compra de licença direto pelo app via Asaas (Pix ou cartão).
- Atualização obrigatória antes de liberar o uso quando há nova versão.
- Correção: a licença só é criada depois que o pagamento é confirmado.

## [2.0.1] - 2026-07-04
- Instalador assinado como DXN'T.

## [2.0.0] - 2026-07-04
- Landing page nova.
- Faxina geral no código e otimização do build.

## [1.0.2] - 2026-07-04
- Correção na publicação cross-repo da release.

## [1.0.1] - 2026-07-04
- Auto-update, tela de onboarding, ajustes de bandeja e ícones.
