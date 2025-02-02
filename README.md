# brasil-traffic-accidents
Repositório para análise de dados de acidentes de trânsito no Brasil. O objetivo é explorar, visualizar e gerar insights sobre as principais causas, locais e tendências de acidentes, visando auxiliar na criação de políticas públicas e estratégias para reduzir acidentes nas rodovias brasileiras.
Aqui está um minitexto com os comandos que você pode usar para criar, ativar e instalar as dependências de uma venv para o seu projeto:

---

**Passos para configurar o ambiente virtual e instalar as dependências:**

1. **Criar o ambiente virtual:**

   No terminal, dentro do diretório do projeto, execute o comando:

   ```bash
   python -m venv venv
   ```

2. **Ativar o ambiente virtual:**

   - **No Windows:**

     ```bash
     .\venv\Scripts\activate
     ```

   - **No macOS/Linux:**

     ```bash
     source venv/bin/activate
     ```

3. **Instalar as dependências do projeto:**

   Após ativar a venv, instale as bibliotecas listadas no arquivo `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

4. **Extrair o arquivo `.gpkg`:**

   O projeto utiliza o arquivo `bcim_2016_21_11_2018.gpkg`, que está comprimido em 5 partes dentro da pasta `utils`. Para rodar o código corretamente, você precisará extrair esse arquivo antes de executar o projeto.

   Para extrair, execute o seguinte comando dentro do diretório `utils`:

   ```bash
   cat bcim_2016_21_11_2018.gpkg.part1 bcim_2016_21_11_2018.gpkg.part2 bcim_2016_21_11_2018.gpkg.part3 bcim_2016_21_11_2018.gpkg.part4 bcim_2016_21_11_2018.gpkg.part5 > bcim_2016_21_11_2018.gpkg
   ```

   Após a extração, o arquivo `bcim_2016_21_11_2018.gpkg` estará pronto para ser usado no projeto.

Agora seu ambiente está pronto para rodar o projeto!
