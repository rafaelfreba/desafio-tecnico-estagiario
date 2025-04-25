### 🎯  DESAFIO TÉCNICO PARA VAGA DE ESTÁGIO COMO DESENVOLVEDOR PHP/LARAVEL SES-MT

📌 Objetivo:

Criar uma aplicação simples de Gestão de Tarefas (To-Do List), com funcionalidades básicas de CRUD, autenticação e uma interface responsiva utilizando Bootstrap e Blade.

🛠️ Tecnologias Requeridas
```bash
  Backend: Laravel 12
  
  Frontend: Blade Template Engine + Bootstrap 5
  
  Banco de Dados: MySQL ou SQLite
  
  Autenticação: Laravel Breeze (ou Jetstream, se preferir)
  
  Versionamento: Git (GitHub)
```
✅ Funcionalidades Esperadas
```bash
  1. Autenticação

    * Login e cadastro de usuários.
    
    * Cada usuário só pode visualizar suas próprias tarefas.
    
    🚨 Dica: [Para as permissões use Spatie (opcional)](https://spatie.be/docs/laravel-permission/v6/introduction)
```
```bash
  2. CRUD de Tarefas

    Listagem das tarefas com:
    
      * Título
      
      * Descrição
      
      * Status (Pendente, Concluída)
      
      * Data de criação
      
      * Criação de novas tarefas
      
      * Edição de tarefas existentes
      
      * Conclusão de tarefas (trocar o status para "Concluída")
      
      * Exclusão de tarefas
```
```bash
  3. Interface
  
    * Utilizar Blade + Bootstrap
    
    * Layout base com menu fixo (navbar) contendo nome do usuário logado e opção de logout
    
    * Responsivo (pode testar com dev tools do navegador)
    
    🚨 Dica: [Para o layout use AdminLte3 (opcional)](https://github.com/jeroennoten/Laravel-AdminLTE/wiki/Installation)
```
```bash
  4. Extra (opcional, vale ponto bônus)

    * Filtro por status (Todas, Pendentes, Concluídas)
    
    * Paginação na listagem
    
    * Testes automatizados (Feature ou Unit Test com PHPUnit)
```
📁 Organização do Projeto

    * Utilize boas práticas de estruturação de código (controllers, requests, models, etc.)
    
    * Use migrations e seeders
    
    * Inclua um README.md com as instruções para rodar o projeto
    
    * Capturas de tela (opcional)

🚀 Critérios de Avaliação

  * Organização e legibilidade do código
  
  * Estrutura de pastas e uso correto do Laravel
  
  * Separação de responsabilidades (controller, request, model)
  
  * Uso correto do Blade e Bootstrap

  * Funcionalidade completa do CRUD

  * Git com histórico de commits claros e organizados

  * Capricho na UI, mesmo que simples


