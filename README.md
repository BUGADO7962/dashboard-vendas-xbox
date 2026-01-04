# dashboard-vendas-xbox
Dashboard de vendas desenvolvido em Excel

Xbox Dashboard
Este projeto é uma análise de vendas de assinaturas do Xbox Game Pass, com base em dados simulados de usuários e planos. O objetivo é fornecer insights sobre o desempenho das assinaturas por tipo de plano, período, e características dos clientes.

📊 Dados Utilizados
O arquivo Excel xbox_desafio.xlsx contém as seguintes abas:

1. A̳ssets
Paleta de cores utilizada no projeto (#9BC848, #22C55E, #2AE6B1, #5BF6A8, #E8E6E9).

Referências visuais para logos e ícones.

2. B̳ases
Tabela principal com dados de assinaturas.

Colunas:

Subscriber ID

Name

Plan (Core, Standard, Ultimate)

Start Date

Auto Renewal (Sim/Não)

Subscription Price

Subscription Type (Mensal, Trimestral, Anual)

EA Play Season Pass (Sim/Não)

EA Play Season Pass Price

Minecraft Season Pass (Sim/Não)

Minecraft Season Pass Price

Coupon Value

Total Value

3. Detalhes1
Filtro avançado com dados de:

Auto Renewal = No

Subscription Type = Quarterly

Mostra o cálculo de Total Value para esses casos.

4. C̳álculos
Pivot tables e cálculos agregados:

Soma de Total Value por Auto Renewal.

Soma de EA Play Season Pass Price por plano.

Soma de Minecraft Season Pass Price por plano.

Soma de Total Value por mês para usuários com ambos passes ativos.

Fórmulas utilizadas:

=GETPIVOTDATA(...) para extrair dados das tabelas dinâmicas.

5. D̳ashboard
Painel de controle com:

Título: XBOX GAME PASS SUBSCRIPTIONS SALES

Saudação personalizada: Bem vindo, Diego!

🚀 Como Reproduzir o Projeto
1. Abrir o arquivo
Use Microsoft Excel ou Google Sheets (com adaptações para fórmulas do Excel).

2. Explorar os dados
Navegue pelas abas para entender a estrutura.

A aba B̳ases contém a fonte de dados principal.

3. Analisar os cálculos
A aba C̳álculos contém tabelas dinâmicas que resumem:

Valores por renovação automática.

Preços dos passes por plano.

Valores totais por mês.

4. Visualizar o Dashboard
A aba D̳ashboard é a interface principal.

Pode ser estendida com gráficos e KPIs.

5. Adaptar para suas necessidades
Filtre os dados na aba B̳ases.

Atualize as tabelas dinâmicas em C̳álculos.

Personalize o Dashboard com novas métricas.

🛠️ Ferramentas Sugeridas
Microsoft Excel (com suporte a tabelas dinâmicas e GETPIVOTDATA)

Power BI (para versão mais interativa)

Google Sheets (com adaptações)

📌 Observações
Os dados são fictícios e para fins educacionais.

As fórmulas em C̳álculos dependem da estrutura atual das tabelas dinâmicas.

O dashboard pode ser expandido com gráficos e mais KPIs.

Desenvolvido por: Erick Adriano de Oliveira
📅 2025 – Projeto de Análise de Dados – Xbox Game Pass
