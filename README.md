<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" /><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" /><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />


# ☁️ Previsão do Tempo

Este é um aplicativo simples de Previsão do Tempo que permite buscar informações meteorológicas para qualquer cidade. Ele utiliza a API do OpenWeatherMap para exibir dados como temperatura atual, máxima, mínima, umidade e velocidade do vento.

<div align= "center">
<img width="500" height="300" alt="API Funcionando" src="https://github.com/user-attachments/assets/fdf28d06-f787-4325-882d-9850f661c27b" />

</div>

## 📋 Sumário

* [🚀 Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [⚙️ Configuração e Instalação](#%EF%B8%8F-configura%C3%A7%C3%A3o-e-instala%C3%A7%C3%A3o)
* [🎮 Como Usar](#-como-usar)


## 🚀 Tecnologias Utilizadas

* **HTML5:** Para a estruturação semântica e acessível da página web.
* **CSS3:** Responsável pela estilização visual do aplicativo, garantindo uma interface moderna e responsiva.
* **JavaScript:** A linguagem principal para a lógica de busca, manipulação do DOM e comunicação com a API do OpenWeatherMap.
* **Font Awesome:** Utilizado para os ícones no layout da interface.
* **OpenWeatherMap API:**  A API de onde os dados de previsão do tempo são obtidos.

## ⚙️ Configuração e Instalação

Para configurar e rodar este projeto em seu ambiente de desenvolvimento local, siga os passos abaixo:

1.  **Clone o Repositório:**
    Abra seu terminal ou prompt de comando e execute:
    
    ```bash
    git clone https://github.com/swaggyvitu/wheatherProjectAPI.git
    cd wheatherProjectAPI
    ```
    
2.  **Obtenha sua API Key do OpenWeatherMap::**
    * Visite o site do [OpenWeatherMap](https://openweathermap.org/api) e registre-se para obter sua chave de API gratuita.

3.  **Atualize a API Key no Código:**

      * Abra o arquivo `src/javascript/script.js`.
      * Localize a linha que define `apiKey`:
        ```javascript
        const apiKey = "SUA_CHAVE_AQUI";;
        ```
      * Substitua `"apiKey"` pela sua chave de API obtida no OpenWeatherMap.

4.  **Execute a Aplicação:**
    Após clonar o repositório e configurar sua API Key, basta abrir o arquivo `index.html` diretamente em seu navegador web preferido. Não é necessário um servidor web para esta aplicação simples.

## ☁️  Como Usar

1.  **Abra a Aplicação:** Navegue até o arquivo `index.html` em seu navegador web.
2.  **Digite o Nome da Cidade:** No campo de busca, digite o nome da cidade para a qual deseja verificar a previsão do tempo.
3.  **Pesquisar:** Clique no ícone de lupa ou pressione Enter para realizar a busca.
4.  **Visualize as Informações:** As informações meteorológicas, como temperatura, descrição, temperatura máxima e mínima, umidade e velocidade do vento, serão exibidas na tela.
5.  **Mensagens de Alerta:** Se você não digitar uma cidade ou se a cidade não for encontrada, uma mensagem de alerta será exibida.