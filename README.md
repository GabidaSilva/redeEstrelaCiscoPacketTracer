# Projeto: Configuração de Rede Estrela para Comunicação da Equipe de Produção

## Descrição do Projeto
Este projeto tem como objetivo configurar uma topologia de rede estrela utilizando o **Cisco Packet Tracer** para conectar os membros da equipe de produção de um show. A rede permite que os membros se comuniquem facilmente através de seus computadores conectados a um switch central.

---

## Configuração da Rede

### Topologia Utilizada
- **Modelo:** Rede estrela
- **Dispositivos:**
  - 1 Switch (modelo 2960)
  - 4 Computadores (PCs)
- **Conexões:** Cabos Ethernet (Copper Straight-Through)

### Endereços IP Configurados
Cada PC foi configurado com um endereço IP da mesma sub-rede:
- **PC0:** `192.168.1.2`
- **PC1:** `192.168.1.3`
- **PC2:** `192.168.1.4`
- **PC3:** `192.168.1.5`
- **Máscara de Sub-rede:** `255.255.255.0`

---

## Testes de Conectividade
Os testes de comunicação entre os PCs foram realizados com o comando **ping**. Abaixo estão os resultados obtidos:

### Comandos Executados
- `ping 192.168.1.3`
- `ping 192.168.1.4`
- `ping 192.168.1.5`

### Resultados
Todos os testes de conectividade foram **bem-sucedidos**, indicando que:
1. Os dispositivos estão conectados corretamente.
2. O switch está funcionando como esperado.
3. Todos os dispositivos estão na mesma sub-rede.

---

## Como Abrir o Projeto
1. Baixe o arquivo `rede_estrela.pkt` (disponível neste repositório).
2. Abra o arquivo no **Cisco Packet Tracer** (versão 8.2 ou superior).
3. Visualize a topologia e teste os dispositivos, se necessário.

---

## Estrutura do Repositório
- `rede_estrela.pkt`: Arquivo da topologia criada no Cisco Packet Tracer.
- `screenshots/`: Pasta contendo prints da topologia e dos testes realizados.
- `README.md`: Documento com informações sobre o projeto.

---

## Sobre o Projeto
Este projeto foi desenvolvido para modernizar a comunicação da equipe de produção do show da banda de Miguel, garantindo uma infraestrutura de rede eficiente e funcional.

---

## Autor
Gabriela

Se tiver sugestões ou melhorias, fique à vontade para abrir uma issue ou enviar um pull request!

