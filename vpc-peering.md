O VPC Peering é uma maneira de conectar duas redes virtuais da AWS em uma mesma região. Para estabelecer a conexão, você pode seguir os seguintes passos:

1. Crie as VPCs: Primeiro, crie as duas VPCs que deseja conectar. Certifique-se de que as VPCs não tenham sub-redes sobrepostas, pois isso pode causar conflitos de endereço IP.

2. Crie as regras de rota: Em cada VPC, crie uma regra de rota que aponte para a VPC do outro lado. Para fazer isso, acesse o console do Amazon VPC, selecione a VPC que deseja modificar e adicione uma nova rota. A rota deve apontar para a VPC do outro lado usando o ID da VPC e o ID do Peering Connection.

3. Crie o Peering Connection: Em cada VPC, crie um Peering Connection que aponte para a VPC do outro lado. Certifique-se de que as configurações do Peering Connection correspondam às da outra VPC.

4. Aceite o pedido de conexão: Em cada VPC, aceite o pedido de Peering Connection enviado pela outra VPC. O pedido pode ser encontrado no console do Amazon VPC.

5. Verifique a conectividade: Após estabelecer a conexão, teste a conectividade entre as VPCs para garantir que a comunicação esteja funcionando corretamente.

Lembre-se de que o VPC Peering só pode ser usado para conectar VPCs na mesma região da AWS. Além disso, o Peering Connection é bidirecional, o que significa que a comunicação pode ser iniciada de qualquer VPC conectada.
