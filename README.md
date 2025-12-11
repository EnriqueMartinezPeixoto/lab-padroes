# Documentação do Modulo de Conexão

## Descrição
Este projeto implementa um padrão de conexão segura com o banco de dados, utilizando **Design Pattern** para evitar hardcoding

# O que foi feito
- [x] Criação de repositorio
- [x] Implemento da Conexão
- [x] Resolução de conflito de Merge
- [x] Separação de configuração

## Exemplo de Uso
Abaixo o codigo padrão utilizado pelo arquiteto

``` Python
# Constante de configuração
DB_HOST = "192.168.0.1"

def conectar_banco():
  """Conecta usando a constante definida"
return f"Conectando ao {DB_HOST}"
