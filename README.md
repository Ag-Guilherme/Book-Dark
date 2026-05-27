# Book-Dark
BookDark — Plataforma de Livros Digitais
O que é
O BookDark (personalizável como "Livro do Gui" ou qualquer outro nome) é uma plataforma web de leitura digital com visual escuro que permite centralizar, organizar e ler livros de diversas fontes em um único lugar. Tudo funciona localmente no navegador, sem necessidade de servidor.
Funcionamento por Tópicos
1. Visual e Interface
Design totalmente escuro com acentos personalizáveis em dourado
7 temas disponíveis: Padrão (dourado), Oceano (ciano), Vampire (vermelho), Floresta (verde), Roxo, Sunset (laranja) e Mono (cinza)
Layout responsivo que funciona em desktop, tablet e celular
Grid de cards com capas dos livros
2. Fontes de Livro Suportadas
PDF — Link direto para arquivo PDF, com leitor integrado que renderiza página por página
Google Drive — Cole o link de compartilhamento do Drive, o livro é exibido via embed oficial do Google
EPUB — Link direto para arquivo EPUB, aberto via iframe
URL — Qualquer link de página web ou arquivo
3. Painel Administrativo (Protegido por Senha)
Senha padrão: admin123
Acessado pelo botão "Admin" no canto superior direito
Funcionalidades do painel:
📚 Livros — Lista todos os livros com busca, botões de editar, copiar URL e excluir
+ Adicionar — Formulário para adicionar novos livros (PDF, Drive, EPUB ou URL)
⚙️ Configurações — Editar o nome da plataforma em tempo real com pré-visualização
🎨 Temas — Visualizar e trocar entre os 7 temas disponíveis
Exportar/Importar — Backup completo em JSON (inclui livros, favoritos, tema e nome)
4. Leitor Integrado
PDF — Renderiza página por página com canvas, botões de navegação (anterior/próxima) e suporte a teclado (setas ← →)
Google Drive — Abre o visualizador nativo do Google Drive dentro de um iframe
EPUB/URL — Exibido via iframe com scroll livre
Painel lateral com livros relacionados
5. Sistema de Favoritos
Qualquer livro pode ser marcado como favorito (ícone de coração)
Aba dedicada "Favoritos" na navegação principal
Salvos no localStorage do navegador
6. Categorias
Ficção, Não-Ficção, HQ/Manga, Técnico, Romance, Terror, Geral
Cada livro é classificado em uma categoria ao ser adicionado
Filtro rápido por abas no topo da página
7. Nome Personalizável
O nome da plataforma pode ser alterado em Admin → Configurações
Aparece no header, na tela de login e no título da aba do navegador
Pré-visualização em tempo real enquanto digita
Botão para restaurar o nome padrão ("Livro do Gui")
8. Edição de Livros
Cada livro pode ser editado pelo botão ✏️ (lápis) na tabela admin
Campos editáveis: Título, Autor, URL do Arquivo, URL da Capa e Categoria
Alterações salvas instantaneamente
9. Persistência de Dados
Todos os dados são salvos no localStorage do navegador
Não precisa de banco de dados ou servidor
Backup exportável/importável em formato JSON
10. Troca de Temas
7 temas acessíveis pelo ícone de paleta (🎨) no header ou pelo admin
Cada tema muda: cor de fundo, cor de destaque (accent), bordas e textos
O tema escolhido é salvo automaticamente
