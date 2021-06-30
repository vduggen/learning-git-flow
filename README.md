# Git Flow

## Nomenclatura branch

- ### **master**: contém o nosso código de produção, todo o código que estamos desenvolvendo, em algum momento será “juntado” com essa branch

- ### **develop**: contém o código do nosso próximo deploy, isso significa que conforme as features vão sendo finalizadas elas vão sendo juntadas nessa branch para posteriormente passarem por mais uma etapa antes de ser juntada com a master

- ### **feature/\***: são branches para o desenvolvimento de uma funcionalidade específica, por convenção elas tem o nome iniciado por feature/, por exemplo: feature/cadastro-usuarios. Importante ressaltar que essas branches são criadas sempre à partir da branch develop

- ### **hotfix/\***: são branches responsáveis pela realização de alguma correção crítica encontrada em produção e por isso são criadas à partir da master. Importante ressaltar que essa branch deve ser juntada tanto com a master quanto com a develop

- ### **release/\***: tem uma confiança maior que a branch develop e que se encontra em nível de preparação para ser juntada com a master e com a develop (caso alguma coisa tenha sido modificada na branch em questão)

# Refêrencias

- [Git Flow Introdução](https://tableless.com.br/git-flow-introducao/)
- [Cheatsheet](https://danielkummer.github.io/git-flow-cheatsheet/index.pt_BR.html)
- [Versionamento Semântico](https://semver.org/lang/pt-BR/)
