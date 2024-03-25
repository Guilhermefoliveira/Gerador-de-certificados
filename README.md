# Gerador de Certificados

Um aplicativo simples para gerar certificados personalizados.

Este aplicativo foi desenvolvido usando Python com Flask e a biblioteca python-docx para gerar certificados em formato .docx.

## Como usar

1. Certifique-se de ter o Python instalado em sua máquina. Você pode baixá-lo em [python.org](https://www.python.org/).
2. Clone este repositório em sua máquina local:

    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```
3. Navegue até o diretório do projeto:

    ```bash
    cd nome-do-repositorio
    ```
4. Instale as dependências:

    ```bash
    pip install -r requirements.txt
    ```
5. Inicie o aplicativo:

    ```bash
    python app.py
    ```
6. Abra seu navegador e acesse `http://localhost:5000` para acessar o aplicativo.

7. Preencha o formulário com os dados necessários para o certificado e selecione o modelo desejado.

8. Clique em "Gerar Certificado" para criar o certificado preenchido.

9. Clique em "Baixar Certificado" para baixar o certificado gerado.

## Estrutura do Projeto

- `app.py`: Arquivo principal do aplicativo Flask.
- `templates/`: Pasta contendo os modelos HTML para renderização das páginas.
- `static/`: Pasta contendo arquivos estáticos como CSS, JavaScript, etc.
- `dist/`: Pasta onde os certificados gerados são armazenados.

## Dependências

- Flask
- python-docx

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue para sugestões ou enviar um pull request com melhorias.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes.

---
