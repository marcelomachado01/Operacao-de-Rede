# Operações de Rede com Bash 

Este script Bash oferece um conjunto de ferramentas para realizar operações básicas de rede diretamente do seu terminal. Ele permite visualizar configurações de rede, verificar conectividade e examinar a tabela de roteamento.

## Funcionalidades

* **Exibir configurações de rede ⚙️:**
    * Mostra as configurações de rede do seu sistema, incluindo endereços IP, máscaras de rede e interfaces.
    * Utiliza o comando `ifconfig` para exibir as informações.
* **Verificar conectividade de rede :**
    * Permite testar a conectividade com um host específico usando o comando `ping`.
    * Você pode inserir o endereço IP ou nome do host que deseja testar.
* **Exibir tabela de roteamento ️:**
    * Mostra a tabela de roteamento do seu sistema, que define como os pacotes de rede são encaminhados.
    * Utiliza o comando `netstat -rn` para exibir as informações.
* **Menu Interativo ⌨️:**
    * Oferece um menu simples e intuitivo para navegar pelas funcionalidades do script.
    * Você pode escolher a operação desejada digitando o número correspondente.

## Como Usar

1.  **Salve o script:**
    * Copie o código do script e salve-o em um arquivo com a extensão `.sh` (por exemplo, `rede.sh`).
2.  **Torne o script executável:**
    * Abra o terminal e navegue até o diretório onde você salvou o script.
    * Execute o comando `chmod +x rede.sh` para dar permissão de execução ao script.
3.  **Execute o script:**
    * Execute o script com o comando `./rede.sh`.
4.  **Siga as instruções do menu:**
    * O script exibirá um menu com as opções disponíveis.
    * Digite o número da opção desejada e pressione Enter.
    * Siga as instruções adicionais, se necessário (por exemplo, digitar o host para pingar).

## Requisitos

* Terminal Bash
* Comandos `ifconfig`, `ping` e `netstat` instalados no sistema

## Contribuição

* Contribuições são bem-vindas!
* Sinta-se à vontade para abrir issues e pull requests para melhorias e novas funcionalidades.
* Compartilhe suas ideias!
