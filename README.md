# study_rust

- Repositório de Dependências: https://crates.io/

# Primeiros passos

## Check
```bash
rustup update

rustc --version

cargo --version
```

## Novo projeto
```bash
cargo new hello-rust

cd hello-rust

cargo run
```
# Comandos Cargo
A carga é o sistema de construção e gerente de pacotes da Rust.A maioria dos Rustaceans usa essa ferramenta para gerenciar seus projetos de ferrugem, porque a carga lida com muitas tarefas para você, como criar seu código, baixar as bibliotecas depende e construir essas bibliotecas.(Chamamos as bibliotecas de que seu código precisa de dependências.)

|Comandos|O que faz|
|:--|:--|
|`cargo new`|Cria um projeto|
|`cargo run`|Executa o projeto
|`cargo build`|Instala dependências

# Comandos rustc
|Comandos|O que faz|
|:--|:--|
|`rustc main.rs`|Compila a logica rust (gera um executável)