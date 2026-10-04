# painel-login

Página intermediária do botão **"Entrar com Google"** do Painel do Salão.

O Google só devolve o login para endereços `https`, e o painel fica na rede local do salão (`http://192.168.x.x`). Esta página recebe a resposta do Google e redireciona o celular de volta para o painel. Ela só aceita redirecionar para endereços de rede local.

Não guarda nada: é um HTML estático sem servidor.
