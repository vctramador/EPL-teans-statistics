# EPL-teans-statistics

```markdown
# Analysis of the 2023-24 Premier League Season

This repository contains an analysis of the 2023-24 Premier League season, using a dataset available on Kaggle. The analysis was conducted using the pandas library for data manipulation and matplotlib for data visualization.

## Dataset

The dataset contains information about Premier League matches, including:

- Squad: Team name
- home_MP: Home matches played
- home_W: Home wins
- home_D: Home draws
- home_L: Home losses
- home_GF: Home goals scored
- home_GA: Home goals conceded
- home_GD: Home goal difference
- home_Pts: Home points
- home_Pts/MP: Home points per match
- away_MP: Away matches played
- away_W: Away wins
- away_D: Away draws
- away_L: Away losses
- away_GF: Away goals scored
- away_GA: Away goals conceded
- away_GD: Away goal difference
- away_Pts: Away points
- away_Pts/MP: Away points per match
- away_xG: Expected goals away
- away_xGA: Expected goals against away
- away_xGD: Expected goal difference away
- away_xGD/90: Expected goal difference per 90 minutes away

## Analyses Conducted

### 1. Home vs Away Performance

We compared the teams' performance in terms of points per game at home and away.

![Pts/MP Home vs Away](images/Pts_MP_Home_Away.png)

### 2. Best Defense and Best Attack

We identified the teams with the best defense (fewest goals conceded) and the best attack (most goals scored), both at home and away.

#### Best Attack at Home
![Top 10 Best Attacks at Home](images/Top_Attacks_Home.png)

#### Best Attack Away
![Top 10 Best Attacks Away](images/Top_Attacks_Away.png)

#### Best Defense at Home
![Top 10 Best Defenses at Home](images/Top_Defenses_Home.png)

#### Best Defense Away
![Top 10 Best Defenses Away](images/Top_Defenses_Away.png)

### 3. Frequencies of Wins, Draws, and Losses

We analyzed the frequencies of wins, draws, and losses at home and away to see if there are any interesting patterns.

#### Home: Wins, Draws, and Losses per Team
![Home: Wins, Draws, and Losses per Team](images/Wins_Draws_Losses_Home.png)

#### Away: Wins, Draws, and Losses per Team
![Away: Wins, Draws, and Losses per Team](images/Wins_Draws_Losses_Away.png)

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/vctramador/EPL-teans-statistics.git
   ```
2. Navigate to the project directory:
   ```bash
   cd EPL-teans-statistics
   ```
3. Install the dependencies:
   ```bash
   pip install pandas matplotlib
   ```
4. Run the analysis script:
   ```bash
   python Premier-League.ipynb
   ```

## Contributions

Contributions are welcome! Feel free to open issues and submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```


# Portugês 

```markdown
# Análise da Temporada 2023-24 da Premier League

Este repositório contém uma análise da temporada 2023-24 da Premier League, usando um dataset disponível no Kaggle. A análise foi realizada utilizando a biblioteca pandas para manipulação de dados e matplotlib para visualização dos dados.

## Dataset

O dataset contém informações sobre os jogos da Premier League, incluindo:

- Squad: Nome do time
- home_MP: Jogos em casa
- home_W: Vitórias em casa
- home_D: Empates em casa
- home_L: Derrotas em casa
- home_GF: Gols marcados em casa
- home_GA: Gols sofridos em casa
- home_GD: Saldo de gols em casa
- home_Pts: Pontos em casa
- home_Pts/MP: Pontos por jogo em casa
- away_MP: Jogos fora de casa
- away_W: Vitórias fora de casa
- away_D: Empates fora de casa
- away_L: Derrotas fora de casa
- away_GF: Gols marcados fora de casa
- away_GA: Gols sofridos fora de casa
- away_GD: Saldo de gols fora de casa
- away_Pts: Pontos fora de casa
- away_Pts/MP: Pontos por jogo fora de casa
- away_xG: Expected goals fora de casa
- away_xGA: Expected goals contra fora de casa
- away_xGD: Saldo de expected goals fora de casa
- away_xGD/90: Saldo de expected goals por 90 minutos fora de casa

## Análises Realizadas

### 1. Desempenho em Casa vs Fora de Casa

Comparamos o desempenho dos times em termos de pontos por jogo em casa e fora.

![Pts/MP em Casa vs Fora de Casa](images/Pts_MP_Home_Away.png)

### 2. Melhor Defesa e Melhor Ataque

Identificamos os times com a melhor defesa (menos gols sofridos) e o melhor ataque (mais gols marcados), tanto em casa quanto fora.

#### Melhor Ataque em Casa
![Top 10 Best Attacks at Home](images/Top_Attacks_Home.png)

#### Melhor Ataque Fora
![Top 10 Best Attacks Away](images/Top_Attacks_Away.png)

#### Melhor Defesa em Casa
![Top 10 Best Defenses at Home](images/Top_Defenses_Home.png)

#### Melhor Defesa Fora
![Top 10 Best Defenses Away](images/Top_Defenses_Away.png)

### 3. Frequências de Vitórias, Empates e Derrotas

Analisamos as frequências de vitórias, empates e derrotas em casa e fora, para ver se existem padrões interessantes.

#### Vitórias, Empates e Derrotas em Casa
![Home: Wins, Draws, and Losses per Team](images/Wins_Draws_Losses_Home.png)

#### Vitórias, Empates e Derrotas Fora
![Away: Wins, Draws, and Losses per Team](images/Wins_Draws_Losses_Away.png)

## Como Utilizar

1. Clone este repositório:
   ```bash
   git clone https://github.com/vctramador/EPL-teans-statistics.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd EPL-teans-statistics
   ```
3. Instale as dependências:
   ```bash
   pip install pandas matplotlib
   ```
4. Execute o script de análise:
   ```bash
   python Premier-League.ipynb
   ```

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.
