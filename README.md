# Projeto - Cisco Packet Tracker

## Introdução

Empresa Fictícia: Tech Solutions.

### Visão Geral do Projeto

Este projeto foi desenvolvido utilizando o Cisco Packet Tracer, um simulador de rede amplamente utilizado para planejamento, configuração e teste de redes. A Tech Solutions, uma empresa fictícia, está em processo de expansão e reestruturação de sua infraestrutura de rede. Para atender às demandas crescentes de conectividade e garantir um desempenho eficiente, a rede da empresa foi dividida em três sub-redes distintas: LAN 1, LAN 2 e LAN 3.

### Objetivos do Projeto

1. Segurança e Isolamento: Garantir que cada departamento da empresa tenha uma sub-rede isolada, aumentando a segurança e reduzindo o risco de acessos não autorizados.
2. Desempenho e Eficiência: Otimizar o desempenho da rede, minimizando congestionamentos e melhorando a gestão do tráfego de dados.
3. Escalabilidade: Permitir a expansão futura da rede sem a necessidade de reconfigurações significativas.
4. Facilidade de Gerenciamento: Simplificar o gerenciamento da rede, facilitando a resolução de problemas e a implementação de políticas de rede.

## Divisão das Sub-redes

### LAN 1

- Endereço de Rede: 192.168.255.0 / 24
- Máscara de Sub-rede: 255.255.255.0
- Quantidade de Hosts Válidos: 254
- Endereço do Prefixo da Sub-rede: 192.168.255.0
- Uso: Designada para o departamento administrativo, esta sub-rede suporta os servidores internos, estações de trabalho dos gerentes e sistemas de gerenciamento de documentos.

### LAN 2

- Endereço de Rede: 172.16.0.0 / 16
- Máscara de Sub-rede: 255.255.0.0
- Quantidade de Hosts Válidos: 65534
- Endereço do Prefixo da Sub-rede: 172.16.0.0
- Uso: Utilizada pelo departamento de desenvolvimento, inclui servidores de desenvolvimento, estações de trabalho dos desenvolvedores e recursos de controle de versão.

### LAN 3

- Endereço de Rede: 200.100.100.0 / 24
- Máscara de Sub-rede: 255.255.255.0
- Quantidade de Hosts Válidos: 254
- Endereço do Prefixo da Sub-rede: 200.100.100.0
- Uso: Destinada ao departamento de vendas e suporte ao cliente, esta sub-rede abriga os servidores de CRM, estações de trabalho dos agentes de vendas e suporte e o sistema de telefonia IP.

## Tecnologias e Equipamentos

Para a construção da infraestrutura de rede da Tech Solutions, foram utilizadas diversas tecnologias e equipamentos que garantem uma conectividade eficiente e segura.

### Swicthes Gerenciáveis

Utilizados para conectar dispositivos dentro das sub-redes e fornecer capacidade de configuração avançada para otimização do tráfego e segmentação de rede por meio de VLANs (Virtual Local Area Networks).

### Roteadores

Responsáveis por interconectar as sub-redes e permitir a comunicação entre elas, além de fornecer acesso à Internet e outras redes externas. Os roteadores também implementam políticas de segurança como firewalls e filtragem de pacotes.

### Firewalls

Integrados ou dedicados, os firewalls protegem a rede contra ameaças externas, controlando o tráfego de entrada e saída com base em políticas de segurança definidas.

### Access Points (APs)

Dispositivos para fornecer conectividade sem fio, permitindo que dispositivos móveis e sem fio acessem a rede de forma segura e eficiente.

### Servidores de Rede

Incluem servidores de arquivos, servidores de impressão, servidores de e-mail e outros serviços essenciais para a operação da empresa. Estes servidores são distribuídos conforme a necessidade de cada sub-rede.

### Sistemas de Gerenciamento de Rede

Ferramentas e software utilizados para monitorar, gerenciar e solucionar problemas na rede, garantindo disponibilidade e desempenho contínuos.

### VLANs (Virtual Local Area Networks)

Implementadas para segmentar a rede fisicamente em sub-redes lógicas, aumentando a segurança e eficiência do tráfego de rede.

## Plano de Implementação

- Planejamento e Design: Detalhamento das necessidades da empresa, mapeamento das sub-redes e definição das políticas de segurança.
- Configuração dos Equipamentos: Programação dos switches e roteadores, criação das VLANs e configuração dos endereçamentos IP.
- Teste e Validação: Verificação da conectividade entre dispositivos, testes de desempenho e ajustes de configuração conforme necessário.
- Documentação e Treinamento: Criação de documentação detalhada da rede e treinamento da equipe de TI para gerenciamento e manutenção.

## Conclusão

Este projeto visa proporcionar à Tech Solutions uma infraestrutura de rede robusta, segura e eficiente, alinhada com as melhores práticas de engenharia de redes. Através da segmentação em sub-redes, a empresa poderá desfrutar de um ambiente de TI otimizado, capaz 
de suportar suas operações atuais e futuras expansões.
