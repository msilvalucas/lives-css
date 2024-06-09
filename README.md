# Códigos CSS Odo.digital

### REMOVE ITEMS (MINHA CONTA E ATENDIMENTO)

_Esse código CSS irá remover os ícones MINHA CONTA e ATENDIMENTO:_

```css
.utilities-container .utilities-item:nth-of-type(1),
.utilities-container .utilities-item:nth-of-type(2) {
  display: none !important;
}
```

### ADD Efeito Hover e Border-radius nos itens do menu

_Esse código CSS irá Adicionar um efeito houver (Efeito que acontece quando o usuário passa o mouse sobre um item) e uma borda arredondada:_

```css
a.nav-list-link:hover {
  background-color: #333;
  padding: 10px;
  border-radius: 5px;
}
```
