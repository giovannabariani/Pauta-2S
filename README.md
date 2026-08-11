# Pauta 2S

Versão focada em gestão operacional da pauta.

## Equipe
- Giovanna Bariani — Diretora de estratégia
- Sabrina Santos — Gerente de estratégia
- John Oliveira — Supervisor de estratégia
- Guilherme Dionisio — Gerente de conteúdo
- Michelle Bastos — Supervisora de conteúdo

## Clientes / filtros
- Stella
- Spaten
- GUT
- Pitch
- Effie

## Novo Job
O cadastro agora tem:
- Título
- Cliente
- Complexidade: Alta / Média / Baixa
- Responsáveis
- Início
- Deadline
- TP — Touchpoint
- Status
- Caixa livre de observações
- Link Google Drive / Google Slides
- Link Monday
- Link do brief do cliente

O modelo GET / TO / BY foi removido.

## Visões

### Timeline
Mostra os jobs por período, cliente e responsáveis.

### Por membro
Agora funciona como uma lista operacional, inspirada na referência enviada:
- Nome do job
- Status
- Cliente
- Touchpoint
- Deadline
- Complexidade indicada por cor
- Ações rápidas para iniciar, pausar ou retomar
- Abrir, editar e excluir
- Botão para adicionar um job já atribuído à pessoa

### Por job
Cards com resumo de cada job e seus principais dados.

### Relatório
Mostra:
- Total de jobs visíveis
- Em andamento
- Entregues
- Atrasados
- Distribuição por cliente
- Distribuição por membro da equipe

## Tema
O botão lua / sol alterna entre modo escuro e claro.

## Links
Os links são atalhos. Não há integração automática com Google Drive ou Monday nesta versão.

## Dados
A V4 ainda utiliza `localStorage`, então os dados ficam salvos somente no navegador usado.

Ela tenta migrar automaticamente os jobs existentes da V3.

## Publicação no GitHub
Para atualizar o site:
1. Substitua o arquivo atual por este `index.html`.
2. Mantenha o nome exatamente `index.html`.
3. Substitua também o `README.md`.
4. Faça `Commit changes`.
5. O GitHub Pages publicará a nova versão quando o deploy estiver configurado.
