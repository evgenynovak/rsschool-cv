## Evgeniy Novak
### Contact information
* E-mail:  evnovak171@mail.ru
* Discord: Evgeniy Novak(@evgenynovak)
### About myself
My goal is to become a front-end developer
### Skills
* JavaScript
* HTML
* CSS
* Git
### Example 
```
function Board ({board, onClickAtCell}) {
  return (
    <BoardBlock>
      {board.map( (cell, i) =>
        <Cell key={i} cell={cell} onClick={() => onClickAtCell(i)} />
      )}
    </BoardBlock>
  );
}
```

