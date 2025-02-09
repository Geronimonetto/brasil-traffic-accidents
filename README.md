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

4. **Baixar o arquivo `.gpkg`:**  

   O projeto utiliza o arquivo `bcim_2016_21_11_2018.gpkg`, essencial para a análise dos dados.  

   - Baixe o arquivo no seguinte link:  
     [bcim_2016_21_11_2018.gpkg](https://drive.google.com/file/d/13UHOXJ4IjC_RYLzHRDekDDwpym3TofOl/view?usp=sharing)  

   - Após o download, mova o arquivo para a pasta `utils` do projeto.  

Agora seu ambiente está pronto para rodar o projeto! 🚀
