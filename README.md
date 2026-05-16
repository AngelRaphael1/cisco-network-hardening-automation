# cisco-network-hardening-automation
Laboratório no Cisco Packet Tracer com foco em segmentação por VLANs, aplicação de ACLs e script em Python 3 para auditoria automatizada de portas.

# 🛡️ De Troubleshooting à Automação: Validando Postura de Segurança com Python

Em segurança de redes, configurar a infraestrutura é apenas parte do processo; validar continuamente as políticas aplicadas é igualmente essencial. Este projeto consiste em um laboratório prático desenvolvido no **Cisco Packet Tracer** focado em segmentação de rede, hardening e automação de validações utilizando **Python 3**.

## 🔹 O Cenário de Infraestrutura
- Implementação de uma topologia de rede segmentada utilizando **VLANs**.
- Configuração e provisionamento de serviços essenciais como **DNS** e **Web Server**.

## 🔹 As Políticas de Defesa (Hardening)
- Aplicação de **Access Control Lists (ACLs)** estruturadas para reduzir a superfície de ataque.
- Bloqueio preventivo de tráfego desnecessário e restrição rígida a protocolos legados ou inseguros.

## 🔹 A Auditoria Automatizada
Para complementar os testes manuais de troubleshooting, desenvolvi um script em **Python 3** capaz de validar automaticamente se as políticas de segurança estão ativas e filtrando corretamente serviços críticos (como tentativas de conexão em portas de gerência como SSH e Telnet).

## 🛠️ Tecnologias e Ferramentas
- **Cisco Packet Tracer:** Simulação e configuração da topologia de rede e ACLs.
- **Python 3 (Sockets/Subprocess):** Lógica de automação para testes de conectividade e validação de regras de firewall.
- **Conceitos de Redes:** VLANs, Roteamento, ACLs estendidas, Protocolos TCP/IP.
