# resumo_lab_8
Resumo de aprendizagem do Lab 8: Gerenciamento de Custos no Azure (módulo 3)
## Bootcamp DIO Microsoft Azure Essentials AZ-900
Lab 8 : Gerenciamento de custos no Azure: Calculadora do TCO, Calculadora de preços, Gerenciamento de Custos, Marcas/Tags no Portal Azure

Calculadora do TCO - Custo Total de Propriedade - estimar a economia de custos gerada pela migração de cargas de trabalho para o Azure em 3 passos, com comparativo de custos:
- Definir suas cargas de trabalho - servidores, BD, armazenamento e rede.
- Ajustar suposições - cobertura de software (benefício híbrido com descontos, quando não precisa adquirir uma nova licença).
- Exibir relatórios - conforme as definições de opções de recursos e cenário: em que período (3 anos), em que região (East US), recomendações custo total local e custo total Azure.

Calculadora de preço - simular e validar os custos de produtos e serviços no ambiente virtual da nuvem. 
  - Opções: redes, armazenamento, Web, VMs, BD
- Simulações: MESMA MÁQUINA, EM CONDIÇÕES DIFERENTES. Existem estratégias que precisam ser exploradas para se ter o melor da nuvem. Simular todos os recursos possíveis no ambiente.
  - 1º teste pagar conforme o uso, inclui uma nova licença na região East US, sistema operacional Windwons, camada padrão, manter instância, suporte incluso. Preço estimado US$ 137,24;
  - 2º teste mesma máquina usar o benefício hídrido (40% desconto), preço estimado US$ 70,00.
  - 3º teste pagar na frente, fazer um plano de reserva de 3 anos. Preço estimado US$ 47,90.
  - 4º teste máquina teste, pagar conforme o uso, limitar tempo de uso para 26 dias úteis/mês por 12hs (312hs úteis/mês). Preço estimado US$ 29,95.
  - Relatório que permite download para personalizar dashboard e apresentar para o cliente com as informações da sua empresa.

Gerenciamento de Custos no Azure (Cost Management My Bill) - Ferramenta de monitoramento, controle e acompanhamento dos custos. Pode-se gerar alertas de custos, enviar um e-mail quando exceder o limite, Budget determinado, como uma condicionante. recomendações do Advisor, traz sugestões de melhorias associadas aos custos, indicações de estratégias. Validar custos.

Marcas /Tags - dupla chave 'nome-valor" permite identificar o departamento ou projeto de determinado recurso. Não exige associar e os recursos relacionados não herdam a Tag. Ele não é atribuído automaticamente. Fazer atriuição pela Policy para criar uma condição na Tag. Permite identificar origem nos relatórios de cobrança.

Gerenciar custos por meio de ferramentas disponíveis para administrar os custos e recursos no portal Azure.
