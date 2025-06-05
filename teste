#include <stdio.h> // Inclui a biblioteca padrão de entrada e saída para funções como printf e scanf

int main() {
    // --- Declaração de variáveis para a Carta 1 ---
    char estado1;
    char codigo1[5]; // 4 caracteres para o código (ex: A01) + 1 para o terminador nulo '\0'
    char nomeCidade1[50]; // Suporta nomes de cidades de até 49 caracteres + terminador nulo
    int populacao1;
    float area1;
    float pib1;
    int pontosTuristicos1;
    float densidadePopulacional1; // Nova variável para a densidade populacional da Carta 1
    float pibPerCapita1;         // Nova variável para o PIB per capita da Carta 1

    // --- Declaração de variáveis para a Carta 2 ---
    char estado2;
    char codigo2[5];
    char nomeCidade2[50];
    int populacao2;
    float area2;
    float pib2;
    int pontosTuristicos2;
    float densidadePopulacional2; // Nova variável para a densidade populacional da Carta 2
    float pibPerCapita2;         // Nova variável para o PIB per capita da Carta 2

    // --- Coleta de dados para a Carta 1 ---
    printf("--- Inserir dados para a Carta 1 ---\n");

    printf("Estado (A-H): ");
    scanf(" %c", &estado1); // O espaço antes de %c é importante para consumir qualquer caractere de nova linha pendente

    printf("Codigo da Carta (ex: A01): ");
    scanf("%s", codigo1); // %s lê uma string até encontrar um espaço em branco

    printf("Nome da Cidade: ");
    scanf(" %[^\n]", nomeCidade1); // %[^\n] lê a linha inteira até a quebra de linha, incluindo espaços

    printf("Populacao: ");
    scanf("%d", &populacao1);

    printf("Area (em km^2): ");
    scanf("%f", &area1);

    printf("PIB (em bilhoes de reais): ");
    scanf("%f", &pib1);

    printf("Numero de Pontos Turisticos: ");
    scanf("%d", &pontosTuristicos1);

    // --- Calculos para a Carta 1 ---
    // É importante verificar se 'area1' ou 'populacao1' são zero para evitar divisão por zero,
    // mas como não podemos usar 'if/else', assumimos valores válidos conforme as simplificações.
    densidadePopulacional1 = (float)populacao1 / area1;
    pibPerCapita1 = (pib1 * 1000000000.0) / populacao1; // Multiplica o PIB por 1 bilhão para ter o valor total antes da divisão

    printf("\n"); // Adiciona uma linha em branco para melhor legibilidade entre as entradas das cartas

    // --- Coleta de dados para a Carta 2 ---
    printf("--- Inserir dados para a Carta 2 ---\n");

    printf("Estado (A-H): ");
    scanf(" %c", &estado2);

    printf("Codigo da Carta (ex: A01): ");
    scanf("%s", codigo2);

    printf("Nome da Cidade: ");
    scanf(" %[^\n]", nomeCidade2);

    printf("Populacao: ");
    scanf("%d", &populacao2);

    printf("Area (em km^2): ");
    scanf("%f", &area2);

    printf("PIB (em bilhoes de reais): ");
    scanf("%f", &pib2);

    printf("Numero de Pontos Turisticos: ");
    scanf("%d", &pontosTuristicos2);

    // --- Calculos para a Carta 2 ---
    densidadePopulacional2 = (float)populacao2 / area2;
    pibPerCapita2 = (pib2 * 1000000000.0) / populacao2; // Multiplica o PIB por 1 bilhão para ter o valor total antes da divisão

    printf("\n"); // Adiciona uma linha em branco antes de exibir os resultados

    // --- Exibição dos dados da Carta 1 ---
    printf("--- Carta 1 ---\n");
    printf("Estado: %c\n", estado1);
    printf("Codigo: %s\n", codigo1);
    printf("Nome da Cidade: %s\n", nomeCidade1);
    printf("Populacao: %d\n", populacao1);
    printf("Area: %.2f km^2\n", area1); // %.2f formata o float com duas casas decimais
    printf("PIB: %.2f bilhoes de reais\n", pib1);
    printf("Numero de Pontos Turisticos: %d\n", pontosTuristicos1);
    printf("Densidade Populacional: %.2f hab/km^2\n", densidadePopulacional1);
    printf("PIB per Capita: %.2f reais\n", pibPerCapita1);

    printf("\n"); // Adiciona uma linha em branco para separar a exibição das cartas

    // --- Exibição dos dados da Carta 2 ---
    printf("--- Carta 2 ---\n");
    printf("Estado: %c\n", estado2);
    printf("Codigo: %s\n", codigo2);
    printf("Nome da Cidade: %s\n", nomeCidade2);
    printf("Populacao: %d\n", populacao2);
    printf("Area: %.2f km^2\n", area2);
    printf("PIB: %.2f bilhoes de reais\n", pib2);
    printf("Numero de Pontos Turisticos: %d\n", pontosTuristicos2);
    printf("Densidade Populacional: %.2f hab/km^2\n", densidadePopulacional2);
    printf("PIB per Capita: %.2f reais\n", pibPerCapita2);

    return 0; // Indica que o programa foi executado com sucesso
}
