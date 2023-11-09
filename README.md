# Sankhya-PHP-API
Conexão de página única para acessar a API do sankhya, sem complicação.

Nessa página específica estou usando a API para logar e para acessar o DBExplorer.

Depois de tentar muito se conectar de forma mais simples, essa foi a forma mais tranquila que eu achei.
## Tudo que tiver -SUA/SEU- é para você por os dados do seu sistema
Lista de itens que precisarão ser trocados:
### No login (primeira parte):

--IP do servidor

--Porta do servidor

--Nome de Usuário

--Senha de usuário


### Na query(segunda parte):

--IP do servidor

--Porta do servidor

--Query (O que deseja buscar no banco de dados)

## Possíveis Problemas:

### Usamos o "Curl" para fazer a resquisição, então se você não tiver ele ativado no seu XAMPP vai dar problema, aqui um guia rapido para ativa:

Acesse seu php.ini, normalmente localizado no diretório: C:xamppapachephp

Procure pela linha: ;extension=php_curl.dll

Descomente essa linha ( tira-se o ; do inicio da linha )

Salve o documento

reinicie o Xampp



