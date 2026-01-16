# Bug - Erro na Recuperação de Senha

## Descrição
Ao tentar recuperar a senha utilizando um e-mail válido,, o sistema não exibe mensagem de confirmação para o usuário.

## Ambiente
- Navegador: Chrome
- Sistema operacional: Windows 10
- Dispositivo: Desktop
- Ambiente: Teste

## Pré-condição
- Usuário cadastrado no sistema
- Usuário na tela de login

## Passos para reproduzir
1. Acessar o site
2. Clicar em "Esqueci minha senha"
3. Informar um e-mail válido cadastrado
4. Clicar no botão "Enviar"

## Resultado esperado
Sistema deve exibir mensagem informando que as instruções de recuperação de senha foram enviadas para o e-mail do usuário.

## Resultado obtido
Sistema não exibe nenhuma mensagem de confirmação após o envio do e-mail.

## Severidade
Média

## Prioridade 
Média

## Teste Case relacionado
TC_Forgot_Password.md
