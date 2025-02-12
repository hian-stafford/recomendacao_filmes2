# MovieLens Similarity Analysis

Este projeto utiliza o dataset MovieLens para analisar a similaridade entre filmes com base nas avaliações dos usuários. O objetivo é demonstrar como utilizar correlação estatística para encontrar recomendações de filmes semelhantes.

## Tecnologias Utilizadas
- **Pandas**: Para manipulação de dados e criação de tabelas dinâmicas.
- **NumPy**: Para cálculos estatísticos.

## Metodologia
1. **Carregamento dos Dados**: O dataset MovieLens é lido e as informações de filmes e avaliações são combinadas.
2. **Criação da Matriz Usuário-Filme**: Utilizando `pivot_table`, organizamos as avaliações dos filmes por usuário.
3. **Cálculo da Correlação**: Usamos `corrwith` para determinar a similaridade entre um filme escolhido e os demais.
4. **Filtragem de Resultados**: Para evitar ruído estatístico, removemos filmes com poucas avaliações.
5. **Classificação por Similaridade**: Os filmes são ordenados com base na correlação com o filme-alvo.

## Aplicação em Projetos Reais
Este método pode ser usado para:
- **Sistemas de Recomendação**: Criar sugestões personalizadas para usuários.
- **Análise de Preferências**: Identificar padrões de gosto em bases de clientes.
- **Otimização de Catálogos**: Melhorar a exibição de conteúdos com base em tendências de usuários.

A abordagem utilizada permite uma implementação eficiente de recomendação de filmes, mas pode ser expandida para outros domínios como e-commerce e streaming.
