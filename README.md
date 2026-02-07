#  Automação de Relatório de Vendas

Sistema Python que automatiza o processo completo de extração, análise e envio de relatório de vendas diárias para a diretoria.

##  Descrição

Este projeto automatiza uma tarefa diária de analista: acessar o sistema de vendas, baixar a planilha do dia anterior, processar os dados e enviar um email com relatório formatado para a diretoria.

**Processo automatizado:**
1. Acessa Google Drive automaticamente
2. Navega até a pasta de vendas
3. Baixa a planilha do dia anterior
4. Processa 7.089 transações de vendas
5. Calcula faturamento total e quantidade de produtos
6. Compõe email profissional com os indicadores
7. Envia automaticamente para a diretoria

##  Funcionalidades

-  Automação completa do navegador (Chrome)
-  Download automático de arquivos do Google Drive
-  Processamento de planilhas Excel (.xlsx)
-  Cálculo de indicadores de negócio (faturamento e volume)
-  Composição e envio automático de emails via Gmail
-  Formatação profissional de relatórios
-  Execução sem intervenção manual

##  Tecnologias Utilizadas

- **Python 3.13**
- **PyAutoGUI** - Automação de mouse e teclado
- **Pandas** - Análise e processamento de dados
- **OpenPyXL** - Leitura de arquivos Excel
- **Pyperclip** - Manipulação de área de transferência
- **Time** - Controle de timing entre ações

##  Resultados

O sistema processa com sucesso:
- **7.089 transações** de vendas
- **Faturamento total:** R$ 2.917.311,00
- **Volume de produtos:** 15.227 unidades vendidas

##  Instalação
```bash
# Clone o repositório
git clone https://github.com/SEU_USUARIO/automacao-vendas.git

# Entre no diretório
cd automacao-vendas

# Instale as dependências
pip install pandas pyautogui openpyxl pyperclip
```

##  Como Usar
```python
# Execute o notebook Jupyter
jupyter notebook "Arquivo_Inicial_-_Aula_1.ipynb"

# Ou execute as células sequencialmente:
# 1. Automação de navegação e download
# 2. Processamento de dados
# 3. Envio de email
```

##  Exemplo de Email Gerado
```
Prezado,

Segue o relatório de vendas de hoje.

Faturamento: R$2.917.311,00
Quantidade de produtos vendidos: 15,227

Qualquer coisa estou à disposição.
Abs,
Alex Perna
```

##  Estrutura do Código
```python
# 1. Automação de Navegação
- Abre Chrome
- Acessa Google Drive
- Navega e baixa planilha

# 2. Processamento de Dados
- Lê arquivo Excel com Pandas
- Calcula soma do faturamento
- Calcula total de produtos

# 3. Envio de Email
- Abre Gmail
- Compõe email formatado
- Envia automaticamente
```

##  Aprendizados

Este projeto me ensinou:

- **Automação de processos:** Como automatizar tarefas repetitivas com Python
- **Web scraping e navegação:** Controle programático de navegadores
- **Análise de dados:** Processamento de grandes volumes com Pandas
- **Integração de ferramentas:** Google Drive + Excel + Gmail
- **Solução de problemas reais:** Aplicação prática de programação no dia a dia empresarial

##  Contexto de Aprendizado

Projeto desenvolvido durante estudo de automação com Python, simulando cenário real de trabalho onde analista precisa enviar relatórios diários à diretoria.

##  Observações

- As coordenadas do mouse (x, y) são específicas da minha resolução de tela
- Para usar em outra máquina, ajuste as posições usando `pyautogui.position()`
- O arquivo Excel deve estar na pasta Downloads
- Requer Chrome instalado e configurado

##  Autor

**Alex Perna**
-  Email: alexpernaoficial@gmail.com
-  LinkedIn: www.linkedin.com/in/alexpernaoficial
-  GitHub: (https://github.com/alexpernaoficial)
-  Maringá - PR

---

 **Projeto desenvolvido como parte da jornada de transição para TI e aprendizado de automação com Python**

 Se este projeto foi útil para você, deixe uma estrela!
```
