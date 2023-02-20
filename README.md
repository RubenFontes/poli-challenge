# Sobre
Esse repositório contém os arquivos do processo seletivo da empresa Poli para a vaga de Dev. Wordpress Jr.

## Códigos
```bash
button{
    cursor: pointer;
}
```
 A regra `cursor: pointer;` foi utilizada para especificar que o cursor do mouse deve ser exibido como link ao apontar sobre o elemento button.

```bash
::-webkit-scrollbar {
    width: 10px;
}
```
 O pseudo-elemento `::-webkit-scrollbar` foi utilizado para modificar a aparência da barra de rolagem do navegador. Selecionado, usei a propriedade `width` para modificar a largura da barra de rolagem e setá-la em 10 pixels.

```bash
::-webkit-scrollbar-track {
    background-color: transparent;
}
```
O `::-webkit-scrollbar-track` seleciona a alça de rolagem arrastável. Utilizei a propriedade `background-color` para modificar a cor de fundo para transparente.

```bash
::-webkit-scrollbar-thumb {
    background: lightgrey; 
}
```
 O `::-webkit-scrollbar-thumb` seleciona a trilha (barra de progresso) da barra de rolagem. Utilizei a propriedade `background` para modificar a cor de fundo para cinza claro.

```bash
::-webkit-scrollbar-thumb:hover {
    background: darkgrey; 
}
```
 O seletor `:hover` é usado para selecionar elementos quando você passa o mouse sobre eles. No contexto do caso de uso, utilizei para destacar quando o usuário mantiver pressionar a alça de rolagem da barra.
