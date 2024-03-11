# Documentação da Collection de APIs

Bem-vindo à documentação da nossa Collection da API de Portadores! Aqui você encontrará informações essenciais sobre como utilizar nossa API de forma eficaz.

## Conceito de Portador

Na nossa empresa de soluções de meios de pagamento, o termo "portador" refere-se ao usuário final, ou seja, o dono do cartão de crédito que utiliza nossos serviços.

## Organização da Collection

Nossa Collection da API de Portadores está organizada em duas pastas:

1. **Autenticação**: Esta pasta contém endpoints relacionados à autenticação e geração de token de acesso.

2. **Portador API**: Aqui você encontrará endpoints específicos destinados ao gerenciamento de informações do portador.

## Preparação para Uso
A Collection já está preparada para uso imediato, segue instruções:
1. Gere o token no endpoint dentro da pasta Autenticação 
2. Abra a pasta Portador API e consuma o endpoint desejado

Não é necessário ajustar nenhuma variável. Basta gerar o token na pasta de Autenticação e depois utilizar os demais endpoints sem alterar nada. Todo o ambiente já foi configurado remotamente.

## Adicionando Token Manualmente
Caso as variáveis fiquem desconfiguradas ou você precise adicionar o token manualmente, siga estas instruções:
1. Gere o token no endpoint dentro da pasta Autenticação e o copie
2. Abra a pasta Portador API e abra o endpoint desejado
3. No menu de Headers, adicione o token gerado
4. No campo Authorization, insira o comando "Bearer" seguido do token.


```makefile
Authorization: Bearer SEU_TOKEN_DE_ACESSO

```
Isso garante que as solicitações sejam autenticadas corretamente e tenham acesso aos recursos protegidos pela autenticação.
