# Portfólio Vitor Almeida Santos 

Portfólio criado para a disciplina de Desenvolvimento Web do curso de Sistemas de Informação do Instituto Federal de Educação, Ciência e Tecnologia Baiano.

# **Estrutura da Página**

O site é feito de duas partes principais:
1. **home**: Onde o usario pode me conhecer e saber minhas redes.
2. **Sobre mim**: Onde tem um breve texto sobre mim.
3. **Educação**: Onde o usuário pode vizualizar minhas informações educacionais
4. **Ferramentas**: onde o usuário pode vizualizar as linguagens e ferramentas
5. **Projetos**: Onde o usuário pode saber qual projetos eu ja participei 

# Dados do Autor
- **Nome:** Vitor Almeida Santos
- **Instituição de estudo:** Instituto Federal de Educação, Ciência e Tecnologia Baiano - campus Itapetinga
- **Website:** [vialsa.github.io](https://vialsa.github.io/)
- **Email:** [20211ITA01GB0038@alunos.ifbaiano.edu.br](20211ITA01GB0038@alunos.ifbaiano.edu.br)

# Sobre o Codigo
O codigo em si foi desenvolvido utilizando HTML e CSS. O objetivo é apresentar de forma elegante e responsiva as habilidades, formação acadêmica, experiências e projetos desenvolvidos.

# Estrutura do Código
## **HTML**
- Segue uma estrutura padrão, contendo uma seção *header* para a navegação, *main* para o conteúdo principal e *footer* para o rodapé.
- O conteúdo é dividido em seções: "Home", "Sobre Mim", "Educação", "Ferramentas", e "Projetos", cada uma com um ID específico para facilitar a navegação.

#### Html *header*
```html
<header>
        <div class="interface">
            <div class="logo">
                <a href="">
                    <img src="img/wolf-4-svgrepo-com8.svg" alt="Logo">   
                </a>
            </div><!--Termina a logo/interface-->

            <nav>
                <ul>
                    <li>
                         <a href="#home">Home</a>
                    </li>
                    <li>
                        <a href="#sobreM">Sobre mim</a>
                    </li>
                    <li>
                        <a href="#educa">Educação</a>
                    </li>
                    <li>
                        <a href="#ferramenta">Ferramentas</a>
                    </li>
                    <li>
                        <a href="#projetos">Projetos</a>
                    </li>
                    

                </ul>
            </nav><!--Termina menu da interface_Dsk-->

            <div class="btn_CV">
                <a href="Vitor_Almeida_Currículo.pdf">
                    <button>CV</button>
                </a>
            </div>
        </div> <!--Termina a Interface-->
    </header>
```
#### Html *main*
![image](https://github.com/user-attachments/assets/90b83439-6a44-44d2-9788-ec40c287cc75)

#### Html *footer*
```html
<footer>
        © 2024 Copyright Portifólio by Vitor Almeida
</footer>
```

##**CSS** 
- Um arquivo externo de CSS é utilizado para estilizar a página, aplicando cores escuras e vermelhas para criar um visual moderno e elegante. Alem de ter uma integração de Fonte importada do Google Fonts, utilizando a família "Ubuntu" para garantir uma tipografia consistente.

#### CSS *Seletor Universal*
```css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;  
    font-family: "Ubuntu", sans-serif;
    font-weight: 300;
    font-style: normal;
    --vermelho_padrao-- :#c20000;
    --vermelho_brilhante--: #ff0202;
    --cor_fonte--: #dfdddd;
    --backgraund_claro--: #1010106f;
}
```
  
- A página é responsiva, escondendo o cabeçalho em telas menores que 920px.

#### CSS *Responsiva: 920px*
```css
*{
@media (max-width: 919px) {
    header {
        display: none; /* Esconde a header em telas menores que 768px */
    }
}
```
  
- Estilos personalizados são aplicados para diferentes elementos, como animações na imagem de perfil e efeitos de hover nos links de navegação.

#### CSS *Animação Botão*
```css
header a:hover{
    color: var(--vermelho_brilhante--);
    transform: scale(1.1);
}
```

#### CSS *Animação Perfil*
```css
.home_img{  
    border-radius: 40%;
    max-width: 250px;
    max-height: 250px;
    width: auto;
    height: auto;
    overflow: hidden;
    cursor: pointer;
    animation:sombra 2s linear ;
    animation-direction: alternate;
    animation-iteration-count: infinite;
}

@keyframes sombra {
    from{
        box-shadow: 0 0 20px var(--vermelho_padrao--);
    }
    to{
        box-shadow: 0 0 50px var(--vermelho_brilhante--) ;
    }
}
```

Esse portifólio mostra quem quem sou eu, o que eu sei fazer e como entrar em contato com comigo. O HTML organiza tudo e o CSS deixa tudo bonito.

Se tiver alguma dúvida, pode perguntar! 😊
```
