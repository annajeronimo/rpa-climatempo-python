# ☁️ Previsão do Tempo com Python (RPA)

Este é um projeto simples de **RPA (Robotic Process Automation)** usando **Python e Selenium** para automatizar a coleta da previsão do tempo do site [Climatempo](https://www.climatempo.com.br/).
O script acessa o site, pesquisa por uma cidade, coleta a **temperatura atual** e a **condição climática**, e salva as informações em uma planilha Excel.

---

## 📸 Demonstração

![Exemplo de planilha gerada](link_da_imagem_ou_gif)

---

## 🛠️ Tecnologias usadas

- Python 3.x
- Selenium
- OpenPyXL (para salvar em Excel)
- ChromeDriver

---

## 📦 Instalação

1. Clone este repositório:


git clone https://github.com/seu-usuario/previsao-tempo-rpa.git
cd previsao-tempo-rpa

2. Crie e ative um ambiente virtual (opcional, mas recomendado):
![image](https://github.com/user-attachments/assets/dcd75bd6-0e3e-400f-9b35-0ae9f8561444)

3. Instale as dependências:
![image](https://github.com/user-attachments/assets/5d7fe7f3-c8ad-4f4e-a0d9-74dadf3c5448)

4. Baixe o ChromeDriver compatível com sua versão do Chrome e coloque o executável na raiz do projeto (ou adicione ao PATH).

▶️ Como executar
Basta rodar o script principal:
![image](https://github.com/user-attachments/assets/07b3339a-e296-4050-8bb7-d9cd43b401c1)

✏️ Personalização
Você pode mudar a cidade que será pesquisada no script previsao.py modificando esta linha:
![image](https://github.com/user-attachments/assets/6e80f4c8-5845-47a5-a9f7-74c5c6d04e5a)
Também é possível adaptá-lo para coletar múltiplas cidades ou rodar automaticamente todo dia com o Task Scheduler (Windows) ou cron (Linux/Mac).

📝 Exemplo de saída (Excel)
Cidade	Temperatura	Condição
São Paulo	24º	Sol com nuvens

🤖 Sobre
Este projeto é ideal para iniciantes que estão aprendendo automação com Python e desejam aplicar conceitos de RPA em tarefas do dia a dia.



📄 Licença

Este projeto está sob a licença MIT:

Copyright (c) 2025 Ana Carolina




