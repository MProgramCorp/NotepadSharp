# Releases

## [Versão 0.1.0-beta](https://github.com/MProgramCorp/CalculatorPlusPlus/releases/tag/v0.1.0-beta)
*Versão mais recente do Notepad#*

### Motor Gráfico e Desempenho

- **Pipeline DirectX 11 Nativo**: Renderização acelerada por Direct3D 11 sobre C++20, garantindo tempo de resposta instantâneo, latência de entrada nula e digitação extremamente suave.
- **Alocador Segment Heap do Windows 11**: Ativação nativa do alocador de memória de alta performance via manifesto, otimizando a manipulação de grandes volumes de texto e prevenindo fragmentação de heap.
- **Histórico Linear em RAM (Estilo Photoshop)**: Sistema de snapshots em memória RAM com agrupamento contínuo de digitação (*debounce*), assegurando operações de desfazer e refazer instantâneas e sem perda de dados.

### Interface e Design Fluent (UI/UX)

- **Identidade Visual Windows 11 Fluent**: Tema escuro com acabamento acrílico, tipografia adaptativa Segoe UI e ícone de alta resolução integrado diretamente aos recursos da aplicação.
- **Sistema de Abas Dinâmico**: Abas fluidas com suporte a reordenação por arrasto, botão dedicado `+` para criação rápida e navegação simples.
- **Arrastar e Soltar (Drag & Drop)**: Suporte completo para arrastar arquivos de texto de qualquer pasta do Windows Explorer diretamente para dentro do editor.

### Recursos de Edição, Correção e Produtividade

- **Persistência e Restauração de Sessão**: Fechamento instantâneo sem popups obstrutivos. O *SessionManager* grava automaticamente todas as abas, cursores e rascunhos em disco (`%LocalAppData%\NotepadSharp\session\`) e restaura tudo ao reabrir.
- **Paleta de Comandos Rápida (`Ctrl+P`)**: Centro de controle integrado para busca e acionamento de qualquer recurso ou atalho através do teclado.
- **Localizar e Substituir Completo (`Ctrl+F` / `Ctrl+H`)**: Painel de busca em tempo real com realce de termos, sensibilidade a maiúsculas (*Match Case*), palavras inteiras (*Whole Word*) e suporte a Expressões Regulares (*Regex*).
- **Conversores e Transformações Inline**: Ferramentas embutidas para conversão de texto (UPPERCASE, lowercase, camelCase, snake_case, kebab-case), codificação Base64 e URL, formatador/minificador de JSON e XML, e avaliador de cálculos matemáticos inline.

## Funcionalidades:

- **Edição Fluida de Texto**: Cursor responsivo, contagem precisa de linhas, colunas, caracteres e codificação (UTF-8 / CRLF / LF).
- **Barra de Título Integrada**: Header unificado moderno com menus, fixação no topo e controles de janela sem barras pretas legadas.
- **Sistema Multi-Abas Inteligente**: Crie, alterne, reordene e feche abas com rapidez, com indicador de alteração pendente (`*`).
- **Menu de Contexto de Aba**: Feche a aba ativa, feche outras abas, feche abas à direita, copie o caminho do arquivo ou abra a pasta no Windows Explorer.
- **Restauração de Sessão Contínua**: Fechamento rápido sem interrupções e recuperação integral do ambiente de trabalho na inicialização.
- **Descarte Individual Seguro**: Opção de salvar ou descartar alterações pendentes ao fechar uma aba individual específica.
- **Corretor Ortográfico Integrado**: Verificação em tempo real sem travar a interface e dicionário pessoal expansível.
- **Paleta de Comandos (Ctrl+P)**: Encontre e execute comandos e conversores instantaneamente via digitação.
- **Busca e Substituição (Ctrl+F / Ctrl+H)**: Navegação bidirecional por ocorrências com suporte a regex e substituição unitária ou global.
- **Manipulação Rápida de Linhas**: Duplicação de linha (`Ctrl+D`), exclusão rápida (`Ctrl+Shift+K`), movimentação vertical (`Alt+Up` / `Alt+Down`) e comentários (`Ctrl+/`).
- **Suíte de Transformação de Texto**: Alterne caixas de texto com um comando (Maiúsculas, Minúsculas, camelCase, snake_case, kebab-case).
- **Formatador e Minificador JSON/XML**: Indentação limpa com espaçamento ajustado ou minificação em uma única linha.
- **Codificador / Decodificador Base64 e URL**: Codifique ou decodifique sequências de texto sem necessidade de navegadores ou ferramentas externas.
- **Avaliador de Expressões Matemáticas**: Calcule operações matemáticas diretamente selecionando ou digitando no editor.
- **Inserção de Data e Hora (F5)**: Carimbo de data e hora formatado no padrão local instantaneamente.
- **Fixar Janela no Topo (Ctrl+Shift+T)**: Mantenha suas anotações sempre visíveis sobrepondo outras janelas.
- **Tela Cheia Imersiva (F11)**: Foque totalmente na escrita sem distrações da barra de tarefas.
- **Personalizador de Temas e Cores**: Ajuste fino de paleta visual, contraste e cores de syntax highlighting.

Agradecemos pelo seu apoio contínuo ao Notepad#. Sua opinião é fundamental para nós. Se você tiver alguma dúvida, sugestão ou encontrar algum bug nesta versão Beta, entre em contato ou abra uma issue no repositório. Estamos empenhados em proporcionar a melhor experiência possível aos nossos usuários.
