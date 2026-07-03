# Arquitetura em Alto Nível

O FeCarlos - Concilia foi estruturado em camadas para separar interface, processamento fiscal e persistência.

## Entrada de Dados

O usuário importa relatórios fiscais obtidos em sistemas externos, como Portal Nacional, Prefeitura e Livro Fiscal Omega.

## Normalização

Os arquivos são convertidos para um formato interno padronizado, permitindo comparar informações mesmo quando os layouts de origem são diferentes.

## Processamento

O motor de conciliação classifica as notas em grupos operacionais, como encontradas, ausentes, divergentes, canceladas ou pendentes de apuração.

## Visualização

O frontend apresenta dashboards, tabelas, filtros e indicadores para apoiar a tomada de decisão.

## Exportação

As análises podem ser transformadas em relatórios Excel ou PDF para conferência, documentação e envio a terceiros.
