# Python-Selenium-Automation
Project created with the objective of automating interactions with the web.


# Target Site
It was developed to be used specifically on the "vivastreet.co.uk" website, interacting with ad renewal buttons. If you want to test it or have the same need as my client, just download the script and make some adaptations that will be described below.

# Technologies used
In order for the project to be fully functional, the following technologies were used:
Python (programming language), Selenium (Framework), WebDriver (API), Time (Python Library).

# How to use?
If you are interested in using this script, follow these steps:
1 - Install Python on your device and then use the following command in cmd: "pip install -U pyinstaller" (It will allow us to create the executable file at the end).

2 - Download the files.

3 - Inside the folder, there will be 3 files, namely:
Automacao.py = Responsible for executing interactions with the Web.
Usuario.py = File containing the login data, necessary to access the account on the website.
chromedriver.exe = Executable that enables communication between the script and the browser. (The code only works if the chromedriver is in the same version as your Chrome browser. After checking which one it is, download it from the following link: "https://googlechromelabs.github.io/chrome-for-testing").

4 - After editing the login data in the "Usuario.py" file, open the CMD in the folder where the files are located and run the command: "pyinstaller --onefile automacao.py". The script executable will be generated in the "dist" folder, created in the same directory after running the command.

5 - Start the file and observe the code in action.

# Note:
Feel free to adapt the project according to your needs.


# Site Alvo
Ele foi desenvolvido para ser usado especificamente no site "vivastreet.co.uk" interagindo com botões de renovação de anúncio. Caso queira testá-lo ou tenha a mesma necessidade que meu contratante, basta fazer o download do script e realizar algumas adaptações que serão descritas abaixo.

# Tecnologias utilizadas
Para que o projeto ficasse completamente funcional, foram utilizadas as seguintes tecnologias:
Python (linguagem de programação), Selenium (Framework), WebDriver (API), Time (Biblioteca Python).

# Como usar?
Caso tenha interesse em utilizar esse script, siga este passo a passo:
1 - Instale o Python em seu dispositivo e na sequência, utilize o seguinte comando no cmd: "pip install -U pyinstaller" (Ele vai permitir que no final criemos o arquivo executável).

2 - Faça o download dos arquivos.

3 - Dentro da pasta, haverá 3 arquivos, sendo eles:
    Automacao.py = Responsável por executar as interações com a Web.
    Usuario.py = Arquivo que contém os dados de login, necessário para acessar a conta no site.
    chromedriver.exe = Executável que possibilita a comunicação entre o script e o navegador. (O código só funciona se o chromedriver estiver na mesma versão do seu navegador Chrome. Após     consultar qual é, faça o download no seguinte link: "https://googlechromelabs.github.io/chrome-for-testing").
    
4 - Tendo editado os dados de login no arquivo "Usuario.py", abra o CMD na pasta onde os arquivos se encontram e execute o comando: "pyinstaller --onefile automacao.py". Será gerado o executável do script na pasta "dist", criada no mesmo diretório após a execução do comando.

5 - Inicie o arquivo e observe o código em ação.

# Observação:
Fique a vontade para adaptar o projeto segundo as suas necessidades.
