
# ResumoLabAzure

## Resumo dos Aprendizados sobre Localização de Serviços no Azure

Durante a aula, foi possível explorar na prática a vasta gama de serviços oferecidos na nuvem Azure. Compreendi a importância crucial que a nuvem desempenha no cenário de TI atual, mostrando-se uma habilidade indispensável para qualquer profissional da área.

O Azure permite não apenas a localização estratégica de serviços em diferentes regiões geográficas, mas também otimiza o desempenho, a disponibilidade e a conformidade com requisitos legais e de segurança específicos de cada região. A habilidade de gerenciar serviços na nuvem é cada vez mais valorizada no mercado de trabalho, tornando-se uma competência essencial no mundo tecnológico de hoje.

# Microsoft Azure — Tópicos Aprendidos

Este documento resume os principais conceitos aprendidos para a certificação Azure Fundamentals (AZ-900), com foco nos modelos de serviços em nuvem, data centers e estruturas de custo.

## Data Centers: Físico para Virtualização
O Azure utiliza data centers para fornecer serviços em nuvem virtualizados, garantindo uma infraestrutura escalável e flexível para as empresas.

## Modelos de Nuvem

### Nuvem Privada
- Acesso exclusivo a uma única organização.
- A empresa cria e mantém um ambiente de nuvem dentro de seu próprio data center.

### Nuvem Pública
- Pertencente a um provedor de serviços de nuvem ou hospedagem.
- Oferece recursos e serviços para múltiplas organizações e usuários.
- Acessada de forma segura, geralmente pela internet.

### Nuvem Híbrida
- Combina nuvens públicas e privadas para otimizar a execução de aplicativos.
- Oferece flexibilidade para escolher onde os aplicativos serão executados, dependendo das necessidades.

---

## Comparação de Modelos

### Nuvem Pública
- Sem despesas de capital (CapEx) para escalonamento vertical.
- Aplicativos podem ser provisionados ou desprovisionados rapidamente.
- As organizações pagam apenas pelos recursos utilizados.

### Nuvem Privada
- Controle total da organização sobre os recursos e a segurança.
- A organização é responsável pela manutenção e atualização de hardware.

### Nuvem Híbrida
- Flexibilidade para decidir onde os aplicativos serão executados.
- Controle sobre segurança, conformidade e requisitos legais.
- Oferece a maior flexibilidade entre os modelos.

---

## Comparação CapEx e OpEx

### Despesas de Capital (CapEx)
- Gasto inicial em infraestrutura física.
- O valor das despesas de CapEx diminui com o tempo.

### Despesas Operacionais (OpEx)
- Pagamento por produtos e serviços conforme necessário.
- Cobrança imediata com base no uso.

### Modelo Baseado em Consumo
- Pagamento apenas pelos recursos utilizados.
- Permite melhor previsão de custos.
- Cobrança é feita com base no uso real dos serviços.


# Azure - Benefícios

## Alta Disponibilidade
A alta disponibilidade se concentra em garantir o máximo de tempo de operação para os serviços, independentemente de interrupções ou eventos que possam ocorrer. Isso é feito através de redundâncias, failovers e acordos de nível de serviço (SLA).

## Escalabilidade
A escalabilidade refere-se à capacidade de ajustar os recursos para atender à demanda. 
- Quando a demanda aumenta, mais recursos podem ser adicionados para manter o desempenho.
- Quando a demanda cai, os recursos podem ser reduzidos, otimizando custos.
- Em ambientes de nuvem, como no Azure, você paga apenas pelos recursos que utiliza.

## Elasticidade
A elasticidade permite que os recursos computacionais sejam ajustados automaticamente conforme a demanda de um sistema ou aplicação. 
- Se a carga de trabalho aumenta, mais recursos são provisionados.
- Quando a carga diminui, os recursos são reduzidos para evitar desperdícios.
- A elasticidade maximiza a eficiência e garante que as organizações paguem apenas pelos recursos utilizados em tempo real.

## Confiabilidade
A confiabilidade se refere à capacidade dos serviços de nuvem de operar de maneira consistente e previsível, garantindo que as aplicações e sistemas estejam sempre disponíveis e funcionais. 
- Inclui alta disponibilidade, recuperação de desastres e redundância de dados.
- Provedores como o Azure utilizam replicação de dados, balanceamento de carga e backups automáticos para garantir a continuidade dos serviços.

## Previsibilidade
A previsibilidade em nuvem permite que as organizações antecipem o comportamento do sistema em termos de desempenho, custo e disponibilidade. 
- Ferramentas de monitoramento e escalabilidade automática garantem um controle mais preciso.
- Com SLAs e monitoramento em tempo real, as empresas podem prever e controlar melhor seus recursos e custos.

## Segurança
A segurança em nuvem abrange políticas, controles e práticas para proteger dados, aplicativos e infraestrutura.
- Inclui proteção contra ameaças, controle de acesso, criptografia e conformidade com regulamentos.
- Provedores como o Azure oferecem ferramentas como firewalls, detecção de intrusão, criptografia e autenticação multifator (MFA).
- A segurança envolve responsabilidade compartilhada: o provedor protege a infraestrutura e o cliente gerencia a segurança de seus dados.

## Governança
Governança em nuvem envolve políticas e processos para garantir a gestão eficiente dos recursos de TI.
- Controla o uso, segurança e conformidade dos recursos.
- Ferramentas como o **Azure Policy** permitem criar e aplicar regras, enquanto o **Azure Cost Management** monitora e controla os custos.
- Uma boa governança garante conformidade, otimização de custos e segurança.

## Gerenciabilidade
A gerenciabilidade refere-se à capacidade de monitorar, controlar e otimizar os recursos e serviços em nuvem.
- Ferramentas como o **Azure Monitor** oferecem visibilidade do desempenho dos serviços, enquanto o **Azure Automation** automatiza tarefas de gerenciamento.
- Permite escalabilidade automática, aplicação de atualizações e monitoramento de uso e desempenho em tempo real.
- Uma boa gerenciabilidade garante eficiência, minimiza o tempo de inatividade e otimiza os custos.


# Criação de Máquina Virtual Windows Server no Azure

A criação de uma máquina virtual (VM) com Windows Server e banco de dados no Azure é um processo simplificado que oferece alta flexibilidade e escalabilidade. O Azure fornece um assistente intuitivo para configurar e implantar a VM. Os principais passos incluem:

1. **Seleção da Imagem**: Escolha a imagem do Windows Server e, se necessário, um banco de dados (como SQL Server) integrado.
2. **Configuração da VM**: Defina os recursos, como o tamanho da máquina (CPU, memória), disco e rede. 
3. **Autenticação**: Configure as credenciais de administrador (senha ou chave SSH) para acessar a máquina.
4. **Monitoramento e Gerenciamento**: Após a implantação, você pode gerenciar a VM pelo portal do Azure, ajustando recursos conforme necessário.

Esse processo permite criar um ambiente de servidor rapidamente, sem a necessidade de gerenciar hardware físico.

## Calculadora de Preço no Azure

A **Calculadora de Preço do Azure** permite estimar os custos dos serviços que você planeja usar. Ela ajuda a calcular o preço de VMs, armazenamento, redes e outros serviços, com base em configurações personalizadas. Você pode:

- **Escolher os serviços** que deseja utilizar (ex: VM com Windows Server).
- **Ajustar os recursos** como CPU, memória, tipo de disco e localização geográfica.
- **Obter uma previsão** detalhada do custo mensal, considerando as opções de escalabilidade e uso.

Essa ferramenta facilita o planejamento financeiro para a implementação de soluções no Azure, ajudando a otimizar custos.
