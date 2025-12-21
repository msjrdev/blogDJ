# Projeto de um Blog em Django

Este repositório contém o código-fonte do meu Sistema de Blog Django. Trata-se de um sistema de blog completo e funcional, onde estou me aprofundando mais em Django na prática — desde modelos, templates e formulários até permissões, dashboards e implantação.


---

## O que contém esse projeto

- Estrutura do projeto e layout de pastas em um cenário real  
- Modelos: Blog, Categoria, Comentário, Relações de Usuário, slugs, manipulação de mídia  
- Formulários: Criar/Editar posts, cadastro de usuários, comentários  
- Autenticação e Autorização: Login, logout, Grupos, Permissões, decorators  
- Personalizações e listagens do painel administrativo  
- Dashboards para Editores/Gerentes com verificação de funções  
- Busca, paginação, posts em destaque e recentes  
- Upload de arquivos (mídia), arquivos estáticos e templates  
- Checklist e etapas de implantação

---

## Funcionalidades implementadas

- Sistema de múltiplas funções (Administrador / Gerente / Editor / Autor)  
- Criar / Ler / Atualizar / Excluir (CRUD) para posts e categorias  
- Geração e preenchimento automático de slugs únicos  
- Upload e configuração de mídia (imagem)  
- Sistema de comentários (somente usuários autenticados podem comentar)  
- Painéis de controle para Gerente e Editor com contagens e tabelas  
- Verificações granulares de permissão (usando Grupos e Permissões do Django + verificações personalizadas)  
- Função de busca com retenção do termo de busca na caixa de texto  
- Deploy do projeto

---

## Requisitos
- Python 3.13 ou superior (recomendado)  
- Django 5.x (consulte requirements.txt) - use sempre a versão mais recente 
- UV (gerenciador e instalador de pacotes Python moderno e de alto desempenho, escrito em Rust)
- PostgreSQL / MySQL ou SQLite para desenvolvimento
