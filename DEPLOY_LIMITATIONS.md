# Observação sobre o Deploy

O aplicativo completo pode ser acessado em:

**https://gabrielmurga.shinyapps.io/avaliacao_institucional_da_ufpr/**  

No deploy (shinyapps.io), a **aba de Upload de Excel** não funciona porque a plataforma executa
o app em um ambiente **somente leitura**.  
Isso impede que o banco `hackathon.duckdb` seja atualizado e causa erros ao tentar criar ou
modificar tabelas.

 **Importante:**  
Localmente (VSCode/Jupyter/Terminal), onde o arquivo DuckDB é gravável, **todas as funcionalidades—including Upload e atualização do banco—funcionam normalmente**.

Essa limitação é da plataforma de hospedagem
