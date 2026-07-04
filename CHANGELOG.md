# Changelog

Todas as mudanças relevantes do Nexus X são documentadas aqui.

O formato segue [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/) e o projeto adota [Versionamento Semântico](https://semver.org/lang/pt-BR/).

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
