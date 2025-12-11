# Documentação do modulo de Conexão

## Descrição
Este projeto implementa um padrão de conexão segura com o banco de dados, utilizando **Design Patter para evitar *hard coding*

## O que foi feito
-[x] Criação de repositório
-[x] Implementação da conexão
-[x] Resolução de conflito de merge
-[x] Separação de configuração

## Exemplo de uso
Abaixo o Código padrão utilizando pelo arquiteto:

''' Python
# Constante de configuração
DB_HOST = "192.168.0.1"

def conectar banco():
    *** Conecta usando a constante definida***
    return f"Conectado ao {DB_HOST}"
