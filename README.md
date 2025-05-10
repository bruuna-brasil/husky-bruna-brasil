# husky-bruna-brasil

# Relatório - Configuração do Husky

## Objetivo
Configurar hooks com Husky para garantir a qualidade do código antes do commit e push.

## Etapas Realizadas

1. Criação do repositório `atividade-husky` no GitHub.
2. Inicialização do projeto com `npm init -y`.
3. Instalação do Husky e ativação com `npx husky install`.
4. Criação do hook `pre-commit` para:
   - Verificação de lint (`npm run lint`)
   - Compilação do projeto (`npm run build`)
5. Criação do hook `pre-push` para:
   - Execução dos testes (`npm test`)
6. Adição de scripts ao `package.json`.

## Evidências

### ✅ Execução do `pre-commit`
![Pre-commit](./screenshots/pre-commit.png)

### ✅ Execução do `pre-push`
![Pre-push](./screenshots/pre-push.png)

## Conclusão
O Husky foi configurado corretamente e os hooks estão funcionando conforme esperado. Todos os commits seguem a convenção semântica.
