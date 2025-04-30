MATERIAL DE TREINAMENTO PARA MODERADORES E ADMINISTRADORES

Este manual abrangente destina-se aos moderadores e administradores da plataforma Moodle da empresa. Aqui você encontrará instruções detalhadas e aprofundadas sobre todas as funcionalidades disponíveis para gerenciamento completo do ambiente de aprendizagem, incluindo configurações avançadas, personalização e automação.

## O que você vai encontrar neste manual

Como administrador ou moderador do Moodle, você terá acesso a funcionalidades avançadas que permitem controlar todos os aspectos da plataforma. Este manual detalha:

- Configuração completa do ambiente
- Gerenciamento de usuários e permissões
- Criação e organização de cursos
- Personalização visual com o tema Boost Magnific
- Configuração de trilhas de aprendizagem
- Automação de processos e mensagens
- Geração de relatórios avançados
- Procedimentos de backup e restauração
- Otimização de desempenho

## Funções e Responsabilidades do Administrador

Como administrador/moderador da plataforma Moodle, suas principais responsabilidades incluem:

1. **Manutenção do ambiente**: garantir que a plataforma esteja funcionando corretamente e disponível para todos os usuários
2. **Gerenciamento de usuários**: criar, modificar e excluir contas, atribuir papéis e permissões
3. **Organização estrutural**: configurar categorias, cursos e módulos de aprendizagem
4. **Personalização**: adaptar a plataforma à identidade visual e necessidades da empresa
5. **Suporte**: auxiliar professores e alunos na utilização da plataforma
6. **Monitoramento**: acompanhar o uso do sistema e o progresso geral dos participantes
7. **Backup**: garantir a segurança dos dados e a possibilidade de recuperação em caso de problemas

## Navegação pelo Manual

Utilize o menu lateral para navegar pelos diferentes capítulos deste manual. Cada seção contém instruções detalhadas, passo a passo, para realizar as diversas tarefas administrativas. Recomendamos que você leia o manual completo para ter uma visão abrangente das capacidades do sistema, mesmo que inicialmente utilize apenas algumas funcionalidades específicas.

As seções estão organizadas em ordem lógica, começando com as configurações básicas e avançando para recursos mais avançados. Entretanto, você pode acessar diretamente qualquer capítulo de acordo com sua necessidade atual.

Vamos começar explorando o acesso e configuração inicial da plataforma.

## Índice

1. [Acesso e Configuração Inicial](#acesso-e-configuração-inicial)
   - [Acesso à Plataforma](#acesso-à-plataforma)
   - [Painel de Administração](#painel-de-administração)
   - [Configurações Gerais do Site](#configurações-gerais-do-site)
   - [Configurações de Segurança](#configurações-de-segurança)
2. [Gerenciamento de Usuários](#gerenciamento-de-usuários)
   - [Visualizar Usuários](#visualizar-usuários)
   - [Adicionar Novos Usuários](#adicionar-novos-usuários)
   - [Sincronização com Diretório Corporativo](#sincronização-com-diretório-corporativo-ldapactive-directory)
   - [Excluir ou Suspender Usuários](#excluir-ou-suspender-usuários)
   - [Atribuir Funções e Permissões](#atribuir-funções-e-permissões)
3. [Gerenciamento de Cursos](#gerenciamento-de-cursos)
   - [Criar Categorias de Cursos](#criar-categorias-de-cursos)
   - [Criar um Novo Curso](#criar-um-novo-curso)
   - [Configurações Avançadas de Cursos](#configurações-avançadas-de-cursos)
   - [Importar Conteúdo Entre Cursos](#importar-conteúdo-entre-cursos)
   - [Duplicar Cursos](#duplicar-cursos)
   - [Excluir ou Ocultar Cursos](#excluir-ou-ocultar-cursos)
   - [Restaurar um Curso a partir de Backup](#restaurar-um-curso-a-partir-de-backup)
4. [Trilhas de Aprendizagem e Cursos Modulares](#trilhas-de-aprendizagem-e-cursos-modulares)
   - [Configuração de Pré-requisitos](#configuração-de-pré-requisitos)
   - [Configuração de Conclusão Condicional](#configuração-de-conclusão-condicional)
   - [Criação de Cursos Modulares (Metacursos)](#criação-de-cursos-modulares-metacursos)
   - [Liberação Progressiva de Conteúdo](#liberação-progressiva-de-conteúdo)
   - [Criação de Programas de Certificação](#criação-de-programas-de-certificação)
5. [Avaliações e Feedback](#avaliações-e-feedback)
   - [Questionários com Correção Automática](#questionários-com-correção-automática)
   - [Atividades com Envio de Arquivos](#atividades-com-envio-de-arquivos)
   - [Feedback Automatizado ou Personalizado](#feedback-automatizado-ou-personalizado)
   - [Avaliação de Reação com Performance por Curso/Módulo](#avaliação-de-reação-com-performance-por-cursomdulo)
6. [Relatórios e Monitoramento](#relatórios-e-monitoramento)
   - [Relatórios de Desempenho e Progresso](#relatórios-de-desempenho-e-progresso)
   - [Rastreamento de Acessos e Atividades](#rastreamento-de-acessos-e-atividades)
   - [Emissão de Certificados](#emissão-de-certificados)
   - [Controle de Presença](#controle-de-presença)
7. [Fóruns e Espaços de Discussão](#fóruns-e-espaços-de-discussão)
   - [Tipos de Fóruns e Configuração](#tipos-de-fóruns-e-configuração)
   - [Moderação e Acompanhamento](#moderação-e-acompanhamento)
8. [Recursos Didáticos Interativos](#recursos-didáticos-interativos)
   - [Inserção e Gerenciamento de Mídias](#inserção-e-gerenciamento-de-mídias)
   - [Atividades Interativas Adicionais](#atividades-interativas-adicionais)
9. [Personalização da Plataforma](#personalização-da-plataforma)
   - [Adaptação da Identidade Visual](#adaptação-da-identidade-visual)
   - [Criação de Diferentes Perfis](#criação-de-diferentes-perfis)
10. [Automação de Processos](#automação-de-processos)
    - [Automatização de Mensagens](#automatização-de-mensagens)
    - [Automatização de Processos de Curso](#automatização-de-processos-de-curso)
11. [Controle de Turmas e Inscrições](#controle-de-turmas-e-inscrições)
    - [Inscrição Manual e Auto-inscrição](#inscrição-manual-e-auto-inscrição)
    - [Organização de Grupos e Turmas](#organização-de-grupos-e-turmas)
    - [Monitoramento e Gerenciamento de Turmas](#monitoramento-e-gerenciamento-de-turmas)
12. [Backup e Restauração](#backup-e-restauração)
    - [Backup de Cursos](#backup-de-cursos)
    - [Restauração de Cursos](#restauração-de-cursos)
13. [Manutenção e Otimização](#manutenção-e-otimização)
    - [Otimizar Desempenho da Plataforma](#otimizar-desempenho-da-plataforma)
    - [Monitoramento da Plataforma](#monitoramento-da-plataforma)
    - [Práticas Recomendadas](#práticas-recomendadas)

## Acesso e Configuração Inicial

### Acesso à Plataforma

1. Abra o navegador web (recomendamos Chrome, Firefox ou Edge atualizados)
2. Digite o endereço da plataforma Moodle na barra de endereços
3. Na página de login, utilize as mesmas credenciais da intranet da empresa/Windows
4. Caso seja seu primeiro acesso como administrador, você deverá atualizar a senha temporária fornecida pelo administrador principal

### Painel de Administração

O painel de administração é o centro de controle da plataforma. Para acessá-lo:

1. Clique no ícone de engrenagem (⚙️) no canto superior direito da tela
2. Selecione "Administração do site" no menu suspenso

Alternativamente:
- No bloco de Administração (geralmente à esquerda), clique em "Administração do site"

O painel de administração contém as seguintes seções principais:
- **Usuários**: gerenciamento de contas, permissões e políticas de privacidade
- **Cursos**: configurações, formatos e backup/restauração de cursos
- **Notas**: configurações do livro de notas e relatórios
- **Plugins**: gerenciamento de extensões, blocos e filtros do sistema
- **Aparência**: temas, logotipos e elementos de interface
- **Servidor**: configurações de desempenho, cache e caminhos
- **Relatórios**: logs, estatísticas e análises de atividades
- **Desenvolvimento**: documentação e ferramentas para desenvolvedores

### Configurações Gerais do Site

1. No painel de administração, acesse "Administração do site" → "Configurações gerais"
2. Configure os parâmetros fundamentais:
   - **Nome completo do site**: aparecerá no topo das páginas e nos e-mails
   - **Nome curto do site**: aparecerá na barra de navegação
   - **Descrição da página inicial**: texto que aparece na página inicial para usuários não logados
   - **Formato da página inicial**: para usuários logados (pode ser por lista de cursos ou baseado em painéis)
   - **Itens de notícias**: número de anúncios que aparecerão na página inicial
   - **Política do site**: defina textos para termos de uso e política de privacidade

3. Seção "Contato":
   - Preencha informações do administrador do site (nome, e-mail, etc.)
   - Configure e-mail de suporte que receberá as dúvidas dos usuários

4. Seção "Localização":
   - Defina país, fuso horário e formato de datas padrão
   - Configure o idioma principal e os idiomas que estarão disponíveis

5. Clique em "Salvar alterações" ao final

### Configurações de Segurança

1. No painel de administração, acesse "Administração do site" → "Segurança" → "Políticas do site"
2. Configure políticas de senhas:
   - Comprimento mínimo (recomendado: 8 caracteres)
   - Complexidade (números, maiúsculas, minúsculas, caracteres especiais)
   - Período de validade da senha (dias até expirar)
   - Histórico de senhas (evitar reutilização)

3. Configure políticas de login:
   - Número de tentativas permitidas antes de bloqueio
   - Período de bloqueio após tentativas falhas
   - Duração da sessão (tempo até logout automático por inatividade)

4. Configure a política de cookies:
   - Mensagem de consentimento
   - Períodos de retenção de dados

## Gerenciamento de Usuários

### Visualizar Usuários

1. No painel de administração, acesse "Usuários" → "Contas" → "Navegar na lista de usuários"
2. Você verá uma tabela com todos os usuários cadastrados na plataforma
3. Recursos da lista de usuários:
   - **Filtros**: filtre por nome, e-mail, último acesso, curso, etc.
   - **Colunas personalizáveis**: clique no botão "Mostrar mais..." para adicionar/remover colunas
   - **Exportação**: exporte a lista para CSV ou outro formato usando o botão "Baixar tabela como"
   - **Ações em massa**: selecione múltiplos usuários para realizar ações como enviar mensagem, excluir ou atribuir funções

### Adicionar Novos Usuários

#### Adição Manual

1. No painel de administração, acesse "Usuários" → "Contas" → "Adicionar um novo usuário"
2. Preencha os campos obrigatórios (marcados com asterisco):
   - **Nome e sobrenome**
   - **Nome de usuário** (recomendado usar o mesmo da intranet)
   - **Endereço de e-mail** (verifique a formatação correta)
   - **Senha** (ou deixe o sistema gerar uma senha temporária marcando "Criar senha e notificar usuário")
3. Configure campos adicionais:
   - **Cidade e país**
   - **Fuso horário** (importante para prazos e agendamentos)
   - **Idioma preferido**
   - **Descrição** (informações complementares sobre o usuário)
4. Opções avançadas:
   - **Interesses**: tags para identificar áreas de interesse
   - **Imagem do usuário**: foto de perfil (tamanho recomendado: 100x100 pixels)
   - **Opções de e-mail**: configurações de como o usuário receberá e-mails do sistema
5. Clique em "Criar usuário"
6. Após a criação, você será redirecionado para a página de atribuição de funções, onde poderá definir o nível de acesso do usuário

#### Importação em Massa

1. No painel de administração, acesse "Usuários" → "Contas" → "Carregar usuários"
2. Prepare um arquivo CSV com os dados dos usuários:
   - A primeira linha deve conter os nomes dos campos
   - Campos mínimos: username, firstname, lastname, email
   - Use vírgula como separador e aspas para delimitar textos
3. Exemplo de estrutura do CSV:
   ```
   username,password,firstname,lastname,email,city,country
   joao.silva,Temp123$,João,Silva,joao.silva@empresa.com,São Paulo,BR
   maria.santos,Temp123$,Maria,Santos,maria.santos@empresa.com,Rio de Janeiro,BR
   ```
4. Carregue o arquivo usando o botão "Escolher arquivo"
5. Configure as opções de importação:
   - **Delimitador CSV**: geralmente vírgula (,)
   - **Codificação**: UTF-8 recomendado para caracteres especiais
   - **Preview rows**: número de linhas para visualizar na pré-importação
6. Clique em "Carregar usuários" para iniciar a importação
7. Na tela de pré-visualização, mapeie os campos do CSV para os campos do Moodle
8. Configure as opções adicionais:
   - **Atualizar usuários existentes**: sim/não
   - **Permitir renomeações**: sim/não
   - **Permitir exclusões**: sim/não
   - **Função padrão**: atribuição automática de função para todos os importados
9. Clique em "Carregar usuários" para confirmar

### Sincronização com Diretório Corporativo (LDAP/Active Directory)

O Moodle pode ser configurado para sincronizar automaticamente com o diretório de usuários da empresa:

1. No painel de administração, acesse "Plugins" → "Autenticação" → "Gerenciar autenticação"
2. Ative o plugin "LDAP server" ou "Active Directory"
3. Configure os parâmetros de conexão:
   - **Host**: endereço do servidor LDAP/AD
   - **Porta**: geralmente 389 (LDAP) ou 636 (LDAP seguro)
   - **Versão**: versão do protocolo LDAP
   - **Base DN**: ponto inicial da busca (ex: ou=users,dc=empresa,dc=com)
   - **Credenciais de acesso**: usuário e senha com permissão para consulta
4. Configure o mapeamento de campos:
   - Defina quais campos do LDAP correspondem aos campos do Moodle
   - Configure quais grupos/OUs serão sincronizados
5. Defina a periodicidade da sincronização
6. Execute uma sincronização manual para testar a configuração

### Excluir ou Suspender Usuários

#### Exclusão de Usuários

1. No painel de administração, acesse "Usuários" → "Contas" → "Navegar na lista de usuários"
2. Localize o usuário usando os filtros ou a barra de pesquisa
3. Clique no ícone de engrenagem ao lado do nome do usuário
4. Selecione "Excluir" no menu suspenso
5. Você terá duas opções:
   - **Exclusão completa**: remove todos os dados do usuário (use com cautela)
   - **Anonimização**: mantém registros de atividades mas anonimiza dados pessoais (recomendado para conformidade com LGPD)
6. Confirme a exclusão na caixa de diálogo

**Importante:** A exclusão de usuários pode afetar dados históricos, relatórios e atividades. Considere suspender contas em vez de excluí-las se precisar manter registros.

#### Suspensão de Contas

1. No painel de administração, acesse "Usuários" → "Contas" → "Navegar na lista de usuários"
2. Localize o usuário a ser suspenso
3. Clique no ícone de engrenagem ao lado do nome do usuário
4. Selecione "Editar" no menu suspenso
5. Na seção "Geral", localize o campo "Conta suspensa" e altere para "Sim"
6. Opcionalmente, adicione uma nota no campo "Razão da suspensão" (visível apenas para administradores)
7. Clique em "Salvar alterações"

A suspensão tem os seguintes efeitos:
- O usuário não poderá fazer login na plataforma
- Seus dados permanecem intactos
- Suas atividades anteriores são preservadas
- A conta pode ser reativada facilmente alterando "Conta suspensa" para "Não"

### Atribuir Funções e Permissões

#### Funções Globais

As funções globais aplicam-se a todo o site:

1. No painel de administração, acesse "Usuários" → "Permissões" → "Atribuir funções globais"
2. Selecione a função desejada:
   - **Administrador**: acesso total a todas as áreas do site
   - **Gerente**: acesso a maioria das áreas, exceto algumas configurações técnicas
   - **Criador de curso**: pode criar novos cursos
   - **Usuário autenticado**: função básica atribuída automaticamente após login
3. Na página seguinte, verá duas colunas:
   - À esquerda: usuários que já possuem a função
   - À direita: usuários potenciais para atribuição
4. Busque usuários na coluna direita usando o campo de pesquisa
5. Selecione um ou mais usuários e clique no botão "Adicionar"
6. Os usuários selecionados agora aparecerão na coluna esquerda com a função atribuída

#### Funções em Categorias de Cursos

1. No painel de administração, acesse "Cursos" → "Gerenciar cursos e categorias"
2. Localize a categoria desejada
3. Clique no ícone de engrenagem ao lado do nome da categoria
4. Selecione "Atribuir funções" no menu suspenso
5. Selecione a função a ser atribuída:
   - **Gerente da categoria**: gerencia todos os cursos na categoria
   - **Professor**: pode ensinar em todos os cursos da categoria
   - **Aluno**: inscrito automaticamente em todos os cursos da categoria
6. Atribua a função seguindo o mesmo processo descrito para funções globais

#### Funções em Cursos Específicos

1. Acesse o curso desejado
2. No bloco de administração, clique em "Usuários" → "Participantes"
3. Clique no botão "Inscrever usuários"
4. Busque usuários pelo nome ou e-mail
5. Selecione a função apropriada para cada usuário (Professor, Professor não-editor, Aluno, etc.)
6. Configure opções adicionais:
   - **Duração da inscrição**: período válido da inscrição
   - **Início da inscrição**: data de início
   - **Método de inscrição**: manual, auto-inscrição, etc.
7. Clique em "Inscrever usuários"

#### Personalização de Funções

1. No painel de administração, acesse "Usuários" → "Permissões" → "Definir funções"
2. Você verá a lista de todas as funções do sistema
3. Para editar uma função existente:
   - Clique no ícone de engrenagem ao lado do nome da função
   - Selecione "Editar" no menu suspenso
4. Para criar uma nova função:
   - Clique em "Adicionar uma nova função"
   - Ou use "Duplicar" em uma função existente para criar com base nela
5. Na página de edição, configure:
   - **Nome curto**: identificador único da função
   - **Nome personalizado**: nome exibido na interface
   - **Descrição**: detalhes sobre a finalidade da função
   - **Tipo de função**: contexto em que a função será disponível (sistema, categoria, curso, etc.)
6. Na seção "Permissões", configure cada capacidade:
   - **Permitir**: concede a permissão
   - **Impedir**: nega a permissão, mas pode ser sobrescrita
   - **Proibir**: nega a permissão e não pode ser sobrescrita
   - **Não definido**: usa a configuração padrão
7. Clique em "Salvar alterações" quando terminar

**Dicas para configuração de permissões:**
- Organize por contexto (Aparência, Cursos, Usuários, etc.) para facilitar
- Busque permissões específicas usando o campo de pesquisa
- Teste a nova função em um ambiente controlado antes de implementar amplamente
- Documente as alterações feitas para referência futura

## Gerenciamento de Cursos

### Criar Categorias de Cursos

As categorias ajudam a organizar cursos por departamento, tema ou nível:

1. No painel de administração, acesse "Cursos" → "Adicionar uma categoria"
2. Preencha os campos:
   - **Nome da categoria**: nome que aparecerá na lista de cursos
   - **Nome curto**: identificador abreviado (opcional)
   - **ID de número**: código para integração com sistemas externos (opcional)
   - **Descrição**: informações detalhadas sobre a categoria
   - **Mostrar contagem de cursos**: exibe número de cursos na categoria
3. Na seção "Categoria pai", defina a hierarquia:
   - Selecione "Top" para uma categoria de nível superior
   - Ou escolha uma categoria existente para criar uma subcategoria
4. Clique em "Criar categoria"

#### Organização Hierárquica de Categorias

Crie uma estrutura de categorias e subcategorias para refletir a organização da empresa:
- **Departamentos**: RH, Comercial, Operações, etc.
  - **Subcategorias por nível**: Iniciante, Intermediário, Avançado
  - **Subcategorias por tema**: Liderança, Técnico, Comportamental
- **Público-alvo**: Gestores, Colaboradores, Novos funcionários
- **Tipo de conteúdo**: Treinamentos obrigatórios, Desenvolvimento, Processos internos

### Criar um Novo Curso

1. No painel de administração, acesse "Cursos" → "Adicionar um novo curso"
2. Preencha os campos na seção "Geral":
   - **Nome completo do curso**: título completo que aparecerá nos cabeçalhos e listas
   - **Nome curto do curso**: abreviação (aparece na navegação e URLs)
   - **Categoria do curso**: selecione a categoria onde o curso será listado
   - **Visibilidade**: "Mostrar" (visível para alunos) ou "Ocultar" (visível apenas para professores)
   - **Data de início**: quando o curso estará disponível para os alunos
   - **Data de término**: quando o curso será encerrado (opcional)
   - **ID do curso**: código para integração com sistemas externos (opcional)

3. Seção "Descrição":
   - **Sumário do curso**: breve descrição que aparecerá na lista de cursos
   - **Imagem do curso**: imagem de destaque (tamanho recomendado: 1200x400 pixels)
   - **Arquivos adicionais do sumário**: documentos suplementares que aparecerão na descrição

4. Seção "Formato de curso":
   - **Formato**: escolha entre:
     - **Formato de tópicos**: organizado por temas, sem cronograma específico
     - **Formato semanal**: organizado por semanas, com datas automáticas
     - **Formato social**: baseado em um único fórum de discussão
     - **Formato em atividade única**: exibe apenas uma atividade ou recurso
   - **Número de seções**: quantas seções/semanas o curso terá
   - **Seções ocultas**: como mostrar seções ocultas (totalmente ocultas ou visíveis de forma condensada)
   - **Layout do curso**: como as seções serão exibidas (todas na mesma página ou uma seção por página)

5. Seção "Aparência":
   - **Forçar idioma**: define um idioma específico para o curso
   - **Itens de notícias para mostrar**: número de posts recentes exibidos
   - **Mostrar livro de notas aos estudantes**: permite que alunos vejam suas notas
   - **Mostrar relatório de atividades**: permite que alunos vejam suas atividades recentes

6. Seção "Arquivos e envios":
   - **Tamanho máximo de arquivo enviado**: limite para uploads de arquivos no curso

7. Seção "Acompanhamento de conclusão":
   - **Habilitar acompanhamento de conclusão**: ativa o rastreamento de atividades concluídas
   - **Conclusão esperada em**: data prevista para conclusão do curso

8. Seção "Grupos":
   - **Modo de grupo**: define como os grupos funcionarão no curso (sem grupos, grupos separados, grupos visíveis)
   - **Forçar modo de grupo**: aplica a configuração de grupo a todas as atividades do curso

9. Clique em "Salvar e exibir" para criar o curso e acessá-lo, ou "Salvar e voltar" para retornar à lista de cursos

### Configurações Avançadas de Cursos

Após criar o curso, você pode configurar opções adicionais:

1. Acesse o curso e clique no ícone de engrenagem (⚙️)
2. Selecione "Editar configurações" para retornar à tela de configuração
3. Opções adicionais incluem:
   - **Restrições de acesso**: limite o acesso com base em datas, grupos ou outros critérios
   - **Conclusão do curso**: defina critérios automáticos para marcar o curso como concluído
   - **Tags do curso**: adicione palavras-chave para facilitar a busca
   - **Competências do curso**: vincule o curso a frameworks de competências

### Importar Conteúdo Entre Cursos

1. Acesse o curso de destino (onde deseja importar o conteúdo)
2. No bloco de administração, clique em "Importar"
3. Selecione o curso de origem (de onde deseja importar o conteúdo)
4. Escolha quais elementos deseja importar:
   - Atividades específicas
   - Blocos
   - Filtros
   - Grupos
   - Configurações do livro de notas
5. Configure as opções de importação:
   - **Incluir atividades e recursos**: selecione os itens específicos a importar
   - **Incluir blocos**: importa a configuração dos blocos laterais
   - **Incluir filtros**: mantém as configurações de filtros de texto
6. Clique em "Importar" e aguarde a conclusão do processo

### Duplicar Cursos

1. No painel de administração, acesse "Cursos" → "Gerenciar cursos e categorias"
2. Localize o curso que deseja duplicar
3. Clique no ícone de engrenagem ao lado do nome do curso
4. Selecione "Duplicar" no menu suspenso
5. Configure as opções da duplicação:
   - **Nome completo do novo curso**
   - **Nome curto do novo curso**
   - **Data de início do novo curso**
   - **Incluir atividades e recursos**: selecione quais elementos duplicar
   - **Incluir dados de usuários**: opcional, copia envios e notas (use com cautela)
6. Clique em "Continuar" e aguarde a conclusão da duplicação

### Excluir ou Ocultar Cursos

#### Ocultar um Curso

1. No painel de administração, acesse "Cursos" → "Gerenciar cursos e categorias"
2. Localize o curso a ser ocultado
3. Clique no ícone de olho ao lado do nome do curso para alternar sua visibilidade
4. O ícone mudará indicando que o curso está oculto para os alunos
5. Administradores e professores ainda podem ver o curso (com indicação visual de que está oculto)

#### Excluir um Curso

1. No painel de administração, acesse "Cursos" → "Gerenciar cursos e categorias"
2. Localize o curso a ser excluído
3. Clique no ícone de engrenagem ao lado do nome do curso
4. Selecione "Excluir" no menu suspenso
5. Confirme a exclusão na caixa de diálogo

**Importante:** A exclusão de um curso remove permanentemente todo o seu conteúdo, atividades, notas e registros de conclusão. Considere fazer um backup antes da exclusão.

### Restaurar um Curso a partir de Backup

1. No painel de administração, acesse "Cursos" → "Restaurar curso"
2. Selecione uma das opções:
   - **Escolher um arquivo**: carregue um arquivo de backup (.mbz)
   - **Área de backup do usuário**: use um backup previamente salvo
   - **Área de backup do curso**: use um backup automático ou manual de um curso
3. Depois de selecionar o arquivo, clique em "Restaurar"
4. Revise os detalhes do backup e clique em "Continuar"
5. Escolha o destino da restauração:
   - **Restaurar como um novo curso**: cria um curso inteiramente novo
   - **Restaurar em um curso existente**: substitui ou mescla com conteúdo existente
   - **Mesclar com o curso atual**: adiciona conteúdo ao curso atual
6. Configure as opções detalhadas da restauração:
   - **Conteúdo do curso**: selecione quais elementos restaurar
   - **Configuração do curso**: ajuste configurações como nome, categoria, etc.
   - **Definições de restauração**: defina se deseja incluir dados de usuários, grupos, etc.
7. Clique em "Executar restauração" e aguarde a conclusão do processo

## Trilhas de Aprendizagem e Cursos Modulares

### Configuração de Pré-requisitos

O Moodle permite criar sequências de aprendizagem definindo pré-requisitos:

1. No painel de administração, certifique-se de que "Restrições de acesso" esteja habilitado em "Plugins" → "Plugins de disponibilidade" → "Gerenciar restrições"
2. Acesse o curso onde deseja configurar pré-requisitos
3. Ative a edição do curso
4. Para cada atividade ou recurso que requer pré-requisitos:
   - Clique no ícone de edição (lápis) e selecione "Editar configurações"
   - Vá até a seção "Restringir acesso"
   - Clique em "Adicionar restrição" → "Conclusão de atividade"
   - Selecione a atividade que deve ser concluída antes
   - Configure a condição (deve/não deve estar concluída)
   - Defina se a restrição ficará visível ou oculta para os alunos
5. Salve as alterações

Exemplo de sequência:
- Vídeo introdutório → Quiz inicial → Material de estudo → Atividade prática → Avaliação final

### Configuração de Conclusão Condicional

1. Certifique-se de que "Acompanhamento de conclusão" esteja habilitado no curso
2. Para cada atividade ou recurso:
   - Acesse as configurações da atividade
   - Vá até a seção "Conclusão de atividade"
   - Selecione "Mostrar atividade como concluída quando as condições forem satisfeitas"
   - Configure as condições de conclusão:
     - **Visualização**: marcada quando o aluno visualiza a atividade
     - **Nota**: requer uma nota mínima para conclusão
     - **Envio**: requer que o aluno envie algo
     - **Data**: concluída automaticamente em uma data específica
     - **Duração**: requer um tempo mínimo de interação
3. Salve as alterações

### Criação de Cursos Modulares (Metacursos)

Os metacursos permitem agrupar vários cursos em uma estrutura maior:

1. Crie os cursos individuais que servirão como módulos
2. Crie um novo curso que servirá como o metacurso principal
3. No metacurso, habilite o método de inscrição "Metacurso":
   - No bloco de administração, clique em "Usuários" → "Métodos de inscrição"
   - Clique no ícone de olho ao lado de "Metacurso" para ativá-lo
   - Clique no ícone de configuração para adicionar os cursos-filho
   - Selecione os cursos que devem fazer parte desta trilha
4. Configure se a conclusão de todos os cursos-filho será necessária para a conclusão do metacurso

### Liberação Progressiva de Conteúdo

1. Acesse o curso e ative a edição
2. Para cada seção ou tópico que deve ser liberado progressivamente:
   - Clique no ícone de edição (engrenagem) da seção
   - Selecione "Editar seção"
   - Vá até "Restringir acesso"
   - Clique em "Adicionar restrição" e escolha:
     - **Data**: disponível a partir de uma data específica
     - **Conclusão de atividade**: disponível após a conclusão de outra atividade
     - **Nota**: disponível após obter determinada nota em outra atividade
     - **Grupo**: disponível apenas para grupos específicos
     - **Perfil de usuário**: baseado em campos do perfil
3. Combine múltiplas restrições usando operadores "e/ou"
4. Configure se a restrição ficará visível ou oculta para os alunos
5. Salve as alterações

### Criação de Programas de Certificação

1. Crie uma categoria específica para o programa de certificação
2. Crie os cursos que compõem o programa dentro desta categoria
3. Configure pré-requisitos entre os cursos (como descrito anteriormente)
4. Crie um curso principal que servirá como "dashboard" do programa:
   - Adicione um recurso "Página" com a visão geral do programa
   - Use o bloco "Curso concluído" para exibir o progresso em todos os cursos
   - Configure o certificado final que será emitido ao completar todo o programa

## Avaliações e Feedback

### Questionários com Correção Automática

#### Criar um Questionário

1. Acesse o curso e ative a edição
2. Clique em "Adicionar uma atividade ou recurso"
3. Selecione "Questionário"
4. Configure as opções básicas:
   - **Nome**: título do questionário
   - **Descrição**: instruções detalhadas para os alunos
   - **Exibir descrição na página do curso**: se as instruções aparecerão na página principal
5. Configure o tempo:
   - **Abrir questionário**: data e hora de início
   - **Fechar questionário**: data e hora de término
   - **Limite de tempo**: duração máxima para completar (ex: 30 minutos)
   - **Quando o tempo expirar**: o que acontece quando o tempo acaba (envio automático, tempo extra, etc.)
6. Configure a nota:
   - **Categoria de nota**: onde as notas serão armazenadas no livro de notas
   - **Tentativas permitidas**: quantas vezes o aluno pode refazer o questionário
   - **Método de avaliação**: como calcular a nota final (maior nota, média, primeira ou última tentativa)
7. Configure o layout:
   - **Ordem das questões**: fixa ou aleatória
   - **Nova página**: quantas questões por página
   - **Método de navegação**: sequencial (deve seguir a ordem) ou livre (pode pular questões)
8. Configure o comportamento das questões:
   - **Embaralhar dentro das questões**: reorganiza alternativas em questões de múltipla escolha
   - **Comportamento da questão**: como as questões funcionam (feedback imediato, postergado, etc.)
   - **Permitir reenvio**: se o aluno pode tentar novamente durante a mesma tentativa
9. Configure as opções de revisão (quando o aluno pode ver o quê):
   - **Durante a tentativa**: o que é visível enquanto o questionário está sendo realizado
   - **Imediatamente após a tentativa**: logo após enviar
   - **Mais tarde, enquanto o questionário ainda estiver aberto**
   - **Depois que o questionário for fechado**
10. Salve as configurações para criar o questionário

#### Adicionar Questões ao Questionário

1. Após criar o questionário, clique em "Editar questionário"
2. Você verá a interface do banco de questões
3. Clique em "Adicionar" e selecione:
   - **Uma nova questão**: criar do zero
   - **Do banco de questões**: usar questões existentes
   - **Uma questão aleatória**: selecionar aleatoriamente do banco
4. Para criar uma nova questão, selecione o tipo:

##### Múltipla Escolha
1. Selecione "Múltipla escolha" e clique em "Adicionar"
2. Configure os campos básicos:
   - **Nome da questão**: identificador interno
   - **Texto da questão**: o enunciado
   - **Pontuação padrão**: valor da questão
   - **Feedback geral**: mostrado após a resposta
   - **Uma ou múltiplas respostas**: define se mais de uma alternativa pode ser correta
3. Configure as alternativas:
   - **Escolha 1, 2, 3...**: texto de cada alternativa
   - **Nota**: 100% para correta, nenhuma para incorreta (ou porcentagens parciais)
   - **Feedback**: mensagem específica para cada alternativa
4. Configure opções avançadas:
   - **Penalidade para cada tentativa incorreta**: redução da nota em tentativas adicionais
   - **Dicas**: ajuda adicional mostrada em tentativas posteriores
5. Salve a questão

##### Verdadeiro/Falso
1. Selecione "Verdadeiro/Falso" e clique em "Adicionar"
2. Configure os campos básicos
3. Defina qual resposta é correta (Verdadeiro ou Falso)
4. Configure feedback específico para cada resposta
5. Salve a questão

##### Associação
1. Selecione "Associação" e clique em "Adicionar"
2. Configure os campos básicos
3. Adicione pelo menos 3 pares de correspondência:
   - **Pergunta 1, 2, 3...**: primeiro item do par
   - **Resposta 1, 2, 3...**: segundo item correspondente
4. Salve a questão

##### Resposta Curta
1. Selecione "Resposta curta" e clique em "Adicionar"
2. Configure os campos básicos
3. Adicione as respostas possíveis:
   - **Resposta 1, 2, 3...**: texto exato que será aceito
   - **Nota**: porcentagem para cada resposta (100% para totalmente correta)
   - **Diferenciar maiúsculas de minúsculas**: se a capitalização importa
4. Salve a questão

##### Numérica
1. Selecione "Numérica" e clique em "Adicionar"
2. Configure os campos básicos
3. Configure as respostas:
   - **Resposta**: o valor numérico correto
   - **Erro**: margem de tolerância (ex: ±0.01)
   - **Nota**: porcentagem para cada resposta
4. Adicione unidades de medida, se necessário
5. Salve a questão

##### Dissertativa
1. Selecione "Dissertativa" e clique em "Adicionar"
2. Configure os campos básicos
3. Configure as opções:
   - **Formato da resposta**: HTML, texto simples, etc.
   - **Tamanho da caixa de entrada**: dimensões do campo de resposta
   - **Permitir anexos**: número de arquivos que podem ser enviados
4. Adicione informações para o avaliador
5. Salve a questão

##### Calculada
1. Selecione "Calculada" e clique em "Adicionar"
2. Configure os campos básicos, inserindo variáveis com {a}, {b}, etc.
3. Insira a fórmula para calcular a resposta usando as mesmas variáveis
4. Configure o conjunto de dados:
   - **Valor mínimo e máximo** para cada variável
   - **Número de casas decimais**
   - **Distribuição dos valores** (uniforme ou logarítmica)
5. Gere e revise os valores que serão usados
6. Salve a questão

#### Gerenciar o Banco de Questões

1. No bloco de administração do curso, clique em "Banco de questões"
2. Você verá a lista de todas as questões do curso
3. Opções disponíveis:
   - **Categorias**: organize questões em categorias e subcategorias
   - **Importar**: carregue questões de formatos como GIFT, Moodle XML, etc.
   - **Exportar**: salve questões para uso em outros cursos
   - **Criar categoria**: adicione uma nova estrutura de organização
4. Para gerenciar em massa:
   - Selecione múltiplas questões usando as caixas de seleção
   - Use o menu "Com as questões selecionadas..." para mover, excluir ou duplicar

### Atividades com Envio de Arquivos

#### Criar uma Tarefa

1. Acesse o curso e ative a edição
2. Clique em "Adicionar uma atividade ou recurso"
3. Selecione "Tarefa"
4. Configure as opções básicas:
   - **Nome da tarefa**: título da atividade
   - **Descrição**: instruções detalhadas para os alunos
   - **Arquivos adicionais**: materiais de apoio para a tarefa
5. Configure a disponibilidade:
   - **Permitir envios a partir de**: data de início
   - **Data de entrega**: prazo recomendado
   - **Data limite**: prazo final (após essa data, envios são marcados como atrasados)
   - **Lembrar-me de avaliar em**: definir lembretes para correção
6. Configure os tipos de envio:
   - **Tipos de envio aceitos**:
     - **Texto online**: editor do Moodle
     - **Envios de arquivos**: upload de documentos
     - **Conteúdo de questionário**: importado de outra atividade
   - **Limite de palavras**: para envios de texto
   - **Número máximo de arquivos**: quantos arquivos podem ser enviados
   - **Tipos de arquivo aceitos**: restrinja a formatos específicos (pdf, doc, etc.)
7. Configure as opções de feedback:
   - **Tipos de feedback**: comentários, arquivo de feedback, planilha offline
   - **Configurações de comentários**: opções para anotações no envio
8. Configure as opções de envio:
   - **Exigir que os estudantes aceitem o termo de envio**: declaração de trabalho original
   - **Exigir que os estudantes cliquem no botão enviar**: diferencia rascunhos de envios finais
   - **Tentativas reabertas**: definir como lidar com reenvios
9. Configure as opções de grupo:
   - **Envio em grupo**: permite que grupos enviem um único trabalho
   - **Requer que todos os membros do grupo enviem**: exige confirmação de todos
10. Configure as notas:
    - **Nota**: pontuação máxima
    - **Método de avaliação**: simples direta, guia de avaliação ou rubrica
    - **Categoria de nota**: onde a nota aparecerá no livro de notas
11. Salve as configurações

#### Criar Rubrica ou Guia de Avaliação

Para avaliação mais estruturada, crie uma rubrica:

1. Após criar a tarefa, acesse suas configurações novamente
2. Na seção "Nota", selecione "Rubrica" como método de avaliação
3. Clique em "Salvar e exibir"
4. Clique em "Definir um novo formulário do zero"
5. Configure a rubrica:
   - **Nome da rubrica**: título para identificação
   - **Descrição**: instruções para avaliadores
6. Adicione critérios (linhas):
   - Clique em "Adicionar critério"
   - Digite o nome e descrição do critério (ex: "Estrutura", "Conteúdo", "Originalidade")
7. Para cada critério, adicione níveis (colunas):
   - Clique em "Adicionar nível"
   - Configure descrição e pontuação para cada nível
8. Configure as opções:
   - **Permitir que os usuários vejam os pontos para cada nível**: mostra pontuação para alunos
   - **Mostrar pontuação para níveis durante a avaliação**
   - **Permitir que avaliadores adicionem comentários para cada critério**
9. Clique em "Salvar rubrica e torná-la pronta"

### Feedback Automatizado ou Personalizado

#### Configurar Feedback Automático em Questionários

1. Ao criar questões de um questionário, configure:
   - **Feedback geral da questão**: mostrado a todos após responderem
   - **Feedback específico por alternativa**: mostrado conforme a escolha do aluno
   - **Feedback combinado**: baseado em padrões de resposta específicos
2. Para feedback baseado no desempenho geral:
   - Acesse as configurações do questionário
   - Vá para a seção "Feedback geral"
   - Adicione mensagens para diferentes faixas de nota (ex: 0-50%, 51-80%, 81-100%)
   - Os alunos verão a mensagem correspondente à sua faixa de nota

#### Feedback Personalizado em Tarefas

1. Para avaliar uma tarefa com feedback detalhado:
   - Acesse a tarefa e clique em "Ver/avaliar todos os envios"
   - Clique em "Nota" para um envio específico
2. Forneça feedback de várias formas:
   - **Comentários de feedback**: texto geral sobre o trabalho
   - **Arquivos de feedback**: envie documentos comentados ou modelos
   - **Comentários em linha**: para envios de texto, edite diretamente o texto do aluno
   - **Anotações PDF**: para envios em PDF, adicione comentários diretamente no documento
3. Se estiver usando rubrica:
   - Selecione o nível apropriado para cada critério
   - Adicione comentários específicos por critério
4. Clique em "Salvar alterações" para finalizar a avaliação

#### Feedback em Massa

1. Para fornecer feedback a múltiplos alunos rapidamente:
   - Acesse a tarefa e clique em "Ver/avaliar todos os envios"
   - Selecione "Avaliação rápida" para habilitar a edição direta na tabela
   - Insira notas e comentários breves para vários alunos
   - Clique em "Salvar todas as avaliações rápidas" ao terminar

### Avaliação de Reação com Performance por Curso/Módulo

1. Para criar uma avaliação de reação (feedback sobre o curso):
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Pesquisa" ou "Feedback"
2. Configure a atividade "Feedback":
   - **Nome**: título da avaliação de reação
   - **Descrição**: explique o propósito da avaliação
   - **Disponibilidade**: quando os alunos podem responder
   - **Configurações de envio**: anônimo ou com identificação
3. Após criar, clique em "Editar perguntas"
4. Adicione questões relevantes:
   - Escala de satisfação (1-5 estrelas)
   - Múltipla escolha para avaliação de aspectos específicos
   - Campo de texto para comentários qualitativos
5. Organize as questões em páginas lógicas
6. Para análise:
   - Acesse "Análise" na atividade de feedback
   - Visualize gráficos e estatísticas das respostas
   - Exporte os dados para análise externa
7. Crie relatórios personalizados combinando:
   - Dados da avaliação de reação (satisfação)
   - Performance no curso (notas e conclusão)
   - Tempo de acesso e engajamento

## Relatórios e Monitoramento

### Relatórios de Desempenho e Progresso

#### Relatório de Notas

1. No bloco de administração do curso, clique em "Notas"
2. Na visão padrão, você verá a tabela completa com todos os alunos e atividades
3. Para personalizar a visualização:
   - Clique na aba "Configurações"
   - Selecione "Relatório de notas"
   - Configure quais colunas e informações serão exibidas
4. Filtros disponíveis:
   - Por grupo ou agrupamento
   - Por nome (pesquisa)
   - Por atividade
5. Para exportar dados:
   - Selecione a aba "Exportar"
   - Escolha o formato (Excel, texto, XML, etc.)
   - Configure quais informações incluir
   - Clique em "Baixar"

#### Relatório de Conclusão de Curso

1. No bloco de administração do curso, clique em "Relatórios" → "Conclusão do curso"
2. Este relatório mostra o status de conclusão de cada aluno para cada atividade
3. Filtros disponíveis:
   - Por nome do aluno
   - Por grupo
   - Por status de conclusão
4. Para cada atividade, você verá:
   - Se foi concluída (✓)
   - Data de conclusão
   - Se não foi concluída (✗)
5. Para exportar:
   - Selecione o formato na parte inferior
   - Configure as opções
   - Clique em "Baixar"

#### Relatório de Competências

Se você usa competências no seu Moodle:

1. No painel de administração do site, acesse "Competências" → "Relatórios" → "Relatório de competências"
2. Selecione o framework de competências
3. Configure os filtros:
   - Usuário específico ou todos
   - Curso específico ou todos
   - Período de tempo
4. Analise o relatório que mostra:
   - Competências alcançadas/não alcançadas
   - Evidências para cada competência
   - Nível de proficiência atingido

### Rastreamento de Acessos e Atividades

#### Logs de Atividade

1. No bloco de administração do curso, clique em "Relatórios" → "Logs"
2. Configure os filtros:
   - **Curso**: curso atual ou todos os cursos
   - **Participantes**: usuário específico ou todos
   - **Data**: período específico
   - **Atividades**: específica ou todas
   - **Ações**: tipo de interação (visualização, envio, etc.)
   - **Eventos educacionais**: relacionados ao aprendizado
3. Clique em "Obter estes logs" para gerar o relatório
4. Os logs mostram detalhes como:
   - Data e hora exata
   - Nome completo do usuário
   - Evento (o que aconteceu)
   - Contexto (onde aconteceu)
   - Componente (parte do Moodle envolvida)
   - Endereço IP
5. Para análise mais detalhada, exporte os logs

#### Relatório de Atividades do Curso

1. No bloco de administração do curso, clique em "Relatórios" → "Atividade do curso"
2. Selecione o recurso ou atividade específica para analisar
3. Visualize informações como:
   - Número total de visualizações
   - Último acesso
   - Usuários que nunca acessaram
4. Para detalhar por usuário, clique no número de visualizações

#### Relatório de Participação

1. No bloco de administração do curso, clique em "Relatórios" → "Participação"
2. Configure as opções:
   - **Atividade específica**: selecione qual atividade analisar
   - **Mostrar apenas**: todos, visualizações ou envios
   - **Mostrar ações**: desde sempre ou período específico
   - **Grupos**: todos ou um grupo específico
3. Clique em "Ir" para gerar o relatório
4. O relatório mostra:
   - Lista de participantes
   - Contagem de ações (visualizações/envios)
   - Última ação realizada
5. Use as opções no final para:
   - Selecionar usuários específicos
   - Enviar mensagem aos selecionados
   - Exportar dados

#### Tempo Online e Engajamento

1. No bloco de administração do curso, clique em "Relatórios" → "Estatísticas"
2. Selecione o período de tempo para análise
3. Visualize gráficos mostrando:
   - Visualizações por dia/semana
   - Atividades por horário do dia
   - Envios por período
4. Para análise detalhada de um usuário específico:
   - Clique em seu nome na lista de participantes
   - Acesse a aba "Relatórios de atividade"
   - Visualize o gráfico de engajamento mostrando padrões de acesso

### Emissão de Certificados

#### Configurar Certificados

1. Ative a edição do curso
2. Clique em "Adicionar uma atividade ou recurso"
3. Selecione "Certificado"
4. Configure as opções básicas:
   - **Nome**: título do certificado
   - **Descrição**: informações sobre o certificado
   - **Texto do certificado**: conteúdo que aparecerá no certificado
5. Personalize o layout:
   - **Imagem de fundo**: carregue uma imagem personalizada
   - **Bordas**: selecione uma borda decorativa
   - **Selo/Logo**: adicione uma marca oficial
   - **Assinatura**: imagem da assinatura do emissor
6. Configure o texto:
   - **Fonte, tamanho e cores**
   - **Posição dos elementos**
   - **Texto dinâmico**: use variáveis como {USERNAME}, {COURSE}, {DATE}
7. Configure os critérios de emissão:
   - **Data de emissão**: quando o certificado estará disponível
   - **Condições para emissão**: baseadas na conclusão do curso
   - **Nota mínima necessária**: se aplicável
8. Salve as configurações

#### Critérios de Emissão Automática

1. Para vincular o certificado à conclusão do curso:
   - Certifique-se de que o acompanhamento de conclusão esteja ativado
   - Configure critérios de conclusão para o curso:
     - No bloco de administração, clique em "Editar configurações"
     - Vá para a seção "Conclusão do curso"
     - Selecione "Critérios de conclusão"
2. Configure os critérios:
   - **Conclusão de atividade**: requer a conclusão de atividades específicas
   - **Conclusão dependente**: todas ou algumas das atividades selecionadas
   - **Data**: conclusão automática após uma data específica
   - **Duração após inscrição**: período específico após o início
   - **Nota do curso**: requer uma nota mínima para conclusão
3. Vincule o certificado aos critérios:
   - Nas configurações do certificado, vá para "Restrição de acesso"
   - Adicione a restrição "Conclusão de curso"
   - Configure para mostrar o certificado apenas quando o curso for concluído

#### Gerenciar Certificados Emitidos

1. Acesse a atividade de certificado no curso
2. Clique na aba "Relatório"
3. Você verá a lista de todos os certificados emitidos com:
   - Nome do usuário
   - Data de emissão
   - Código de verificação único
4. Opções disponíveis:
   - **Reemitir**: gerar novamente o certificado
   - **Revogar**: invalidar um certificado específico
   - **Exportar**: baixar a lista completa em formato CSV
5. Para verificação de autenticidade:
   - Configure a página de verificação externa
   - Os usuários podem verificar certificados inserindo o código

### Controle de Presença

#### Configurar Registro de Presença

1. Ative a edição do curso
2. Clique em "Adicionar uma atividade ou recurso"
3. Selecione "Presença"
4. Configure as opções básicas:
   - **Nome**: título do registro de presença
   - **Descrição**: informações sobre a atividade
   - **Nota**: pontuação máxima para presença
5. Clique em "Salvar e exibir" para criar o registro
6. Configure as sessões:
   - Clique na aba "Adicionar sessão"
   - Defina data, hora e duração
   - Adicione descrição (ex: "Aula 1 - Introdução")
   - Para sessões

      - **Fórum padrão para uso geral**: múltiplos tópicos e discussões, onde qualquer usuário pode iniciar uma nova discussão a qualquer momento
     - **Fórum perguntas e respostas**: os alunos não veem as respostas de outros alunos até que postem sua própria resposta à questão original
     - **Discussão simples**: consiste em um único tópico em uma página, útil para discussões curtas e focadas
     - **Fórum padrão exibido em formato blog**: similar ao padrão, mas mostra o primeiro post de cada discussão na página principal
     - **Cada pessoa inicia apenas uma discussão**: cada participante pode criar apenas um tópico de discussão (todos podem responder)
5. Configure as anexos e contagem de palavras:
   - **Tamanho máximo do anexo**: limite de upload
   - **Número máximo de anexos**: quantidade permitida
   - **Mostrar contagem de palavras**: exibe quantas palavras o post contém
6. Configure as assinaturas e acompanhamento:
   - **Modo de assinatura**: como os usuários são inscritos (opcional, forçada, etc.)
   - **Rastreamento de leitura**: destaca posts não lidos
7. Configure a moderação:
   - **Período para bloquear**: quando as discussões são encerradas
   - **Limite de mensagens para bloqueio**: número máximo de posts
   - **Tempo para bloquear**: após quanto tempo os posts são bloqueados
8. Configure as notas:
   - **Avaliações**: se os posts podem ser avaliados
   - **Função para avaliar**: quem pode avaliar (professor, todos)
   - **Método de avaliação**: escala numérica, rubrica, etc.
9. Salve as configurações

#### Fórum de Notícias e Avisos

1. Por padrão, cada curso tem um "Fórum de notícias" para comunicados importantes
2. Características especiais:
   - Todos os participantes são automaticamente inscritos
   - Apenas professores e administradores podem criar tópicos
   - Os posts são enviados automaticamente por e-mail
3. Para configurar este fórum:
   - Clique no fórum de notícias
   - Acesse o ícone de engrenagem e selecione "Editar configurações"
   - Ajuste as opções conforme necessário
4. Dicas de uso:
   - Use apenas para anúncios importantes
   - Seja claro e conciso nos títulos
   - Considere agrupar anúncios relacionados em um único post

### Moderação e Acompanhamento

#### Gerenciar Discussões

1. Acesse o fórum que deseja moderar
2. Como moderador, você tem opções adicionais:
   - **Fixar discussões**: torna tópicos importantes visíveis no topo
   - **Mover discussões**: transfere para outro fórum
   - **Excluir discussões**: remove tópicos inadequados
   - **Dividir discussões**: separa respostas em um novo tópico
3. Para acessar estas funções:
   - Clique no ícone de engrenagem ao lado do tópico
   - Selecione a ação desejada

#### Moderar Posts Individuais

1. Para moderar posts específicos:
   - Clique no ícone de engrenagem ao lado do post
   - Opções disponíveis:
     - **Editar**: modificar o conteúdo do post
     - **Excluir**: remover o post
     - **Destacar**: dar destaque visual
     - **Mover**: transferir para outra discussão
2. Para moderação em massa:
   - No fórum, selecione "Mostrar/editar posts atuais"
   - Selecione os posts usando as caixas de seleção
   - Use o menu "Com os posts selecionados..." para aplicar ações em grupo

#### Monitorar Atividade e Participação

1. Configure alertas de notificação:
   - No fórum, clique em "Assinatura"
   - Escolha "Envie-me notificações de novas postagens neste fórum"
2. Visualize estatísticas de participação:
   - No bloco de administração, clique em "Relatórios" → "Participação"
   - Selecione o fórum específico na lista de atividades
   - Configure para mostrar "Postagens" como ação
   - Clique em "Ir" para gerar o relatório
3. Identifique alunos menos participativos:
   - Ordene o relatório por número de postagens
   - Entre em contato com alunos que não estão participando

#### Avaliação de Fóruns

1. Configure a avaliação nas configurações do fórum
2. Para avaliar posts:
   - Acesse o fórum e visualize as discussões
   - Ao lado de cada post, verá o link "Avaliar"
   - Clique e atribua uma nota conforme o método escolhido
   - Adicione feedback quando aplicável
3. Visualização consolidada:
   - No fórum, clique em "Visualizar avaliações"
   - Veja todas as avaliações em uma tabela única
   - Faça ajustes conforme necessário

## Recursos Didáticos Interativos

### Inserção e Gerenciamento de Mídias

#### Adicionar Vídeos

1. **Vídeos do YouTube, Vimeo ou outras plataformas**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "URL" ou "Página"
   - Para URL: cole o link do vídeo
   - Para Página: use o editor HTML e clique no botão "Inserir mídia"
   - Cole o URL do vídeo e configure opções de exibição
   - Salve as alterações

2. **Upload direto de vídeos**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Arquivo"
   - Arraste o arquivo de vídeo ou use o seletor de arquivos
   - Configure as opções de exibição
   - **Importante**: verifique o limite de tamanho de arquivo do seu Moodle (geralmente 50-100MB)
   - Para vídeos maiores, considere compressão ou hospedagem externa

3. **Incorporação de playlist ou canal completo**:
   - Crie uma página HTML
   - No editor, clique no botão HTML
   - Cole o código de incorporação fornecido pela plataforma
   - Ajuste largura e altura conforme necessário
   - Salve as alterações

#### Adicionar Áudios

1. **Arquivos de áudio**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Arquivo"
   - Faça upload do arquivo de áudio (MP3, WAV, OGG)
   - Configure para exibir o player de áudio
   - Salve as alterações

2. **Coleção de áudios**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Pasta"
   - Faça upload de múltiplos arquivos de áudio
   - Configure a visualização (lista de arquivos ou incorporada)
   - Salve as alterações

#### Adicionar Documentos PDF

1. **Upload simples**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Arquivo"
   - Faça upload do PDF
   - Configure opções de exibição:
     - **Forçar download**: aluno deve baixar o arquivo
     - **Abrir**: exibe o PDF no navegador
     - **Em uma janela pop-up**: abre em nova janela
   - Salve as alterações

2. **Biblioteca de documentos**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Pasta"
   - Faça upload de múltiplos PDFs
   - Organize os arquivos em subpastas, se necessário
   - Defina opções de exibição
   - Salve as alterações

#### Gerenciar Arquivos SCORM

1. **O que é SCORM**:
   - Pacote de conteúdo interativo padronizado
   - Permite rastreamento de progresso e interação
   - Frequentemente criado em ferramentas de autoria externas

2. **Adicionar um pacote SCORM**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Pacote SCORM"
   - Na seção "Pacote", faça upload do arquivo .zip SCORM
   - Configure as opções:
     - **Método de exibição**: janela atual, nova janela, etc.
     - **Largura e altura**: dimensões do player
     - **Opções de reprodução**: permitir avançar, retornar, etc.
   - Configure as opções de avaliação:
     - **Método de avaliação**: melhor tentativa, média, primeira, etc.
     - **Número máximo de tentativas**
     - **Status de conclusão**: baseado em nota, visualização, etc.
   - Salve as alterações

#### Adicionar Links Externos

1. **Adicionar um link**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "URL"
   - Digite ou cole o endereço web
   - Configure as opções de exibição:
     - **Exibir**: na página atual ou nova janela
     - **Nome do parâmetro URL**: para passar variáveis ao site externo
   - Salve as alterações

2. **Incorporar conteúdo externo com iframe**:
   - Crie uma página HTML
   - No editor, clique no botão HTML
   - Adicione código de iframe:
     ```html
     <iframe src="https://site-externo.com" width="100%" height="600px"></iframe>
     ```
   - Salve as alterações

#### Gerenciar Biblioteca de Mídias

1. **Acessar o repositório de arquivos**:
   - No bloco de administração, clique em "Arquivos"
   - Ou ao adicionar um arquivo, use o seletor de arquivos
   - Clique em "Repositório de servidor"

2. **Organizar arquivos**:
   - Crie pastas para categorias específicas (Vídeos, Áudios, Documentos)
   - Use convenção de nomenclatura consistente
   - Adicione descritores nos nomes dos arquivos (data, versão, etc.)

3. **Verificar uso de espaço**:
   - No painel de administração do site, acesse "Plugins" → "Repositórios" → "Gerenciar repositórios"
   - Verifique o espaço utilizado e limites
   - Considere limpar arquivos não utilizados regularmente

### Atividades Interativas Adicionais

#### Criar um Glossário

1. **Configuração básica**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Glossário"
   - Configure as opções básicas:
     - **Nome**: título da atividade
     - **Descrição**: propósito e instruções
     - **Tipo de glossário**: principal (um por curso) ou secundário (múltiplos)

2. **Opções de entrada**:
   - **Aprovação de entradas**: moderação necessária ou não
   - **Sempre permitir edição**: se alunos podem editar suas entradas
   - **Permitir entradas duplicadas**: mesmos termos por pessoas diferentes
   - **Permitir comentários**: habilitar discussão nas entradas
   - **Link automático**: criar links automáticos dos termos no curso

3. **Opções de exibição**:
   - **Formato de exibição**: como os termos serão mostrados (dicionário, enciclopédia, etc.)
   - **Itens por página**: quantos termos mostrar por vez
   - **Mostrar alfabeto**: links para navegar por letra inicial
   - **Mostrar link "TODOS"**: opção para ver todos os termos de uma vez
   - **Mostrar link "Especial"**: para termos que começam com símbolos ou números

4. **Opções de avaliação** (se desejado):
   - **Permitir avaliação de entradas**: sim/não
   - **Usuários**: quem pode avaliar (todos ou apenas professores)
   - **Escala**: tipo de avaliação (numérica ou personalizada)

5. **Adicionar termos ao glossário**:
   - Dentro do glossário, clique em "Adicionar novo item"
   - Preencha o termo e sua definição
   - Adicione palavras-chave (sinônimos que também serão vinculados)
   - Opcionalmente, adicione arquivos anexos (imagens, áudios, etc.)
   - Salve as alterações

6. **Gerenciar e moderar entradas**:
   - Para aprovar entradas pendentes: clique na aba "Aprovar"
   - Para editar: clique no ícone de lápis ao lado do termo
   - Para excluir: clique no ícone X
   - Para exportar: use a opção "Exportar entradas" para backup ou transferência

#### Criar um Wiki

1. **Configuração básica**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Wiki"
   - Configure as opções básicas:
     - **Nome**: título do wiki
     - **Descrição**: propósito e instruções
     - **Nome da primeira página**: título da página inicial

2. **Modo e configurações**:
   - **Modo wiki**: individual (cada aluno tem seu próprio) ou colaborativo (um para todos)
   - **Nome da primeira página**: título da página inicial
   - **Formato padrão**: HTML, Creole, NWiki ou texto simples
   - **Forçar formato**: se os usuários podem escolher outro formato

3. **Configurações comuns**:
   - Visibilidade, número ID, agrupamento, etc.
   - Defina restrições de acesso, se necessário
   - Configure acompanhamento de conclusão

4. **Criar a primeira página**:
   - Após salvar, você será direcionado para criar a primeira página
   - Use o editor para adicionar conteúdo
   - Crie links para outras páginas usando [[Nome da Página]]
   - Salve as alterações

5. **Gerenciar o wiki**:
   - **Visualizar**: conteúdo atual
   - **Editar**: modificar conteúdo
   - **Comentários**: discussão sobre a página
   - **Histórico**: versões anteriores
   - **Mapa**: visualização da estrutura do wiki
   - **Arquivos**: gerenciar anexos
   - **Administração**: configurações e permissões

#### Criar uma Enquete

1. **Configuração básica**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Escolha" (para enquetes simples) ou "Pesquisa" (para enquetes complexas)
   - Configure as opções básicas:
     - **Nome**: título da enquete
     - **Descrição**: propósito e instruções

2. **Para a atividade "Escolha" (enquete simples)**:
   - Adicione as opções de resposta
   - Configure limites:
     - **Permitir atualização da escolha**: se os alunos podem mudar de opinião
     - **Permitir mais de uma escolha**: seleção múltipla
     - **Limitar número de respostas**: número máximo por opção
   - Configure exibição:
     - **Mostrar resultados**: quando os alunos podem ver os resultados
     - **Privacidade dos resultados**: anônimo ou com nomes
     - **Mostrar coluna de não respondentes**: exibir quem ainda não participou

3. **Para a atividade "Pesquisa" (enquete avançada)**:
   - Após criar, clique em "Editar perguntas"
   - Adicione diferentes tipos de questões:
     - **Múltipla escolha**: uma ou várias respostas
     - **Resposta de texto**: curta ou longa
     - **Numérica**: resposta em números
     - **Escala Likert**: nível de concordância
     - **Data**: seleção de data
   - Organize as questões em páginas
   - Configure quando mostrar os resultados
   - Configure anonimato das respostas

4. **Analisar resultados**:
   - Acesse a atividade e clique na aba "Respostas" ou "Análise"
   - Visualize estatísticas e gráficos
   - Exporte dados para análise externa (Excel, SPSS, etc.)

## Personalização da Plataforma

### Adaptação da Identidade Visual

#### Configurar o Tema Boost Magnific

1. **Acessar configurações do tema**:
   - No painel de administração, acesse "Aparência" → "Temas" → "Boost Magnific"
   - Clique em "Configurações" para acessar as opções de personalização

2. **Personalizar logotipos e ícones**:
   - **Logo do site**: imagem principal exibida no cabeçalho (tamanho recomendado: 200x50px)
   - **Favicon**: ícone exibido na aba do navegador (tamanho recomendado: 32x32px)
   - **Ícones de curso padrão**: imagem exibida para cursos sem imagem específica

3. **Configurar cores e estilos**:
   - **Cor primária**: cor principal do tema (botões, links, etc.)
   - **Cor secundária**: cor complementar para elementos adicionais
   - **Cor de destaque**: para elementos que precisam de atenção
   - **Cor de fundo**: para o site inteiro ou seções específicas
   - **CSS personalizado**: para personalização avançada

4. **Configurar layout e navegação**:
   - **Largura do conteúdo**: fixa ou fluida (responsiva)
   - **Posição do menu**: esquerda, direita ou oculto
   - **Layout da página inicial**: grade de cursos, carrossel, etc.
   - **Elementos de cabeçalho e rodapé**: links, informações de contato, etc.

5. **Personalizar página de login**:
   - **Imagem de fundo**: para a tela de login
   - **Mensagem de boas-vindas**: texto exibido na página de login
   - **Vídeo de fundo**: URL de vídeo para reprodução na tela de login
   - **Layout do formulário de login**: posição e estilo

#### Personalizar Blocos e Páginas

1. **Configurar blocos na página inicial**:
   - No painel de administração, acesse "Página inicial" → "Ativar edição"
   - Adicione, remova ou reorganize blocos arrastando-os
   - Configure cada bloco clicando no ícone de engrenagem
   - Blocos úteis para a página inicial:
     - **Calendário**: exibe eventos próximos
     - **Cursos em destaque**: mostra cursos selecionados
     - **HTML personalizado**: para anúncios ou boas-vindas
     - **Usuários online**: mostra quem está conectado

2. **Personalizar painel do usuário**:
   - No painel de administração, acesse "Aparência" → "Painel padrão"
   - Configure quais blocos aparecem por padrão no painel dos usuários
   - Defina layout e posições dos blocos
   - Blocos recomendados para o painel:
     - **Visão geral do curso**: lista de cursos do usuário
     - **Cronograma**: atividades com prazo próximo
     - **Mensagens**: comunicações recentes
     - **Arquivos privados**: acesso rápido aos arquivos

3. **Criar páginas personalizadas**:
   - No painel de administração, acesse "Configurações da página inicial" → "Página inicial padrão"
   - Selecione "Site home/Dashboard" para criar uma página personalizada
   - Ou use o recurso "Página" para criar páginas estáticas em qualquer lugar
   - Use HTML e CSS para design avançado
   - Incorpore elementos como:
     - Vídeo institucional
     - Carrossel de banners
     - Links rápidos para recursos importantes
     - Contagem regressiva para eventos

### Criação de Diferentes Perfis

#### Gerenciar Perfis de Usuário

1. **Entender os perfis padrão**:
   - **Administrador**: acesso completo a todas as funções
   - **Gerente**: gerencia cursos e usuários, mas não altera configurações do sistema
   - **Criador de curso**: pode criar novos cursos
   - **Professor**: gerencia conteúdo dentro de seus cursos
   - **Professor não-editor**: pode ensinar e avaliar, mas não editar conteúdo
   - **Aluno**: participa de cursos e atividades
   - **Visitante**: acesso limitado para visualização

2. **Criar perfis personalizados**:
   - No painel de administração, acesse "Usuários" → "Permissões" → "Definir funções"
   - Clique em "Adicionar um novo papel"
   - Ou duplique um papel existente como base
   - Configure:
     - **Nome curto**: identificador único (sem espaços)
     - **Nome personalizado**: nome exibido na interface
     - **Descrição**: explique o propósito do papel
     - **Tipo de papel**: contexto onde será aplicado (sistema, categoria, curso, etc.)

3. **Configurar permissões detalhadas**:
   - Na página de edição de papel, configure cada capacidade:
     - **Permitir**: concede a permissão
     - **Impedir**: nega a permissão, mas pode ser sobrescrita
     - **Proibir**: nega a permissão e não pode ser sobrescrita
   - Organize-se usando a visualização por categorias
   - Busque permissões específicas usando a caixa de pesquisa
   - Exemplos de capacidades importantes:
     - **moodle/course:create**: criar cursos
     - **moodle/course:update**: editar configurações do curso
     - **moodle/course:manageactivities**: adicionar/remover atividades
     - **moodle/user:create**: criar usuários
     - **moodle/site:config**: alterar configurações do site

4. **Exemplos de perfis personalizados**:
   - **Coordenador Departamental**:
     - Baseado no papel de Gerente
     - Restrito a uma categoria específica
     - Permissão para criar cursos e inscrever usuários
     - Acesso a relatórios de progresso
   - **Tutor**:
     - Baseado no papel de Professor não-editor
     - Permissão adicional para enviar mensagens em massa
     - Acesso a relatórios de atividade
     - Sem permissão para editar conteúdo
   - **Monitor**:
     - Baseado no papel de Aluno
     - Permissão adicional para moderar fóruns
     - Permissão para ver atividades ocultas
     - Sem permissão para alterar conteúdo

5. **Atribuir papéis personalizados**:
   - **Nível de sistema**: "Usuários" → "Permissões" → "Atribuir funções globais"
   - **Nível de categoria**: na página da categoria, "Atribuir funções"
   - **Nível de curso**: no curso, "Participantes" → "Inscrever usuários"

#### Configurar Campos de Perfil Personalizados

1. **Acessar configurações de perfil**:
   - No painel de administração, acesse "Usuários" → "Contas" → "Campos de perfil do usuário"

2. **Adicionar novos campos**:
   - Clique em "Criar um novo campo de perfil"
   - Selecione o tipo:
     - **Caixa de texto**: texto curto
     - **Área de texto**: texto longo
     - **Menu de opções**: lista suspensa
     - **Checkbox**: sim/não
     - **Data**: seletor de data
     - **Menu de opções**: seleção única
   - Configure as opções:
     - **Nome curto**: identificador (sem espaços)
     - **Nome**: título exibido
     - **Descrição**: explicação do campo
     - **Campo obrigatório**: sim/não
     - **Visível para**: quem pode ver este campo
     - **Categoria**: agrupamento do campo

3. **Exemplos de campos personalizados**:
   - **Departamento/Setor**: menu de opções com setores da empresa
   - **Cargo/Função**: texto ou menu de opções
   - **Data de Contratação**: campo de data
   - **Competências**: área de texto para listar habilidades
   - **Gestor Direto**: texto para nome do supervisor

4. **Organizar campos em categorias**:
   - Clique em "Criar uma nova categoria"
   - Configure:
     - **Nome**: título da categoria
     - **Ordem**: posição na página de perfil
   - Atribua campos existentes à nova categoria
   - Exemplos de categorias:
     - **Informações Profissionais**
     - **Contato**
     - **Interesses e Expertise**

## Automação de Processos

### Automatização de Mensagens

#### Configurar Mensagens Automáticas

1. **Acessar configurações de notificação**:
   - No painel de administração, acesse "Mensagens" → "Notificações"
   - Ou "Plugins" → "Mensagens" → "Gerenciar mensagens"

2. **Configurar notificações do sistema**:
   - Selecione o tipo de notificação para configurar
   - Para cada tipo, defina:
     - **Métodos de envio**: pop-up, e-mail, móvel, etc.
     - **Permissões**: quem pode enviar este tipo de mensagem
     - **Formato**: HTML ou texto simples
     - **Habilitar/desabilitar**: ativar ou desativar completamente

3. **Tipos de mensagens automáticas padrão**:
   - **Confirmação de inscrição**: quando um usuário é inscrito em um curso
   - **Confirmação de cadastro**: quando uma conta é criada
   - **Alertas de prazo**: quando uma atividade está prestes a vencer
   - **Feedback recebido**: quando um professor avalia um trabalho
   - **Postagem em fórum**: quando há nova atividade em fóruns assinados
   - **Mensagens diretas**: comunicações entre usuários

#### Personalizar Modelos de E-mail

1. **Acessar modelos de e-mail**:
   - No painel de administração, acesse "Idioma" → "Personalização de idioma"
   - Selecione o pacote de idioma (ex: Português - Brasil)
   - Busque o componente "message" ou o tipo específico de e-mail

2. **Editar modelos**:
   - Selecione o arquivo de string que contém o modelo
   - Edite o texto, mantendo as variáveis do sistema (ex: {$a->coursename})
   - Use HTML para formatação avançada
   - Variáveis comuns:
     - **{$a->firstname}**: primeiro nome do destinatário
     - **{$a->lastname}**: sobrenome do destinatário
     - **{$a->sitename}**: nome da plataforma
     - **{$a->coursename}**: nome do curso
     - **{$a->link}**: link relevante para a ação

3. **Exemplo de personalização - Boas-vindas ao curso**:
   ```html
   <h2>Bem-vindo(a) ao curso {$a->coursename}!</h2>
   
   <p>Olá {$a->firstname},</p>
   
   <p>Você foi inscrito(a) com sucesso no curso <strong>{$a->coursename}</strong>.</p>
   
   <p>Para começar, acesse o curso através do link: <a href="{$a->link}">{$a->coursename}</a></p>
   
   <p>Se você tiver dúvidas, entre em contato com seu instrutor ou com o suporte.</p>
   
   <p>Atenciosamente,<br>
   Equipe de Treinamento<br>
   {$a->sitename}</p>
   ```

#### Configurar Alertas e Lembretes

1. **Alertas baseados em eventos**:
   - Configure notificações para eventos específicos:
     - Conclusão de atividade
     - Inscrição/desinscrição
     - Novas postagens em fóruns
   - No painel de administração, acesse "Usuários" → "Permissões" → "Capacidades do usuário"
   - Configure quem pode receber e gerenciar alertas

2. **Lembretes de prazos**:
   - Acesse "Site administration" → "Plugins" → "Message outputs" → "Email"
   - Configure a frequência dos e-mails de lembrete
   - Defina com que antecedência os lembretes devem ser enviados
   - Ative o envio de cópia para professores/gestores

3. **Mensagens automáticas para usuários inativos**:
   - Requer plugin adicional ou configuração personalizada
   - Configure gatilhos baseados em tempo desde o último acesso
   - Defina mensagens progressivas (gentil, informativa, urgente)

### Automatização de Processos de Curso

#### Configurar Conclusão Automática

1. **Configurar critérios de conclusão de curso**:
   - Acesse as configurações do curso
   - Vá para a seção "Conclusão do curso"
   - Selecione "Conclusão automática mediante critérios"
   - Defina os critérios:
     - **Atividades concluídas**: todas ou algumas atividades específicas
     - **Data**: conclusão em uma data específica
     - **Duração**: após período desde a inscrição
     - **Nota**: obtenção de nota     - **Fórum padrão para uso geral**: múltiplos tópicos e discussões, onde qualquer usuário pode iniciar uma nova discussão a qualquer momento
     - **Fórum perguntas e respostas**: os alunos não veem as respostas de outros alunos até que postem sua própria resposta à questão original
     - **Discussão simples**: consiste em um único tópico em uma página, útil para discussões curtas e focadas
     - **Fórum padrão exibido em formato blog**: similar ao padrão, mas mostra o primeiro post de cada discussão na página principal
     - **Cada pessoa inicia apenas uma discussão**: cada participante pode criar apenas um tópico de discussão (todos podem responder)
5. Configure as anexos e contagem de palavras:
   - **Tamanho máximo do anexo**: limite de upload
   - **Número máximo de anexos**: quantidade permitida
   - **Mostrar contagem de palavras**: exibe quantas palavras o post contém
6. Configure as assinaturas e acompanhamento:
   - **Modo de assinatura**: como os usuários são inscritos (opcional, forçada, etc.)
   - **Rastreamento de leitura**: destaca posts não lidos
7. Configure a moderação:
   - **Período para bloquear**: quando as discussões são encerradas
   - **Limite de mensagens para bloqueio**: número máximo de posts
   - **Tempo para bloquear**: após quanto tempo os posts são bloqueados
8. Configure as notas:
   - **Avaliações**: se os posts podem ser avaliados
   - **Função para avaliar**: quem pode avaliar (professor, todos)
   - **Método de avaliação**: escala numérica, rubrica, etc.
9. Salve as configurações

#### Fórum de Notícias e Avisos

1. Por padrão, cada curso tem um "Fórum de notícias" para comunicados importantes
2. Características especiais:
   - Todos os participantes são automaticamente inscritos
   - Apenas professores e administradores podem criar tópicos
   - Os posts são enviados automaticamente por e-mail
3. Para configurar este fórum:
   - Clique no fórum de notícias
   - Acesse o ícone de engrenagem e selecione "Editar configurações"
   - Ajuste as opções conforme necessário
4. Dicas de uso:
   - Use apenas para anúncios importantes
   - Seja claro e conciso nos títulos
   - Considere agrupar anúncios relacionados em um único post

### Moderação e Acompanhamento

#### Gerenciar Discussões

1. Acesse o fórum que deseja moderar
2. Como moderador, você tem opções adicionais:
   - **Fixar discussões**: torna tópicos importantes visíveis no topo
   - **Mover discussões**: transfere para outro fórum
   - **Excluir discussões**: remove tópicos inadequados
   - **Dividir discussões**: separa respostas em um novo tópico
3. Para acessar estas funções:
   - Clique no ícone de engrenagem ao lado do tópico
   - Selecione a ação desejada

#### Moderar Posts Individuais

1. Para moderar posts específicos:
   - Clique no ícone de engrenagem ao lado do post
   - Opções disponíveis:
     - **Editar**: modificar o conteúdo do post
     - **Excluir**: remover o post
     - **Destacar**: dar destaque visual
     - **Mover**: transferir para outra discussão
2. Para moderação em massa:
   - No fórum, selecione "Mostrar/editar posts atuais"
   - Selecione os posts usando as caixas de seleção
   - Use o menu "Com os posts selecionados..." para aplicar ações em grupo

#### Monitorar Atividade e Participação

1. Configure alertas de notificação:
   - No fórum, clique em "Assinatura"
   - Escolha "Envie-me notificações de novas postagens neste fórum"
2. Visualize estatísticas de participação:
   - No bloco de administração, clique em "Relatórios" → "Participação"
   - Selecione o fórum específico na lista de atividades
   - Configure para mostrar "Postagens" como ação
   - Clique em "Ir" para gerar o relatório
3. Identifique alunos menos participativos:
   - Ordene o relatório por número de postagens
   - Entre em contato com alunos que não estão participando

#### Avaliação de Fóruns

1. Configure a avaliação nas configurações do fórum
2. Para avaliar posts:
   - Acesse o fórum e visualize as discussões
   - Ao lado de cada post, verá o link "Avaliar"
   - Clique e atribua uma nota conforme o método escolhido
   - Adicione feedback quando aplicável
3. Visualização consolidada:
   - No fórum, clique em "Visualizar avaliações"
   - Veja todas as avaliações em uma tabela única
   - Faça ajustes conforme necessário

## Recursos Didáticos Interativos

### Inserção e Gerenciamento de Mídias

#### Adicionar Vídeos

1. **Vídeos do YouTube, Vimeo ou outras plataformas**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "URL" ou "Página"
   - Para URL: cole o link do vídeo
   - Para Página: use o editor HTML e cl#### Configurar Registro de Presença

1. Ative a edição do curso
2. Clique em "Adicionar uma atividade ou recurso"
3. Selecione "Presença"
4. Configure as opções básicas:
   - **Nome**: título do registro de presença
   - **Descrição**: informações sobre a atividade
   - **Nota**: pontuação máxima para presença
5. Clique em "Salvar e exibir" para criar o registro
6. Configure as sessões:
   - Clique na aba "Adicionar sessão"
   - Defina data, hora e duração
   - Adicione descrição (ex: "Aula 1 - Introdução")
   - Para sessões recorrentes, use "Adicionar múltiplas sessões"
7. Configure status de presença:
   - Clique na aba "Configurações"
   - Defina os possíveis status (Presente, Atrasado, Ausente, Justificado)
   - Atribua pontos para cada status (ex: Presente = 2, Atrasado = 1, Ausente = 0)

#### Registrar Presenças

1. Acesse a atividade de presença no curso
2. Clique na aba "Registrar"
3. Selecione a sessão específica
4. Para cada aluno, selecione o status apropriado
5. Adicione comentários quando necessário
6. Clique em "Salvar presenças" quando terminar

#### Relatórios de Presença

1. Acesse a atividade de presença no curso
2. Clique na aba "Relatório"
3. Visualize dados consolidados:
   - Resumo por aluno (porcentagem de comparecimento)
   - Detalhamento por sessão
   - Estatísticas globais da turma
4. Filtre por:
   - Grupo
   - Status específico
   - Período de datas
5. Exporte os dados em diferentes formatos:
   - Excel
   - CSV
   - PDF

## Fóruns e Espaços de Discussão

### Tipos de Fóruns e Configuração

#### Criar um Fórum

1. Ative a edição do curso
2. Clique em "Adicionar uma atividade ou recurso"
3. Selecione "Fórum"
4. Configure as opções básicas:
   - **Nome do fórum**: título da atividade
   - **Descrição**: instruções e propósito do fórum
   - **Tipo de fórum**:
     - **Fórum padrão para uso geral**: múltiplos tópicos e discussões, onde qualquer usuário pode iniciar uma nova discussão a qualquer momento
     - **Fórum perguntas e respostas**: os alunos não veem as respostas de outros alunos até que postem sua própria resposta à questão original
     - **Discussão simples**: consiste em um único tópico em uma página, útil para discussões curtas e focadas
     - **Fórum padrão exibido em formato blog**: similar ao padrão, mas mostra o primeiro post de cada discussão na página principal
     - **Cada pessoa inicia apenas uma discussão**: cada participante pode criar apenas um tópico de discussão (todos podem responder)# Manual Detalhado do Moderador/Administrador
5. Configure as anexos e contagem de palavras:
   - **Tamanho máximo do anexo**: limite de upload
   - **Número máximo de anexos**: quantidade permitida
   - **Mostrar contagem de palavras**: exibe quantas palavras o post contém
6. Configure as assinaturas e acompanhamento:
   - **Modo de assinatura**: como os usuários são inscritos (opcional, forçada, etc.)
   - **Rastreamento de leitura**: destaca posts não lidos
7. Configure a moderação:
   - **Período para bloquear**: quando as discussões são encerradas
   - **Limite de mensagens para bloqueio**: número máximo de posts
   - **Tempo para bloquear**: após quanto tempo os posts são bloqueados
8. Configure as notas:
   - **Avaliações**: se os posts podem ser avaliados
   - **Função para avaliar**: quem pode avaliar (professor, todos)
   - **Método de avaliação**: escala numérica, rubrica, etc.
9. Salve as configurações

#### Fórum de Notícias e Avisos

1. Por padrão, cada curso tem um "Fórum de notícias" para comunicados importantes
2. Características especiais:
   - Todos os participantes são automaticamente inscritos
   - Apenas professores e administradores podem criar tópicos
   - Os posts são enviados automaticamente por e-mail
3. Para configurar este fórum:
   - Clique no fórum de notícias
   - Acesse o ícone de engrenagem e selecione "Editar configurações"
   - Ajuste as opções conforme necessário
4. Dicas de uso:
   - Use apenas para anúncios importantes
   - Seja claro e conciso nos títulos
   - Considere agrupar anúncios relacionados em um único post

### Moderação e Acompanhamento

#### Gerenciar Discussões

1. Acesse o fórum que deseja moderar
2. Como moderador, você tem opções adicionais:
   - **Fixar discussões**: torna tópicos importantes visíveis no topo
   - **Mover discussões**: transfere para outro fórum
   - **Excluir discussões**: remove tópicos inadequados
   - **Dividir discussões**: separa respostas em um novo tópico
3. Para acessar estas funções:
   - Clique no ícone de engrenagem ao lado do tópico
   - Selecione a ação desejada

#### Moderar Posts Individuais

1. Para moderar posts específicos:
   - Clique no ícone de engrenagem ao lado do post
   - Opções disponíveis:
     - **Editar**: modificar o conteúdo do post
     - **Excluir**: remover o post
     - **Destacar**: dar destaque visual
     - **Mover**: transferir para outra discussão
2. Para moderação em massa:
   - No fórum, selecione "Mostrar/editar posts atuais"
   - Selecione os posts usando as caixas de seleção
   - Use o menu "Com os posts selecionados..." para aplicar ações em grupo

#### Monitorar Atividade e Participação

1. Configure alertas de notificação:
   - No fórum, clique em "Assinatura"
   - Escolha "Envie-me notificações de novas postagens neste fórum"
2. Visualize estatísticas de participação:
   - No bloco de administração, clique em "Relatórios" → "Participação"
   - Selecione o fórum específico na lista de atividades
   - Configure para mostrar "Postagens" como ação
   - Clique em "Ir" para gerar o relatório
3. Identifique alunos menos participativos:
   - Ordene o relatório por número de postagens
   - Entre em contato com alunos que não estão participando

#### Avaliação de Fóruns

1. Configure a avaliação nas configurações do fórum
2. Para avaliar posts:
   - Acesse o fórum e visualize as discussões
   - Ao lado de cada post, verá o link "Avaliar"
   - Clique e atribua uma nota conforme o método escolhido
   - Adicione feedback quando aplicável
3. Visualização consolidada:
   - No fórum, clique em "Visualizar avaliações"
   - Veja todas as avaliações em uma tabela única
   - Faça ajustes conforme necessário

## Recursos Didáticos Interativos

### Inserção e Gerenciamento de Mídias

#### Adicionar Vídeos

1. **Vídeos do YouTube, Vimeo ou outras plataformas**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "URL" ou "Página"
   - Para URL: cole o link do vídeo
   - Para Página: use o editor HTML e clique no botão "Inserir mídia"
   - Cole o URL do vídeo e configure opções de exibição
   - Salve as alterações

2. **Upload direto de vídeos**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Arquivo"
   - Arraste o arquivo de vídeo ou use o seletor de arquivos
   - Configure as opções de exibição
   - **Importante**: verifique o limite de tamanho de arquivo do seu Moodle (geralmente 50-100MB)
   - Para vídeos maiores, considere compressão ou hospedagem externa

3. **Incorporação de playlist ou canal completo**:
   - Crie uma página HTML
   - No editor, clique no botão HTML
   - Cole o código de incorporação fornecido pela plataforma
   - Ajuste largura e altura conforme necessário
   - Salve as alterações

#### Adicionar Áudios

1. **Arquivos de áudio**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Arquivo"
   - Faça upload do arquivo de áudio (MP3, WAV, OGG)
   - Configure para exibir o player de áudio
   - Salve as alterações

2. **Coleção de áudios**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Pasta"
   - Faça upload de múltiplos arquivos de áudio
   - Configure a visualização (lista de arquivos ou incorporada)
   - Salve as alterações

#### Adicionar Documentos PDF

1. **Upload simples**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Arquivo"
   - Faça upload do PDF
   - Configure opções de exibição:
     - **Forçar download**: aluno deve baixar o arquivo
     - **Abrir**: exibe o PDF no navegador
     - **Em uma janela pop-up**: abre em nova janela
   - Salve as alterações

2. **Biblioteca de documentos**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Pasta"
   - Faça upload de múltiplos PDFs
   - Organize os arquivos em subpastas, se necessário
   - Defina opções de exibição
   - Salve as alterações

#### Gerenciar Arquivos SCORM

1. **O que é SCORM**:
   - Pacote de conteúdo interativo padronizado
   - Permite rastreamento de progresso e interação
   - Frequentemente criado em ferramentas de autoria externas

2. **Adicionar um pacote SCORM**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Pacote SCORM"
   - Na seção "Pacote", faça upload do arquivo .zip SCORM
   - Configure as opções:
     - **Método de exibição**: janela atual, nova janela, etc.
     - **Largura e altura**: dimensões do player
     - **Opções de reprodução**: permitir avançar, retornar, etc.
   - Configure as opções de avaliação:
     - **Método de avaliação**: melhor tentativa, média, primeira, etc.
     - **Número máximo de tentativas**
     - **Status de conclusão**: baseado em nota, visualização, etc.
   - Salve as alterações

#### Adicionar Links Externos

1. **Adicionar um link**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "URL"
   - Digite ou cole o endereço web
   - Configure as opções de exibição:
     - **Exibir**: na página atual ou nova janela
     - **Nome do parâmetro URL**: para passar variáveis ao site externo
   - Salve as alterações

2. **Incorporar conteúdo externo com iframe**:
   - Crie uma página HTML
   - No editor, clique no botão HTML
   - Adicione código de iframe:
     ```html
     <iframe src="https://site-externo.com" width="100%" height="600px"></iframe>
     ```
   - Salve as alterações

#### Gerenciar Biblioteca de Mídias

1. **Acessar o repositório de arquivos**:
   - No bloco de administração, clique em "Arquivos"
   - Ou ao adicionar um arquivo, use o seletor de arquivos
   - Clique em "Repositório de servidor"

2. **Organizar arquivos**:
   - Crie pastas para categorias específicas (Vídeos, Áudios, Documentos)
   - Use convenção de nomenclatura consistente
   - Adicione descritores nos nomes dos arquivos (data, versão, etc.)

3. **Verificar uso de espaço**:
   - No painel de administração do site, acesse "Plugins" → "Repositórios" → "Gerenciar repositórios"
   - Verifique o espaço utilizado e limites
   - Considere limpar arquivos não utilizados regularmente

### Atividades Interativas Adicionais

#### Criar um Glossário

1. **Configuração básica**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Glossário"
   - Configure as opções básicas:
     - **Nome**: título da atividade
     - **Descrição**: propósito e instruções
     - **Tipo de glossário**: principal (um por curso) ou secundário (múltiplos)

2. **Opções de entrada**:
   - **Aprovação de entradas**: moderação necessária ou não
   - **Sempre permitir edição**: se alunos podem editar suas entradas
   - **Permitir entradas duplicadas**: mesmos termos por pessoas diferentes
   - **Permitir comentários**: habilitar discussão nas entradas
   - **Link automático**: criar links automáticos dos termos no curso

3. **Opções de exibição**:
   - **Formato de exibição**: como os termos serão mostrados (dicionário, enciclopédia, etc.)
   - **Itens por página**: quantos termos mostrar por vez
   - **Mostrar alfabeto**: links para navegar por letra inicial
   - **Mostrar link "TODOS"**: opção para ver todos os termos de uma vez
   - **Mostrar link "Especial"**: para termos que começam com símbolos ou números

4. **Opções de avaliação** (se desejado):
   - **Permitir avaliação de entradas**: sim/não
   - **Usuários**: quem pode avaliar (todos ou apenas professores)
   - **Escala**: tipo de avaliação (numérica ou personalizada)

5. **Adicionar termos ao glossário**:
   - Dentro do glossário, clique em "Adicionar novo item"
   - Preencha o termo e sua definição
   - Adicione palavras-chave (sinônimos que também serão vinculados)
   - Opcionalmente, adicione arquivos anexos (imagens, áudios, etc.)
   - Salve as alterações

6. **Gerenciar e moderar entradas**:
   - Para aprovar entradas pendentes: clique na aba "Aprovar"
   - Para editar: clique no ícone de lápis ao lado do termo
   - Para excluir: clique no ícone X
   - Para exportar: use a opção "Exportar entradas" para backup ou transferência

#### Criar um Wiki

1. **Configuração básica**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Wiki"
   - Configure as opções básicas:
     - **Nome**: título do wiki
     - **Descrição**: propósito e instruções
     - **Nome da primeira página**: título da página inicial

2. **Modo e configurações**:
   - **Modo wiki**: individual (cada aluno tem seu próprio) ou colaborativo (um para todos)
   - **Nome da primeira página**: título da página inicial
   - **Formato padrão**: HTML, Creole, NWiki ou texto simples
   - **Forçar formato**: se os usuários podem escolher outro formato

3. **Configurações comuns**:
   - Visibilidade, número ID, agrupamento, etc.
   - Defina restrições de acesso, se necessário
   - Configure acompanhamento de conclusão

4. **Criar a primeira página**:
   - Após salvar, você será direcionado para criar a primeira página
   - Use o editor para adicionar conteúdo
   - Crie links para outras páginas usando [[Nome da Página]]
   - Salve as alterações

5. **Gerenciar o wiki**:
   - **Visualizar**: conteúdo atual
   - **Editar**: modificar conteúdo
   - **Comentários**: discussão sobre a página
   - **Histórico**: versões anteriores
   - **Mapa**: visualização da estrutura do wiki
   - **Arquivos**: gerenciar anexos
   - **Administração**: configurações e permissões

#### Criar uma Enquete

1. **Configuração básica**:
   - Ative a edição do curso
   - Clique em "Adicionar uma atividade ou recurso"
   - Selecione "Escolha" (para enquetes simples) ou "Pesquisa" (para enquetes complexas)
   - Configure as opções básicas:
     - **Nome**: título da enquete
     - **Descrição**: propósito e instruções

2. **Para a atividade "Escolha" (enquete simples)**:
   - Adicione as opções de resposta
   - Configure limites:
     - **Permitir atualização da escolha**: se os alunos podem mudar de opinião
     - **Permitir mais de uma escolha**: seleção múltipla
     - **Limitar número de respostas**: número máximo por opção
   - Configure exibição:
     - **Mostrar resultados**: quando os alunos podem ver os resultados
     - **Privacidade dos resultados**: anônimo ou com nomes
     - **Mostrar coluna de não respondentes**: exibir quem ainda não participou

3. **Para a atividade "Pesquisa" (enquete avançada)**:
   - Após criar, clique em "Editar perguntas"
   - Adicione diferentes tipos de questões:
     - **Múltipla escolha**: uma ou várias respostas
     - **Resposta de texto**: curta ou longa
     - **Numérica**: resposta em números
     - **Escala Likert**: nível de concordância
     - **Data**: seleção de data
   - Organize as questões em páginas
   - Configure quando mostrar os resultados
   - Configure anonimato das respostas

4. **Analisar resultados**:
   - Acesse a atividade e clique na aba "Respostas" ou "Análise"
   - Visualize estatísticas e gráficos
   - Exporte dados para análise externa (Excel, SPSS, etc.)
## Personalização da Plataforma

### Adaptação da Identidade Visual

#### Configurar o Tema Boost Magnific

1. **Acessar configurações do tema**:
   - No painel de administração, acesse "Aparência" → "Temas" → "Boost Magnific"
   - Clique em "Configurações" para acessar as opções de personalização

2. **Personalizar logotipos e ícones**:
   - **Logo do site**: imagem principal exibida no cabeçalho (tamanho recomendado: 200x50px)
   - **Favicon**: ícone exibido na aba do navegador (tamanho recomendado: 32x32px)
   - **Ícones de curso padrão**: imagem exibida para cursos sem imagem específica

3. **Configurar cores e estilos**:
   - **Cor primária**: cor principal do tema (botões, links, etc.)
   - **Cor secundária**: cor complementar para elementos adicionais
   - **Cor de destaque**: para elementos que precisam de atenção
   - **Cor de fundo**: para o site inteiro ou seções específicas
   - **CSS personalizado**: para personalização avançada

4. **Configurar layout e navegação**:
   - **Largura do conteúdo**: fixa ou fluida (responsiva)
   - **Posição do menu**: esquerda, direita ou oculto
   - **Layout da página inicial**: grade de cursos, carrossel, etc.
   - **Elementos de cabeçalho e rodapé**: links, informações de contato, etc.

5. **Personalizar página de login**:
   - **Imagem de fundo**: para a tela de login
   - **Mensagem de boas-vindas**: texto exibido na página de login
   - **Vídeo de fundo**: URL de vídeo para reprodução na tela de login
   - **Layout do formulário de login**: posição e estilo

#### Personalizar Blocos e Páginas

1. **Configurar blocos na página inicial**:
   - No painel de administração, acesse "Página inicial" → "Ativar edição"
   - Adicione, remova ou reorganize blocos arrastando-os
   - Configure cada bloco clicando no ícone de engrenagem
   - Blocos úteis para a página inicial:
     - **Calendário**: exibe eventos próximos
     - **Cursos em destaque**: mostra cursos selecionados
     - **HTML personalizado**: para anúncios ou boas-vindas
     - **Usuários online**: mostra quem está conectado

2. **Personalizar painel do usuário**:
   - No painel de administração, acesse "Aparência" → "Painel padrão"
   - Configure quais blocos aparecem por padrão no painel dos usuários
   - Defina layout e posições dos blocos
   - Blocos recomendados para o painel:
     - **Visão geral do curso**: lista de cursos do usuário
     - **Cronograma**: atividades com prazo próximo
     - **Mensagens**: comunicações recentes
     - **Arquivos privados**: acesso rápido aos arquivos

3. **Criar páginas personalizadas**:
   - No painel de administração, acesse "Configurações da página inicial" → "Página inicial padrão"
   - Selecione "Site home/Dashboard" para criar uma página personalizada
   - Ou use o recurso "Página" para criar páginas estáticas em qualquer lugar
   - Use HTML e CSS para design avançado
   - Incorpore elementos como:
     - Vídeo institucional
     - Carrossel de banners
     - Links rápidos para recursos importantes
     - Contagem regressiva para eventos

### Criação de Diferentes Perfis

#### Gerenciar Perfis de Usuário

1. **Entender os perfis padrão**:
   - **Administrador**: acesso completo a todas as funções
   - **Gerente**: gerencia cursos e usuários, mas não altera configurações do sistema
   - **Criador de curso**: pode criar novos cursos
   - **Professor**: gerencia conteúdo dentro de seus cursos
   - **Professor não-editor**: pode ensinar e avaliar, mas não editar conteúdo
   - **Aluno**: participa de cursos e atividades
   - **Visitante**: acesso limitado para visualização

2. **Criar perfis personalizados**:
   - No painel de administração, acesse "Usuários" → "Permissões" → "Definir funções"
   - Clique em "Adicionar um novo papel"
   - Ou duplique um papel existente como base
   - Configure:
     - **Nome curto**: identificador único (sem espaços)
     - **Nome personalizado**: nome exibido na interface
     - **Descrição**: explique o propósito do papel
     - **Tipo de papel**: contexto onde será aplicado (sistema, categoria, curso, etc.)

3. **Configurar permissões detalhadas**:
   - Na página de edição de papel, configure cada capacidade:
     - **Permitir**: concede a permissão
     - **Impedir**: nega a permissão, mas pode ser sobrescrita
     - **Proibir**: nega a permissão e não pode ser sobrescrita
   - Organize-se usando a visualização por categorias
   - Busque permissões específicas usando a caixa de pesquisa
   - Exemplos de capacidades importantes:
     - **moodle/course:create**: criar cursos
     - **moodle/course:update**: editar configurações do curso
     - **moodle/course:manageactivities**: adicionar/remover atividades
     - **moodle/user:create**: criar usuários
     - **moodle/site:config**: alterar configurações do site

4. **Exemplos de perfis personalizados**:
   - **Coordenador Departamental**:
     - Baseado no papel de Gerente
     - Restrito a uma categoria específica
     - Permissão para criar cursos e inscrever usuários
     - Acesso a relatórios de progresso
   - **Tutor**:
     - Baseado no papel de Professor não-editor
     - Permissão adicional para enviar mensagens em massa
     - Acesso a relatórios de atividade
     - Sem permissão para editar conteúdo
   - **Monitor**:
     - Baseado no papel de Aluno
     - Permissão adicional para moderar fóruns
     - Permissão para ver atividades ocultas
     - Sem permissão para alterar conteúdo

5. **Atribuir papéis personalizados**:
   - **Nível de sistema**: "Usuários" → "Permissões" → "Atribuir funções globais"
   - **Nível de categoria**: na página da categoria, "Atribuir funções"
   - **Nível de curso**: no curso, "Participantes" → "Inscrever usuários"

#### Configurar Campos de Perfil Personalizados

1. **Acessar configurações de perfil**:
   - No painel de administração, acesse "Usuários" → "Contas" → "Campos de perfil do usuário"

2. **Adicionar novos campos**:
   - Clique em "Criar um novo campo de perfil"
   - Selecione o tipo:
     - **Caixa de texto**: texto curto
     - **Área de texto**: texto longo
     - **Menu de opções**: lista suspensa
     - **Checkbox**: sim/não
     - **Data**: seletor de data
     - **Menu de opções**: seleção única
   - Configure as opções:
     - **Nome curto**: identificador (sem espaços)
     - **Nome**: título exibido
     - **Descrição**: explicação do campo
     - **Campo obrigatório**: sim/não
     - **Visível para**: quem pode ver este campo
     - **Categoria**: agrupamento do campo

3. **Exemplos de campos personalizados**:
   - **Departamento/Setor**: menu de opções com setores da empresa
   - **Cargo/Função**: texto ou menu de opções
   - **Data de Contratação**: campo de data
   - **Competências**: área de texto para listar habilidades
   - **Gestor Direto**: texto para nome do supervisor

4. **Organizar campos em categorias**:
   - Clique em "Criar uma nova categoria"
   - Configure:
     - **Nome**: título da categoria
     - **Ordem**: posição na página de perfil
   - Atribua campos existentes à nova categoria
   - Exemplos de categorias:
     - **Informações Profissionais**
     - **Contato**
     - **Interesses e Expertise**

## Automação de Processos

### Automatização de Mensagens

#### Configurar Mensagens Automáticas

1. **Acessar configurações de notificação**:
   - No painel de administração, acesse "Mensagens" → "Notificações"
   - Ou "Plugins" → "Mensagens" → "Gerenciar mensagens"

2. **Configurar notificações do sistema**:
   - Selecione o tipo de notificação para configurar
   - Para cada tipo, defina:
     - **Métodos de envio**: pop-up, e-mail, móvel, etc.
     - **Permissões**: quem pode enviar este tipo de mensagem
     - **Formato**: HTML ou texto simples
     - **Habilitar/desabilitar**: ativar ou desativar completamente

3. **Tipos de mensagens automáticas padrão**:
   - **Confirmação de inscrição**: quando um usuário é inscrito em um curso
   - **Confirmação de cadastro**: quando uma conta é criada
   - **Alertas de prazo**: quando uma atividade está prestes a vencer
   - **Feedback recebido**: quando um professor avalia um trabalho
   - **Postagem em fórum**: quando há nova atividade em fóruns assinados
   - **Mensagens diretas**: comunicações entre usuários

#### Personalizar Modelos de E-mail

1. **Acessar modelos de e-mail**:
   - No painel de administração, acesse "Idioma" → "Personalização de idioma"
   - Selecione o pacote de idioma (ex: Português - Brasil)
   - Busque o componente "message" ou o tipo específico de e-mail

2. **Editar modelos**:
   - Selecione o arquivo de string que contém o modelo
   - Edite o texto, mantendo as variáveis do sistema (ex: {$a->coursename})
   - Use HTML para formatação avançada
   - Variáveis comuns:
     - **{$a->firstname}**: primeiro nome do destinatário
     - **{$a->lastname}**: sobrenome do destinatário
     - **{$a->sitename}**: nome da plataforma
     - **{$a->coursename}**: nome do curso
     - **{$a->link}**: link relevante para a ação

3. **Exemplo de personalização - Boas-vindas ao curso**:
   ```html
   <h2>Bem-vindo(a) ao curso {$a->coursename}!</h2>
   
   <p>Olá {$a->firstname},</p>
   
   <p>Você foi inscrito(a) com sucesso no curso <strong>{$a->coursename}</strong>.</p>
   
   <p>Para começar, acesse o curso através do link: <a href="{$a->link}">{$a->coursename}</a></p>
   
   <p>Se você tiver dúvidas, entre em contato com seu instrutor ou com o suporte.</p>
   
   <p>Atenciosamente,<br>
   Equipe de Treinamento<br>
   {$a->sitename}</p>
## Controle de Turmas e Inscrições

### Inscrição Manual e Auto-inscrição

#### Inscrição Manual de Usuários

1. **Inscrever usuários individualmente**:
   - Acesse o curso desejado
   - No bloco de administração, clique em "Usuários" → "Participantes"
   - Clique no botão "Inscrever usuários"
   - Busque os usuários pelo nome ou e-mail
   - Selecione a função apropriada (Aluno, Professor, etc.)
   - Configure duração da inscrição, se necessário
   - Clique em "Inscrever usuários"

2. **Inscrição em massa**:
   - Para inscrever muitos usuários de uma vez:
     - Crie uma coorte (grupo global) primeiro
     - No painel de administração, acesse "Usuários" → "Contas" → "Coortes"
     - Crie uma nova coorte e adicione usuários
     - No curso, acesse "Usuários" → "Métodos de inscrição"
     - Adicione o método "Sincronização de coorte"
     - Selecione a coorte e a função a ser atribuída
     - Todos os membros da coorte serão inscritos automaticamente

#### Configurar Auto-inscrição

1. **Habilitar auto-inscrição**:
   - No curso, acesse o bloco de administração → "Usuários" → "Métodos de inscrição"
   - Clique no ícone de olho (👁️) ao lado de "Auto-inscrição" para ativá-lo
   - Clique no ícone de engrenagem para configurar

2. **Configurações básicas**:
   - **Nome personalizado da instância**: descrição do método
   - **Permitir inscrições novas**: sim/não
   - **Chave de inscrição**: senha para acesso ao curso
   - **Usar chaves de inscrição de grupo**: senhas específicas para cada grupo
   - **Função atribuída por padrão**: geralmente "Aluno"

3. **Configurações avançadas**:
   - **Data de início**: quando as inscrições abrem
   - **Data limite**: quando as inscrições fecham
   - **Duração da inscrição**: período após o qual a inscrição expira
   - **Notificação de expiração**: alertas antes do término
   - **Limite de inscritos**: número máximo de participantes
   - **Enviar mensagem de boas-vindas**: e-mail automático após inscrição

4. **Distribuir chave de inscrição**:
   - Compartilhe a chave com alunos elegíveis via:
     - E-mail direto
     - Comunicado interno
     - Sistema de gestão (intranet)
   - Instrua os alunos a:
     - Acessar a página do curso
     - Clicar em "Inscrever-me neste curso"
     - Inserir a chave de inscrição
   - Considere renovar as chaves periodicamente por segurança

#### Inscrição com Chaves de Acesso

1. **Criar diferentes chaves para diferentes grupos**:
   - Configure o curso para usar grupos
   - No método de auto-inscrição, ative "Usar chaves de inscrição de grupo"
   - Na página de configuração do método, defina uma chave diferente para cada grupo
   - Os alunos serão automaticamente adicionados ao grupo correspondente à chave utilizada

2. **Gerenciar chaves de inscrição**:
   - Mude periodicamente as chaves para maior segurança
   - Documente quais chaves foram distribuídas e para quem
   - Configure expiração de chaves para cursos recorrentes
   - Para revogar acesso, altere a chave e redistribua apenas para usuários autorizados

3. **Monitorar inscrições**:
   - Verifique regularmente a lista de participantes
   - Configure notificações para novas inscrições
   - Monitore o limite de inscritos, se definido
   - Remova inscrições não autorizadas, se necessário

### Organização de Grupos e Turmas

#### Criar e Gerenciar Grupos

1. **Configurar grupos no curso**:
   - Acesse o curso desejado
   - No bloco de administração, clique em "Usuários" → "Grupos"
   - Clique no botão "Criar grupo"
   - Configure:
     - **Nome do grupo**: identificação clara (ex: "Turma A", "Departamento RH")
     - **Descrição**: detalhes sobre o propósito do grupo
     - **Chave de inscrição**: se utilizará auto-inscrição específica
     - **Imagem do grupo**: ícone ou foto representativa (opcional)
   - Clique em "Salvar alterações"

2. **Adicionar membros ao grupo**:
   - Na página de grupos, selecione o grupo desejado
   - Clique em "Adicionar/remover usuários"
   - Na coluna direita, selecione os usuários a serem adicionados
   - Clique no botão "Adicionar"
   - Os usuários selecionados aparecerão na coluna esquerda
   - Clique em "Voltar aos grupos"

3. **Criar múltiplos grupos de uma vez**:
   - Na página de grupos, clique em "Criar grupos automaticamente"
   - Configure:
     - **Esquema de nomeação**: prefixo e numeração
     - **Número de grupos** ou **Membros por grupo**
     - **Método de alocação**: aleatório ou alfabético
     - **Selecionar membros de função**: quais funções incluir
   - Clique em "Enviar" para criar os grupos

#### Configurar Agrupamentos

Os agrupamentos são "grupos de grupos" que permitem organizar atividades para conjuntos específicos de alunos:

1. **Criar um agrupamento**:
   - Na página de grupos, clique na aba "Agrupamentos"
   - Clique em "Criar agrupamento"
   - Configure:
     - **Nome**: identificação do agrupamento
     - **Descrição**: propósito e detalhes
   - Clique em "Salvar alterações"

2. **Adicionar grupos ao agrupamento**:
   - Na lista de agrupamentos, clique no ícone "Mostrar grupos"
   - Clique em "Adicionar/remover grupos"
   - Selecione os grupos a serem incluídos
   - Clique em "Voltar aos agrupamentos"

3. **Utilizar agrupamentos para atividades**:
   - Ao criar ou editar uma atividade, vá para a seção "Configurações comuns de módulo"
   - Configure:
     - **Modo de grupo**: "Sem grupos", "Grupos separados" ou "Grupos visíveis"
     - **Agrupamento**: selecione o agrupamento desejado
     - **Disponível apenas para membros do agrupamento**: sim/não
   - A atividade estará disponível apenas para os grupos incluídos no agrupamento selecionado

#### Configurar Turmas Paralelas

1. **Estrutura com grupos**:
   - Crie um único curso com todos os materiais
   - Crie grupos para cada turma paralela (ex: "Turma Manhã", "Turma Noite")
   - Configure atividades em "Grupos separados"
   - Professores podem alternar entre grupos para visualizar e avaliar

2. **Estrutura com cursos duplicados**:
   - Crie cursos separados para cada turma
   - Use a função "Duplicar curso" para replicar o conteúdo
   - Atribua professores específicos para cada curso
   - Vantagens: avaliação e progresso completamente separados
   - Desvantagens: mudanças de conteúdo precisam ser replicadas manualmente

3. **Configurar visibilidade para turmas específicas**:
   - Para materiais ou atividades exclusivos:
     - Crie um agrupamento para cada turma
     - Configure itens específicos para estarem "Disponíveis apenas para membros do agrupamento"
     - Itens comuns devem estar disponíveis para todos
   - Alternativamente, use "Restringir acesso" → "Grupo" para limitar a visibilidade

### Monitoramento e Gerenciamento de Turmas

#### Acompanhar Progresso das Turmas

1. **Visualizar progresso por grupo**:
   - Acesse o relatório de conclusão do curso
   - Filtre por grupo específico
   - Analise métricas como:
     - Porcentagem de conclusão
     - Atividades problemáticas (baixa taxa de conclusão)
     - Usuários com progresso lento

2. **Comparar desempenho entre grupos**:
   - No livro de notas, use filtros por grupo
   - Calcule e compare médias, medianas e distribuição de notas
   - Identifique disparidades que possam indicar:
     - Diferenças na qualidade da instrução
     - Variações no nível de preparação dos alunos
     - Problemas de engajamento em grupos específicos

3. **Monitorar engajamento**:
   - Acesse relatórios de logs e atividade
   - Filtre por grupo e período
   - Analise métricas como:
     - Frequência de acesso
     - Tempo médio no curso
     - Participação em fóruns
     - Cumprimento de prazos

#### Intervir em Problemas Comuns

1. **Baixo engajamento em um grupo**:
   - Identifique o problema usando relatórios de acesso
   - Possíveis intervenções:
     - Envie mensagem direta para o grupo
     - Adicione conteúdo mais relevante para esse público
     - Ajuste o nível de dificuldade se necessário
     - Considere mudar o instrutor ou abordagem

2. **Altas taxas de reprovação**:
   - Analise quais atividades têm notas mais baixas
   - Possíveis intervenções:
     - Ofereça material de apoio adicional
     - Crie atividades preparatórias
     - Permita novas tentativas
     - Revise as avaliações para verificar adequação

3. **Problemas de comunicação**:
   - Monitore fóruns e taxas de resposta
   - Possíveis intervenções:
     - Estabeleça expectativas claras de participação
     - Introduza atividades quebra-gelo para grupos mais reservados
     - Crie fóruns temáticos mais específicos
     - Designe moderadores para estimular discussões

#### Reorganizar Grupos durante o Curso

1. **Mover alunos entre grupos**:
   - Na página de grupos, selecione o grupo de origem
   - Selecione os alunos a serem movidos
   - Clique em "Remover"
   - Selecione o grupo de destino
   - Clique em "Adicionar/remover usuários"
   - Selecione os mesmos alunos e clique em "Adicionar"

2. **Dividir grupos grandes**:
   - Crie novos grupos para acomodar a divisão
   - Mova manualmente os alunos ou use a função "Criar grupos automaticamente"
   - Ajuste agrupamentos para refletir a nova estrutura
   - Atualize as configurações de acesso às atividades

3. **Fundir grupos pequenos**:
   - Mova todos os membros para um dos grupos
   - Delete ou desative o grupo vazio
   - Atualize agrupamentos conforme necessário
   - Revise configurações de acesso às atividades

## Backup e Restauração

### Backup de Cursos

#### Criar Backup Manual

1. **Iniciar o processo**:
   - Acesse o curso desejado
   - No bloco de administração, clique em "Backup"
   - Você será direcionado para o assistente de backup

2. **Configurar o escopo do backup**:
   - **Incluir**: selecione quais elementos serão incluídos
     - Atividades específicas ou todas
     - Blocos
     - Filtros
     - Comentários
     - Logs
     - Histórico de conclusão
     - Eventos de usuário
   - **Configurações**: defina detalhes do backup
     - **Incluir usuários inscritos**: sim/não
     - **Incluir atividades e recursos anônimos**: sim/não
     - **Incluir funções atribuídas**: sim/não
     - **Incluir arquivos de curso**: sim/não

3. **Configurações de esquema**:
   - **Filename**: nome do arquivo de backup (padrão: backup-moodle2-course-ID-NOME-DATA-HORA.mbz)
   - **Configurações**: opções avançadas
     - **Incluir blocos**: sim/não
     - **Incluir filtros**: sim/não
     - **Incluir comentários**: sim/não
     - **Incluir funções atribuídas por contexto**: sim/não
     - **Incluir calendários**: sim/não

4. **Confirmação e processamento**:
   - Revise todas as configurações
   - Clique em "Executar backup"
   - Aguarde o processamento (pode levar tempo para cursos grandes)
   - Após a conclusão, você verá o arquivo na área de backups privados

5. **Gerenciar os arquivos de backup**:
   - O arquivo será salvo na área de "Backup de curso"
   - Você pode:
     - **Baixar**: salvar o arquivo .mbz em seu computador
     - **Restaurar**: usar para restaurar em outro curso
     - **Renomear**: alterar o nome do arquivo para identificação
     - **Excluir**: remover arquivos antigos ou desnecessários

#### Configurar Backup Automático

1. **Acessar configurações**:
   - No painel de administração do site, acesse "Cursos" → "Backups" → "Configurações de backup automático"

2. **Configurar programação**:
   - **Backup automático ativo**: habilitar/desabilitar
   - **Horário para execução**: definir horário (preferencialmente fora do horário de pico)
   - **Dias para execução**: selecionar dias da semana
   - **Quantos backups por curso**: número de versões mantidas (rotação)
   - **Período mínimo entre backups**: intervalo entre execuções

3. **Configurar conteúdo**:
   - **Incluir módulos**: selecionar quais tipos de atividades incluir
   - **Incluir inscrições de usuários**: sim/não
   - **Incluir funções atribuídas**: sim/não
   - **Incluir arquivos**: sim/não
   - **Incluir histórico de conclusão**: sim/não
   - **Incluir logs**: sim/não

4. **Configurar armazenamento**:
   - **Destino**: onde os backups serão armazenados
     - **Área de backup do curso**: no próprio Moodle
     - **Diretório do sistema**: pasta no servidor
   - **Nome do diretório**: para backups armazenados no sistema de arquivos

### Restauração de Cursos

#### Restaurar um Backup

1. **Iniciar o processo**:
   - Para restaurar em curso existente:
     - Acesse o curso de destino
     - No bloco de administração, clique em "Restaurar"
   - Para criar um novo curso:
     - No painel de administração, acesse "Cursos" → "Restaurar curso"
   - Ou, na área de backups, selecione arquivo e clique em "Restaurar"

2. **Selecionar o arquivo de backup**:
   - **Importar arquivo de backup**: fazer upload de um arquivo .mbz
   - **Restaurar da área de backups**: usar arquivo já presente no sistema
   - **Área de backup do curso**: usar backup automático ou manual de curso específico

3. **Confirmação e detalhes**:
   - Revise os detalhes do backup (data, versão, conteúdo)
   - Clique em "Continuar"

4. **Configurar destino**:
   - Selecione uma das opções:
     - **Restaurar como novo curso**: cria um curso inteiramente novo
     - **Restaurar neste curso**: pode mesclar ou substituir conteúdo atual
     - **Mesclar o backup com este curso**: adiciona conteúdo sem remover o existente

5. **Configurar detalhes**:
   - Para novo curso:
     - **Nome completo e curto**: identificação do curso
     - **Categoria de curso**: onde o curso será criado
     - **Data de início**: quando o curso estará disponível
   - Para restauração em curso existente:
     - **Restaurar sobre este curso**: excluir conteúdo atual primeiro
     - **Mesclar**: adicionar conteúdo do backup ao existente

6. **Configurar conteúdo**:
   - Selecione quais elementos específicos restaurar:
     - Atividades e recursos específicos
     - Blocos
     - Filtros
     - Usuários
   - Configure as opções para cada tipo:
     - Substituir configurações
     - Incluir atividades
     - Incluir blocos
     - Incluir filtros

7. **Confirmação final**:
   - Revise todas as configurações
   - Clique em "Executar restauração"
   - Aguarde o processamento (pode levar tempo para cursos grandes)
   - Após a conclusão, você será direcionado para o curso restaurado

#### Importar Dados Entre Cursos

1. **Usando a função de importação**:
   - Acesse o curso de destino (onde deseja importar o conteúdo)
   - No bloco de administração, clique em "Importar"
   - Selecione o curso de origem (de onde deseja importar)
   - Selecione os elementos a serem importados
   - Configure detalhes específicos
   - Execute a importação

2. **Diferenças entre importar e restaurar**:
   - **Importação**: transfere apenas conteúdo e atividades, não dados de usuários
   - **Restauração**: pode incluir dados de usuários, inscrições e registros
   - Use importação para:
     - Transferir materiais didáticos entre cursos
     - Reutilizar questionários e atividades
     - Manter estrutura consistente entre cursos similares
   - Use restauração para:
     - Criar cópias completas de cursos
     - Mover cursos entre servidores Moodle
     - Arquivar cursos inteiros com dados de alunos

## Manutenção e Otimização

### Otimizar Desempenho da Plataforma

#### Configurações de Cache

1. **Acessar configurações**:
   - No painel de administração, acesse "Servidor" → "Cache" → "Configuração"

2. **Configurar armazenamentos de cache**:
   - **Aplicação**: cache para dados de aplicação
   - **Sessão**: cache para dados de sessão
   - **Solicitação**: cache para dados de requisição única
   - Opções de armazenamento:
     - **Arquivo**: armazenamento em disco (padrão, mais lento)
     - **APCu**: cache na memória (mais rápido)
     - **Memcached**: distribuído, para múltiplos servidores
     - **Redis**: armazenamento de dados estruturados em memória

3. **Mapeamentos de cache**:
   - Configure quais definições de cache usam quais armazenadores
   - Priorize armazenamento em memória para:
     - **Cache MUC**: cache central do Moodle
     - **Cache de aplicação**: dados frequentemente acessados
     - **Cache de sessão**: para melhor desempenho de usuários

4. **Limpar cache**:
   - Periodicamente limpe caches para:
     - Aplicar alterações de configuração
     - Resolver problemas de desempenho
     - Forçar regeneração de dados
   - No painel de administração, acesse "Desenvolvimento" → "Limpar todos os caches"

#### Gerenciamento de Arquivos

1. **Configurar repositórios de arquivos**:
   - No painel de administração, acesse "Plugins" → "Repositórios" → "Gerenciar repositórios"
   - Ative/configure repositórios como:
     - **Servidor de arquivos**: armazenamento no próprio Moodle
     - **Arquivos privados**: área pessoal de cada usuário
     - **Integrações externas**: Google Drive, OneDrive, Dropbox, etc.

2. **Otimizar armazenamento**:
   - Configure tamanho máximo de arquivos:
     - No site: "Administração do site" → "Segurança" → "Políticas do site"
     - Por curso: nas configurações do curso
     - Por atividade: nas configurações de cada atividade
   - Monitore uso de espaço:
     - No painel de administração, acesse "Relatórios" → "Estatísticas do site"
     - Verifique tendências de crescimento

3. **Gerenciar arquivos não utilizados**:
   - Remova arquivos orfãos:
     - No painel de administração, acesse "Servidor" → "Limpeza do sistema de arquivos"
     - Execute a verificação e remoção de arquivos não referenciados
   - Considere políticas de retenção:
     - Defina por quanto tempo manter backups antigos
     - Configure limpeza automática de arquivos de cursos excluídos

### Monitoramento da Plataforma

#### Relatórios do Sistema

1. **Visualizar logs do sistema**:
   - No painel de administração, acesse "Relatórios" → "Logs"
   - Configure filtros para focar em:
     - Erros específicos
     - Ações administrativas
     - Atividades suspeitas

2. **Verificar estatísticas**:
   - No painel de administração, acesse "Relatórios" → "Estatísticas"
   - Analise tendências de:
     - Número de usuários ativos
     - Visualizações de curso
     - Envios de atividades
     - Uso por horário do dia

3. **Monitorar segurança**:
   - No painel de administração, acesse "Relatórios" → "Segurança" → "Visão geral"
   - Verifique:
     - Tentativas de login malsucedidas
     - Vulnerabilidades detectadas
     - Plugins desatualizados

#### Verificação de Integridade

1. **Verificar saúde do sistema**:
   - No painel de administração, acesse "Servidor" → "Verificações de ambiente"
   - Verifique requisitos de PHP, banco de dados e servidor
   - Resolva quaisquer avisos ou erros relatados

2. **Verificar atualizações**:
   - No painel de administração, acesse "Verificar atualizações"
   - Mantenha o sistema e plugins atualizados
   - Planeje atualizações em períodos de baixo uso

3. **Backup do sistema completo**:
   - Configure backups completos do servidor:
     - Arquivos do Moodle
     - Banco de dados
     - Configurações do servidor
   - Armazene em local seguro e teste restaurações periodicamente

### Práticas Recomendadas

1. **Manutenção regular**:
   - Implemente um cronograma de manutenção:
     - Diária: verificação de logs de erro
     - Semanal: limpeza de caches, verificação de backups
     - Mensal: verificação de espaço em disco, atualização de plugins
     - Semestral: atualização completa do sistema

2. **Documentação**:
   - Mantenha documentação atualizada de:
     - Configurações do servidor
     - Plugins instalados
     - Personalizações realizadas
     - Procedimentos de recuperação de desastres

3. **Planejamento de capacidade**:
   - Monitore métricas-chave:
     - Uso de CPU e memória
     - Espaço em disco
     - Tempos de resposta
   - Planeje expansões antes de atingir limites críticos
   - Considere solução de nuvem para escalabilidade

---

## Conclusão

Este manual abrangente cobre as principais funcionalidades do Moodle para moderadores e administradores. Para questões específicas ou avançadas, consulte a documentação oficial ou entre em contato com o suporte técnico.

Lembre-se de que a plataforma Moodle está em constante evolução, com novas funcionalidades sendo adicionadas regularmente. Mantenha-se atualizado com a documentação oficial e participe da comunidade Moodle para obter informações sobre as melhores práticas e novidades.