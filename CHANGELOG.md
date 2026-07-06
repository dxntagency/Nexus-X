# Changelog

Todas as mudanças relevantes do Nexus X são documentadas aqui.

O formato segue [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/) e o projeto adota [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [2.3.0] - 2026-07-06

### Adicionado
- Exclusão opcional da pasta do Nexus X no Windows Defender, para reduzir alertas causados pelas otimizações do app. Pede consentimento explícito na primeira execução e também pode ser ativada depois em Configurações; nunca mexe em nada fora da própria pasta do app nem desliga qualquer proteção do Windows.

### Corrigido
- Limpeza de cache: o espaço "recuperável" mostrado na tela agora reflete o que realmente será apagado. Antes, arquivos protegidos por terem sido usados recentemente entravam no total exibido mas não eram removidos, dando a impressão de que a limpeza não funcionava.

## [2.2.0] — 2026-07-05

Novo módulo de segurança e otimizações de memória mais profundas.

### Adicionado
- Verificação de Segurança: varredura rápida ou profunda que audita antivírus, firewall, processos, acesso remoto, conexões de rede, inicialização, registro, serviços, tarefas agendadas, arquivos suspeitos, USB, drivers e integridade do sistema
- Pontuação de segurança de 0 a 100 com classificação e correção automática em um clique (reativar antivírus, firewall, remover entradas maliciosas, etc.)

### Alterado
- Otimizador de RAM agora libera também a memória em espera (standby) e o cache do sistema, resultado muito maior
- Limpeza de cache cobre 6 fontes (Temp, Windows Update, Prefetch, shaders, etc.) com detalhamento do que será removido
- Lista de programas de inicialização redesenhada com chave de liga/desliga

## [2.1.0] — 2026-07-05

Compra de licença dentro do app e atualização obrigatória.

### Adicionado
- Compra de licença direto pelo app: planos Mensal (R$ 19,90) e Permanente (R$ 79,90), pagamento via Pix ou cartão de crédito, integrado ao Asaas
- QR Code Pix com copia e cola, liberando o acesso automaticamente assim que o pagamento é confirmado

### Alterado
- Atualização deixa de ser opcional: ao detectar uma versão nova, o app mostra uma tela cheia de atualização e reinicia sozinho ao terminar

### Corrigido
- Verificação de acesso mais rigorosa para licenças em status intermediário (pendente, aguardando pagamento)

## [2.0.0] — 2026-07-04

Repaginação completa do app: nova identidade visual, atualização automática e instalador mais leve.

### Adicionado
- Atualização automática: o app verifica novas versões ao abrir, baixa e instala com um clique (pacotes assinados criptograficamente)
- Nova identidade visual completa (design "instrumento de precisão")
- Barra de título customizada integrada ao tema
- Sidebar recolhível com perfil de usuário (foto e nome)
- Onboarding de primeiro acesso
- Ações rápidas na bandeja: Otimizar RAM, Limpar cache e Otimizar rede sem abrir o app
- Instância única: abrir o app novamente traz a janela existente
- Animação na troca entre login e cadastro
- Site oficial com download sempre apontando para a última versão

### Alterado
- Versão exibida na sidebar agora acompanha a versão real do app
- Instalador significativamente menor (binário otimizado)

### Corrigido
- Tela preta ao restaurar o app da bandeja
- Toggle "Iniciar com o Windows" não refletia o estado real
- Inicialização com o Windows agora abre silenciosamente na bandeja
- Ícone desatualizado na barra de tarefas
- Texto da licença no instalador mostrava versão antiga

### Removido
- Login com Google (temporariamente; volta em versão futura)
- Módulos Softwares (After Effects) e Overclock

## [1.0.0] — 2026-04-19

### Adicionado
- Versão inicial: Otimizador de RAM, Limpeza de Cache, Otimizar Rede, Otimizar Jogos (League of Legends), Modo Extremo e Painel Admin
- Autenticação e licenciamento via Supabase
