# História em Missão — Os 12 Trabalhos de Hércules

Aplicativo complementar ao jogo escolar do 7º R, Escola Pedro Apóstolo. É uma primeira versão demonstrativa com dois perfis e atividades educativas contextualizadas na cultura da Grécia Antiga.

## Como executar no VS Code

1. Extraia a pasta `Historia-em-Missao` do arquivo ZIP.
2. No VS Code, use **Arquivo > Abrir Pasta**.
3. Abra `index.html` em um navegador, ou use a extensão **Live Server** e escolha **Open with Live Server**.
4. Na tela inicial, cadastre um professor, crie uma turma e anote o código. Clique em **Sair** e entre como estudante usando o código **no mesmo navegador**.

Não é necessário instalar dependências nem usar terminal.

## Recursos do professor

- Criação de turmas e códigos locais.
- Propostas de atividades escritas relacionadas às missões e ao jogo externo.
- Visão de missões concluídas, tentativas e respostas por aluno.
- Exportação de relatórios CSV (abríveis em Excel).

## Recursos do estudante

- Campanha das **12 missões** inspiradas nos trabalhos de Hércules.
- Questões objetivas sobre mitologia como fonte cultural, sociedade grega e prática histórica.
- Feedback imediato, novas tentativas, pontos e mapa de progresso.
- Diário de descobertas desbloqueado com acertos.
- Resposta às propostas escritas pelo professor.
- Fontes maiores, alto contraste, narração por voz do navegador e lembretes de pausas.

## Limitações e uso responsável

**Atenção:** este protótipo salva os dados no `localStorage` do navegador. Não há servidor, banco de dados remoto, contas verificadas, senhas nem sincronização entre dispositivos. Os códigos de turma não funcionam em outro computador; nomes iguais na mesma turma reutilizam o mesmo perfil. Isso é adequado apenas para demonstração local na feira, **não para armazenar dados identificáveis de alunos em uso escolar real**.

As 12 tarefas foram transformadas em um módulo histórico introdutório. As histórias de Hércules pertencem à tradição **mitológica**; não são narradas como fatos históricos comprovados. A versão atual usa textos e ícones, sem imagens de mãos ou material externo. Recursos de acessibilidade ajudam na experiência, mas não garantem, isoladamente, adequação a todos os estudantes com TDAH.

Para funcionar em vários aparelhos, a próxima etapa seria implementar backend, autenticação, proteção de dados pessoais e persistência remota seguindo as exigências legais aplicáveis.

## Arquivos

- `index.html`: entrada da aplicação.
- `style.css`: visual responsivo em roxo, dourado e tons de pergaminho.
- `app.js`: regras dos perfis, missões, atividades e relatórios.
