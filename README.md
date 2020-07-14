## Reforçando conhecimentos em JavaScript

:rocket: Tecnologias utilizadas:
- HTML,
- CSS,
- JavaScript

```javascript
addTask = function () {
  if (document.getElementById("task").value != "") {
    item = document.getElementById("task");
    itemId = ul.childElementCount;
    li = createItemEl(item.value, itemId);
    li.appendChild(createRemoveTaskBtn(itemId));
    ul.appendChild(li);
    item.value = "";
  }
};
```
