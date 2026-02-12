Sistema de Contratos de Trabalhador (Worker Contracts)
Este projeto é uma aplicação de console desenvolvida em Java para gerenciar os ganhos de um funcionário com base em seu salário fixo e diversos contratos por hora. O sistema demonstra o uso de composição, onde um objeto possui associações com outros objetos (Trabalhador tem um Departamento e vários Contratos).

🛠️ Funcionalidades
Cadastro de Trabalhador: Registra nome, nível (Junior, Pleno ou Sênior) e salário base.

Gestão de Departamentos: Associa o trabalhador a um setor específico.

Contratos por Hora: Permite adicionar múltiplos contratos, cada um com uma data, valor por hora e duração.

Cálculo de Renda: Calcula o salário total do trabalhador para um mês e ano específicos, somando o salário base aos contratos realizados naquele período.

🏗️ Estrutura do Projeto
O projeto está dividido nos seguintes pacotes:

application: Contém a classe Program com o método main, responsável pela interação com o usuário.

entities: Contém as classes de negócio:

Worker: Classe principal que contém a lógica de cálculo de renda.

Department: Representa o setor do trabalhador.

HourContract: Representa os detalhes de um contrato de serviço.

enums:

WorkerLevel: Enumeração que define os níveis JUNIOR, MID_LEVEL e SENIOR.

🚀 Como Executar
Pré-requisitos
Java JDK 8 ou superior instalado.

Uma IDE (Eclipse, IntelliJ, VS Code) ou terminal.

Passo a Passo
Clone este repositório ou copie os arquivos para sua máquina.

Compile os arquivos .java.

Execute a classe Program.java.

Exemplo de Interação:

Enter department's name: Design
Enter worker data:
Name: Alex
Level: MID_LEVEL
Base salary: 3000.00

How many contracts to this worker? 2
Enter contract #1 data:
Date (DD/MM/YYYY): 20/08/2023
Value per hour: 50.00
Duration (hours): 20

Enter contract #2 data:
Date (DD/MM/YYYY): 15/08/2023
Value per hour: 80.00
Duration (hours): 10

Enter month and year to calculate income (MM/YYYY): 08/2023
Name: Alex
Department: Design
Income for 08/2023: 4800.00

Este é um excelente exemplo de um sistema de composição de objetos em Java, cobrindo conceitos fundamentais como Enumerações, Listas e manipulação de datas.

Aqui está uma proposta de README.md bem estruturado para o seu projeto:

Sistema de Contratos de Trabalhador (Worker Contracts)
Este projeto é uma aplicação de console desenvolvida em Java para gerenciar os ganhos de um funcionário com base em seu salário fixo e diversos contratos por hora. O sistema demonstra o uso de composição, onde um objeto possui associações com outros objetos (Trabalhador tem um Departamento e vários Contratos).

🛠️ Funcionalidades
Cadastro de Trabalhador: Registra nome, nível (Junior, Pleno ou Sênior) e salário base.

Gestão de Departamentos: Associa o trabalhador a um setor específico.

Contratos por Hora: Permite adicionar múltiplos contratos, cada um com uma data, valor por hora e duração.

Cálculo de Renda: Calcula o salário total do trabalhador para um mês e ano específicos, somando o salário base aos contratos realizados naquele período.

🏗️ Estrutura do Projeto
O projeto está dividido nos seguintes pacotes:

application: Contém a classe Program com o método main, responsável pela interação com o usuário.

entities: Contém as classes de negócio:

Worker: Classe principal que contém a lógica de cálculo de renda.

Department: Representa o setor do trabalhador.

HourContract: Representa os detalhes de um contrato de serviço.

enums:

WorkerLevel: Enumeração que define os níveis JUNIOR, MID_LEVEL e SENIOR.

🚀 Como Executar
Pré-requisitos
Java JDK 8 ou superior instalado.

Uma IDE (Eclipse, IntelliJ, VS Code) ou terminal.

Passo a Passo
Clone este repositório ou copie os arquivos para sua máquina.

Compile os arquivos .java.

Execute a classe Program.java.

Exemplo de Interação:

----------------------------------------------------------------------------------------------------------

Plaintext

Enter department's name: Design
Enter worker data:
Name: Alex
Level: MID_LEVEL
Base salary: 3000.00

How many contracts to this worker? 2
Enter contract #1 data:
Date (DD/MM/YYYY): 20/08/2023
Value per hour: 50.00
Duration (hours): 20

Enter contract #2 data:
Date (DD/MM/YYYY): 15/08/2023
Value per hour: 80.00
Duration (hours): 10

Enter month and year to calculate income (MM/YYYY): 08/2023
Name: Alex
Department: Design
Income for 08/2023: 4800.00

----------------------------------------------------------------------------------------------------------

📚 Conceitos Aplicados
Composição de Objetos: A classe Worker possui um Department e uma lista de HourContract.

Enumerações: Uso de enum para tipos fixos de dados.

Manipulação de Datas: Uso de SimpleDateFormat e Calendar para processar e filtrar datas de contratos.

Encapsulamento: Todos os atributos são privados com métodos getter e setter.