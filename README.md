# Notepad#

Notepad# é um editor de texto moderno, ultraleve e de alto desempenho desenvolvido pela **MProgram Corp.** com o objetivo de unir a simplicidade do clássico bloco de notas à produtividade dos editores de código modernos. O software combina a elegância visual do **Fluent Design** do Windows 11 com o poder do **C++20** e a aceleração gráfica do **DirectX 11**, oferecendo uma experiência de digitação extremamente fluida, com corretor ortográfico nativo, paleta de comandos rápida, conversores de texto embutidos e persistência de sessão contínua com consumo zero de recursos em repouso.

---

## Pré-requisitos

- **Sistema Operacional**: Windows 10 ou Windows 11 (64-bit recomendados). *(Obs: Em outras versões do Windows, o Notepad# não foi testado!)*
- **Permissões**: O aplicativo roda como processo de usuário comum, sem necessidade de privilégios de Administrador.

O Notepad# é um executável nativo em C++20 com pipeline gráfico DirectX 11 dedicado e alocador de memória de alta performance *Segment Heap*, livre de dependências pesadas e pronto para uso imediato sem necessidade de instalador.

---

## Funcionalidades

### Interface e Experiência do Usuário (UI/UX)
- **Barra Superior Unificada (Estilo Windows 11 / Calculator++)**: Header integrado de 34px contendo o ícone oficial da aplicação, menus nativos de acesso rápido, título centralizado do documento em edição, alternância de janela sempre no topo (Pin) e controles de minimizar, maximizar e fechar com realce suave.
- **Alocador de Memória Segment Heap**: Otimizado para alocação de memória nativa moderna no Windows 11, reduzindo a fragmentação e acelerando a manipulação de arquivos volumosos.
- **Arrastar e Soltar (Drag & Drop)**: Arraste arquivos de texto diretamente do Windows Explorer para dentro da janela do editor para abri-los instantaneamente em novas abas.

### Sistema Multi-Abas e Persistência
- **Gerenciamento Fluido de Abas**: Crie novas abas com um clique (`+`), reordene abas dinamicamente arrastando-as e navegue rapidamente através da lista compacta.
- **Menu de Contexto de Abas**: Clique com o botão direito sobre qualquer aba para fechar, fechar outras abas, fechar abas à direita, copiar o caminho do arquivo no disco ou abrir a pasta do documento no Windows Explorer.
- **Restauração de Sessão Sem Bloqueios**: Feche o programa a qualquer momento (`Alt+F4` ou no botão `✕`) de forma instantânea. O Notepad# salva automaticamente todas as abas, arquivos não salvos e rascunhos em disco (`%LocalAppData%\NotepadSharp\session\`) e restaura tudo exatamente onde você parou ao reabrir.
- **Descarte Individual Seguro**: Caso decida fechar uma aba específica individualmente com alterações não salvas, o editor disponibiliza confirmação para salvar ou descartar com segurança.

### Edição de Texto e Correção Ortográfica
- **Histórico Linear em RAM (Estilo Photoshop)**: Sistema de histórico de snapshots com agrupamento contínuo de digitação (*debounce*), permitindo desfazer (`Ctrl+Z`) e refazer (`Ctrl+Y`) ações complexas com máxima integridade.
- **Manipulação Rápida de Linhas**: Duplique linhas (`Ctrl+D`), apague linhas inteiras (`Ctrl+Shift+K`), mova linhas para cima/baixo (`Alt+Up` / `Alt+Down`) e alterne comentários de código (`Ctrl+/`).
- **Localizar e Substituir Avançado (`Ctrl+F` / `Ctrl+H`)**: Busca em tempo real com realce de ocorrências, diferenciação entre maiúsculas/minúsculas (*Match Case*), correspondência de palavras inteiras (*Whole Word*) e suporte a expressões regulares (*Regex*).

### Ferramentas, Conversores e Produtividade
- **Paleta de Comandos (`Ctrl+P`)**: Acesso instantâneo a todos os recursos, comandos de menu, formatações e utilitários através de busca rápida pelo teclado.
- **Transformações de Texto**: Conversão instantânea de seleção para **UPPERCASE**, **lowercase**, **camelCase**, **snake_case** e **kebab-case**.
- **Formatador e Minificador**: Formatação (*Prettify*) com indentação e minificação (*Minify*) de documentos **JSON** e **XML**.
- **Codificador / Decodificador**: Codificação e decodificação rápida nos formatos **Base64** e **URL Encode**.
- **Avaliador Matemático Inline**: Calcule expressões matemáticas diretamente dentro do texto com um único comando.
- **Personalizador de Temas e Cores**: Ajuste a paleta de cores do editor, cores de sintaxe e fundo através do painel integrado de customização.

---

## Como usar

1. Faça o download do [Notepad# v0.1.0-beta](https://github.com/MProgramCorp/NotepadSharp/releases/tag/v0.1.0-beta) (versão mais recente).
2. Execute o arquivo `NotepadSharp.exe`.
3. Comece a digitar imediatamente ou utilize `Ctrl+O` para abrir arquivos existentes.
4. Utilize `Ctrl+P` para abrir a **Paleta de Comandos** e explorar todos os recursos e atalhos disponíveis.
5. Feche a janela a qualquer momento com a tranquilidade de que suas abas e textos rascunhados serão preservados automaticamente na próxima abertura.

---

## Principais Atalhos de Teclado

| Atalho | Ação |
| :--- | :--- |
| `Ctrl + N` | Nova aba / Novo documento |
| `Ctrl + O` | Abrir arquivo do disco |
| `Ctrl + S` | Salvar documento atual |
| `Ctrl + Shift + S` | Salvar como... |
| `Ctrl + W` | Fechar aba atual |
| `Ctrl + P` | Abrir Paleta de Comandos |
| `Ctrl + F` | Abrir painel de Localizar |
| `Ctrl + H` | Abrir painel de Substituir |
| `Ctrl + Z` / `Ctrl + Y` | Desfazer / Refazer |
| `Ctrl + D` | Duplicar linha atual |
| `Ctrl + Shift + K` | Deletar linha atual |
| `Alt + Up` / `Alt + Down` | Mover linha para cima / baixo |
| `Ctrl + /` | Comentar / Descomentar linha |
| `Ctrl + Shift + T` | Fixar janela no topo (*Always on Top*) |
| `F11` | Alternar modo Tela Cheia |
| `F5` | Inserir data e hora atual |
| `Ctrl + 0` | Resetar zoom do editor (100%) |

---

## Contribuição

Contribuições para o projeto são sempre bem-vindas! Se você tiver alguma sugestão, melhoria ou encontrar algum problema:
1. Abra uma **Issue** relatando o caso ou propondo uma nova ferramenta.
2. Envie um **Pull Request** com suas alterações.

---

## Contato

- **Suporte**: [suporte@mprogram.com.br](mailto:suporte@mprogram.com.br)
- **Sugestões e Contato Geral**: [contato@mprogram.com.br](mailto:contato@mprogram.com.br)
- **Organização GitHub**: [MProgramCorp](https://github.com/MProgramCorp)

---

## Licença

Veja o arquivo [LICENSE.md](LICENSE.md) para os termos de uso do software.

## Notas de Lançamento

Veja o arquivo [RELEASES.md](RELEASES.md) para o histórico completo de versões e notas de lançamento do Notepad#.

---

Agradecemos pelo seu apoio contínuo ao **Notepad#**. Estamos comprometidos em oferecer a melhor experiência possível. Entre em contato conosco para sugestões ou feedback.
