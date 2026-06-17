# Do Zero ao Deploy - Plano do Curso

## Visao Geral
Curso para **iniciantes absolutos** que nao sabem nada de programacao/infraestrutura.
Tom: passo a passo, didatico, muitos exemplos de terminal com output esperado, diagramas SVG mostrando conceitos visuais, boxes "O que voce vai ver na tela", boxes de erro comum + solucao.

## Course ID: `dzd`
## Formato: formato-curso-v2 (INEMA.CLUB)

## Estrutura - 5 Trilhas

### Trilha 1: Terminal & Git (cor: emerald)
Modulo 1.1 - O Terminal: Seu Primeiro Comando
- O que e terminal/CMD/PowerShell (6 topicos)
- Abrir o terminal (Windows/Mac/Linux com passo a passo visual)
- Navegacao: cd, ls/dir, pwd (com output esperado)
- Criar/mover/copiar arquivos: mkdir, touch, cp, mv, rm
- Editores no terminal: nano/code
- Exercicio: criar estrutura de projeto do zero

Modulo 1.2 - Git: Salvando Seu Trabalho
- O que e controle de versao (analogia: ctrl+z infinito)
- Instalar Git (passo a passo por OS)
- git init, add, commit (ciclo basico)
- git log, diff, status (entendendo o que mudou)
- Branches: criar, trocar, mergear
- .gitignore: o que NAO versionar

Modulo 1.3 - GitHub: Sua Casa na Nuvem
- Criar conta no GitHub
- Tokens de acesso (PAT) - passo a passo
- git remote, push, pull
- GitHub Pages: ativar e publicar
- Codex/Copilot: IA no codigo

Modulo 1.4 - Projeto: Sua Primeira Pagina
- Criar repo no GitHub
- HTML/CSS basico (o minimo pra funcionar)
- Publicar no GitHub Pages
- Dominio personalizado (opcional)

### Trilha 2: Deploy Moderno (cor: blue)
Modulo 2.1 - Vercel: Deploy em 1 Clique
- O que e deploy e por que Vercel
- Criar conta e conectar GitHub
- Primeiro deploy automatico
- Preview deploys (branches)
- Configuracoes de projeto
- Dominios customizados

Modulo 2.2 - Supabase: Seu Banco de Dados
- O que e um banco de dados
- Criar projeto no Supabase
- Tabelas, colunas, tipos
- Inserir e consultar dados (interface)
- API automatica do Supabase
- Autenticacao basica

Modulo 2.3 - APIs: Conectando Servicos
- O que e uma API (analogia: cardapio de restaurante)
- GET, POST, PUT, DELETE
- Testando APIs com curl e Postman/Thunder Client
- Conectar frontend a API do Supabase
- APIs publicas (clima, CEP, etc.)
- Tratamento de erros

Modulo 2.4 - Variaveis de Ambiente
- O que sao e por que existem
- .env local
- Variaveis no Vercel
- Variaveis no GitHub Actions
- Seguranca: o que NUNCA commitar
- Rotacao de secrets

### Trilha 3: Servidor Proprio (cor: purple)
Modulo 3.1 - VPS: Seu Computador na Nuvem
- O que e um VPS (analogia: alugar um computador)
- Provedores: DigitalOcean, Hetzner, Contabo
- Contratar seu primeiro VPS
- Primeiro acesso via console web
- Entendendo Linux no servidor
- Atualizacao e manutencao basica

Modulo 3.2 - SSH: Acesso Seguro
- O que e SSH (analogia: tunel secreto)
- Gerar par de chaves ssh-keygen
- Copiar chave publica pro servidor
- Conectar via ssh
- Alias e config SSH (~/.ssh/config)
- Desabilitar acesso por senha

Modulo 3.3 - Firewall e Protecao
- O que e firewall (analogia: porteiro do predio)
- UFW: permitir/negar portas
- Portas essenciais: 22, 80, 443
- Fail2ban: bloquear tentativas de invasao
- Certificado SSL com Let's Encrypt
- Checklist de seguranca

Modulo 3.4 - Tokens e Gestao de Acesso
- Tipos de token (API key, JWT, PAT, OAuth)
- Armazenar tokens no servidor (.env)
- Rotacao e expiracao
- Secrets managers (basico)
- Auditoria de acesso
- Boas praticas

### Trilha 4: Docker & Automacao (cor: amber)
Modulo 4.1 - Docker para Iniciantes
- O que e container (analogia: mala de viagem completa)
- Instalar Docker
- docker run: seu primeiro container
- Imagens vs containers
- Dockerfile: receita de container
- Build e push

Modulo 4.2 - Docker Compose: Multi-Servicos
- O que e Compose (analogia: orquestra)
- docker-compose.yml basico
- Servicos, redes, volumes
- Subir stack completa (app + banco)
- Logs e debug
- Atualizacao e rollback

Modulo 4.3 - Systemd: Servicos que Nunca Param
- O que e systemd (analogia: gerente de plantao)
- Criar um service file
- start, stop, restart, enable
- Logs com journalctl
- Dependencias entre servicos
- Restart automatico

Modulo 4.4 - Cron: Tarefas Automaticas
- O que e cron (analogia: despertador programavel)
- Sintaxe crontab (* * * * *)
- crontab -e: adicionar tarefas
- Exemplos praticos (backup, limpeza, relatorio)
- Logs de cron
- Alternativas: systemd timers

### Trilha 5: Assistentes IA (cor: teal)
Modulo 5.1 - Jarvis: Seu Assistente Pessoal
- O que e um assistente IA pessoal
- Arquitetura basica (bot + LLM + tools)
- Telegram Bot API
- Conectar com Claude/GPT
- Skills e comandos
- Deploy do assistente no VPS

Modulo 5.2 - Intelecto: IA Autonoma
- Do assistente ao agente autonomo
- Agendamento de tarefas (schedule)
- Memoria persistente
- Integracao com servicos (email, calendario)
- Monitoramento e logs
- Evolucao continua

## Manifesto (incluir em TODA pagina, identico)
```json
{
  "course": "dzd",
  "tracks": [
    { "n": "1", "title": "Terminal & Git", "modules": [
      { "id": "1-1", "title": "O Terminal", "topics": 6, "href": "curso/trilha1/modulo-1-1.html" },
      { "id": "1-2", "title": "Git Essencial", "topics": 6, "href": "curso/trilha1/modulo-1-2.html" },
      { "id": "1-3", "title": "GitHub e Pages", "topics": 6, "href": "curso/trilha1/modulo-1-3.html" },
      { "id": "1-4", "title": "Projeto: Landing Page", "topics": 6, "href": "curso/trilha1/modulo-1-4.html" }
    ]},
    { "n": "2", "title": "Deploy Moderno", "modules": [
      { "id": "2-1", "title": "Vercel", "topics": 6, "href": "curso/trilha2/modulo-2-1.html" },
      { "id": "2-2", "title": "Supabase", "topics": 6, "href": "curso/trilha2/modulo-2-2.html" },
      { "id": "2-3", "title": "APIs", "topics": 6, "href": "curso/trilha2/modulo-2-3.html" },
      { "id": "2-4", "title": "Variaveis de Ambiente", "topics": 6, "href": "curso/trilha2/modulo-2-4.html" }
    ]},
    { "n": "3", "title": "Servidor Proprio", "modules": [
      { "id": "3-1", "title": "VPS", "topics": 6, "href": "curso/trilha3/modulo-3-1.html" },
      { "id": "3-2", "title": "SSH", "topics": 6, "href": "curso/trilha3/modulo-3-2.html" },
      { "id": "3-3", "title": "Firewall", "topics": 6, "href": "curso/trilha3/modulo-3-3.html" },
      { "id": "3-4", "title": "Tokens e Acesso", "topics": 6, "href": "curso/trilha3/modulo-3-4.html" }
    ]},
    { "n": "4", "title": "Docker & Automacao", "modules": [
      { "id": "4-1", "title": "Docker Basico", "topics": 6, "href": "curso/trilha4/modulo-4-1.html" },
      { "id": "4-2", "title": "Docker Compose", "topics": 6, "href": "curso/trilha4/modulo-4-2.html" },
      { "id": "4-3", "title": "Systemd", "topics": 6, "href": "curso/trilha4/modulo-4-3.html" },
      { "id": "4-4", "title": "Cron Jobs", "topics": 6, "href": "curso/trilha4/modulo-4-4.html" }
    ]},
    { "n": "5", "title": "Assistentes IA", "modules": [
      { "id": "5-1", "title": "Jarvis", "topics": 6, "href": "curso/trilha5/modulo-5-1.html" },
      { "id": "5-2", "title": "Intelecto", "topics": 6, "href": "curso/trilha5/modulo-5-2.html" }
    ]}
  ]
}
```

## Diretriz Didatica Principal
- TUDO passo a passo numerado
- Terminal: mostrar EXATAMENTE o que digitar e o que aparece (code blocks com $ prompt e output)
- Boxes "O que voce vai ver" com SVG simulando a tela/interface
- Boxes "Erro comum" com problema + solucao
- Analogias em TODA secao (iniciante absoluto)
- Grid Fazer vs Evitar em todo modulo
- Timeline para processos multi-etapa
- Exercicios praticos no final de cada topico
