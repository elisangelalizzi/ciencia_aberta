# Tutorial dashboard AEROBICOVID para Jornada da Ciencia Aberta- 2025

## 📊 Sobre o Projeto

Este repositório contém um dashboard interativo desenvolvido em R Markdown para visualização e análise de dados do projeto AEROBICOVID, uma pesquisa sobre capacidade aeróbica e COVID-19 desenvolvida pelo GEEPESC-EEFERP-USP.
Esse tutorial foi ensinado na Jornada da Ciencia Aberta -2025, na Universidade de São Paulo na EEFERP, como parte do conteúdo da Estatística Software Relicável, ministrado por mim e pelo Prof. Dr. Edson Zangiacomi Martinez.
O dashboard permite:
- Visualização dinâmica dos dados
- Análises estatísticas descritivas e gráficos.
- Modelagem de VO2 relativo por classificação de gravidade e outras variáveis.
- Exportação de resultados

## 🛠 Tecnologias Utilizadas

- **R** (versão 4.3.0 ou superior)
- **RStudio** (recomendado)
- Pacotes R:
  - `flexdashboard`
  - `tidyverse` (ggplot2, dplyr, etc.)
  - `plotly`
  - `gt`
  - `DT`
  - `broom`

## 📥 Instalação

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/dashboard-aerobicovid.git
```

2. Abra o arquivo `Dashboard_AEROBICOVID.Rmd` no RStudio

3. Instale as dependências necessárias:
```r
install.packages(c("flexdashboard", "tidyverse", "plotly", "gt", "DT", "broom"))
```

4. Execute o dashboard clicando no botão "Knit" no RStudio

## 🏗 Estrutura do Projeto

```
dashboard-aerobicovid/
├── Dashboard_AEROBICOVID.Rmd  # Código fonte do dashboard
├── Dados.csv                  # Conjunto de dados (exemplo)
├── README.md                  # Este arquivo
└── img/                       # Pasta para imagens (opcional)
```

## 📈 Funcionalidades Principais

1. **Visualização de dados**:
   - Gráficos interativos de distribuição
   - Tabelas dinâmicas
   - Medidores visuais

2. **Análise estatística**:
   - Correlações entre variáveis
   - Modelo linear generalizado
   - Análise de resíduos

3. **Exportação**:
   - Dados completos em tabela interativa
   - Resultados de modelos formatados

## 🤝 Como Contribuir

Contribuições são bem-vindas! Siga estes passos:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/incrivel`)
3. Commit suas mudanças (`git commit -m 'Adiciona feature incrível'`)
4. Push para a branch (`git push origin feature/incrivel`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## ✉ Contato

Profa. Dra. Elisangela Lizzi  
Universidade Tecnológica Federal do Paraná (UTFPR)
Cientista de dados de saúde
elisangelalizzi@gmail.com

---

<div align="center">
  <sub>Criado com ❤ por <a href="https://github.com/elisangelalizzi">Elisangela Lizzi</a></sub>
</div>



---

### 📋 Notas Adicionais

1. Certifique-se de ter o R e RStudio instalados
2. O arquivo `Dados.csv` é um exemplo - substitua pelos seus próprios dados
3. Para problemas, abra uma [issue](https://github.com/seu-usuario/dashboard-aerobicovid/issues)

### � Modelo de Citação

Se usar este dashboard em pesquisas, por favor cite como:

```
Lizzi, E. (2025). Dashboard AEROBICOVID - GEEPESC-EEFERP-USP, Jornada da Ciencia Aberta-2025. GitHub repository. 
https://github.com/elisangelalizzi/ciencia_aberta
```
