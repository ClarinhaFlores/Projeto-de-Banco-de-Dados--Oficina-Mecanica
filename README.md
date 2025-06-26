# Oficina Mecanica

O seguinte modelo conceitual encontrado no arquivo "Oficina-Mecanica.pdf", demonstra um esquema de um sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica. Nesse modelo temos as seguintes entidades: "OS" abraviação de 'Ordem de Serviço', "Cliente", "Veiculo", "Serviço", "Equipe Mecanica", "Mecanico", "Peca". Seus relacionamentos são:

- "cliente" pode ter 1 ou mais veiculos, e "veiculo" pode pertencer a apenas 1 cliente;
- "veiculo" pode ter 1 ou mais OS, uma "OS" pode ter apenas um veiculo;
- uma "OS" pode ter 1 ou mais serviços sendo efetuados, e um "serviço" pode ser efetuado em 1 ou mais OS;
- uma "OS" pode ser executada por apenas 1 equipe mecina, e uma "equipe mecanica" pode executar apenas 1 OS por vez;
- uma "equipe mecanica" é composta por 1 ou mais mecanicos, e um "mecanico" pode estar em apenas uma equipe mecanica por vez;
- uma "OS" pode precisa de 1 ou mais pecas, e um tipo de "peca" pode ser necessária em 1 ou mais OS
