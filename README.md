# RedeLab

Plataforma interativa para aprender redes de computadores do básico ao avançado — com simuladores reais, não só texto.

**Acesse:** https://xmatheuscoelhox.github.io/redelab/

## O que tem

- **15 módulos**, do básico ao avançado: internet, modelo OSI/TCP-IP, IPv4/IPv6, MAC/Ethernet, topologias, cabeamento, equipamentos, protocolos e portas, DNS/DHCP/NAT, roteamento e switching, segurança, redes sem fio e tópicos avançados — mais glossário.
- **Calculadora de sub-rede** funcional (rede, broadcast, faixa de hosts, decomposição em binário).
- **Laboratório de rede integrado**: uma topologia real (PCs em VLANs, switch, roteador com DHCP/NAT, internet) com 6 cenários animados — DHCP, ARP, NAT, VLAN e roteamento entre VLANs — com log técnico e tabelas MAC/ARP/NAT ao vivo.
- **Simuladores de segurança**: testador de regras de firewall (ACL avaliada em ordem) e demonstração de ARP spoofing / Man-in-the-Middle.
- **Simuladores de Wi-Fi**: sobreposição de canais 2,4GHz e o passo a passo de conexão/handshake (WPA2/WPA3).
- Animações de encapsulamento OSI, three-way handshake TCP, resolução DNS e DORA do DHCP.
- Quizzes por módulo com progresso salvo no navegador (localStorage).

## Como rodar localmente

É uma página estática, sem build nem dependências:

```bash
git clone https://github.com/XMatheusCoelhoX/redelab.git
cd redelab
```

Depois é só abrir `index.html` no navegador.
