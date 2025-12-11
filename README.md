# Documentação do Módulo de Conexão

## Descrição 
Este projeto implementa um padrão de conexão segura com banco de dados, utilizando **Design Patterns** para evitar *Hardcoding*.

## O que foi feito 
- [x] Criação do repositorio
- [x] Implementação da conexão
- [x] Resolução de conflito Merge
- [x] Separação de comfiguraçao

## Exemplo de Uso
Abaixo, o codigo padrão utilizado pelo Arquiteto:

```python
# Constante de configuração
DB_HOST = "192.168.0.1"

def conectar_banco():
return f"conectado ao {DB_HOST} "
