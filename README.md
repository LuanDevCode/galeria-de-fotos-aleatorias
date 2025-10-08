# 📸 Galeria de Fotos Responsiva

Uma simples e elegante galeria de fotos desenvolvida puramente com **HTML e CSS**. Este projeto foca em demonstrar o uso de **Flexbox** para o layout, **responsividade** (adaptando-se a diferentes tamanhos de tela) e efeitos de **transição** e **hover** para uma experiência de usuário mais interativa.

---

## ✨ Funcionalidades

* **Design Responsivo:** O layout se adapta perfeitamente a dispositivos móveis, tablets e desktops graças ao uso de **Flexbox** e `max-width`.
* **Efeito de Hover Interativo:** Ao passar o mouse sobre as imagens, elas ganham destaque com um efeito de **zoom suave** (`transform: scale`) e aumento de opacidade.
* **Descrição On-Hover:** A descrição da imagem aparece de forma dinâmica quando o usuário interage com a foto.
* **Estilização Moderna:** Uso de fontes externas (Google Fonts - **Roboto**) e ícones (Material Symbols) para um visual limpo e profissional.
* **Imagens Placeholder:** Utiliza o serviço **[Picsum Photos](https://picsum.photos/)** para carregar imagens aleatórias, facilitando a visualização e prototipagem.

---

## 🛠 Tecnologias Utilizadas

| Tecnologia | Descrição |
| :--- | :--- |
| **HTML5** | Estruturação da página e dos elementos da galeria. |
| **CSS3** | Estilização, layout responsivo (Flexbox) e criação dos efeitos de transição. |
| **Google Fonts** | Importação da fonte 'Roboto'. |
| **Material Symbols** | Utilizado para adicionar um ícone no título da página. |

---

## 🚀 Como Visualizar

1.  **Clone o Repositório:**
    ```bash
    git clone https://github.com/LuanDevCode/galeria-de-fotos-aleatorias)
    ```
2.  **Acesse a Pasta:**
    ```bash
    cd nome-do-seu-repositorio
    ```
3.  **Abra o Arquivo:**
    Basta abrir o arquivo `index.html` em seu navegador preferido (Chrome, Firefox, etc.).

---

## 💡 Opinião e Destaques do Código

Este projeto é um excelente exemplo de como criar uma galeria visualmente rica e responsiva sem depender de JavaScript.

### Pontos Fortes no CSS:

1.  **Flexbox no `body`:** O uso de `display: flex;` com `flex-direction: column;` e `min-height: 100vh;` no `body` garante que o conteúdo esteja sempre **centralizado na tela**, o que é ótimo para apresentação.
2.  **Responsividade Controlada:** A combinação de `width: 100%;` e `max-width: 950px;` no container e o uso de `flex-wrap: wrap;` faz com que as fotos se rearranjem de forma **inteligente** em telas menores, mantendo um limite de tamanho em telas maiores.
3.  **Efeito de Zoom:** O uso combinado de `opacity: 60%;` e o `transform: scale(1.2);` com `opacity: 100%;` no `hover` da imagem cria um efeito de **"foco"** muito atraente, realçado pelo `transition: 0.5s;` para a suavidade.
4.  **Descrições Dinâmicas:** A técnica de usar o seletor de adjacência (`.fotos img:hover + p`) para exibir a descrição é um uso **esperto e puro CSS** para criar interatividade sem JavaScript.


---

## 🧑‍💻 Autor

Luan Marcos

