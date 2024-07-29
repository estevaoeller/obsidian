---
id: <% tp.file.title.split(" ")[0] %>
created_date: <% tp.file.creation_date('DD/MM/YYYY') %>
updated_date: <% tp.file.creation_date('DD/MM/YYYY') %>
---
- **🏷️Tags** : #daily [[Daily Notes]]

## 📝 Notas
- <% tp.file.cursor() %>


## Objetivos do Dia

  - [ ] Objetivo 1
  - [ ] Objetivo 2
  - [ ] Objetivo 3


## Links
- [ ] 


## Reflexão

- **Humor:** 

- **O que foi realizado:**

- **O que pode ser melhorado:**

## Thoughts
##### 🙌 One thing I'm excited about right now is...

##### 👎 One thing I'm struggling with today is...

##### 🚀 One+ thing I planned to accomplish today is...


##### 🚀 One+ thing I learned today is...

## 📖 Devocional
- [[07 Devocional/<% "Devocional " + tp.date.now("YYYY-MM-DD") %>|Devocional de Hoje]]


---
### Notes created today
```dataview
List FROM "" WHERE file.cday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.ctime asc
```

### Notes last touched today
```dataview
List FROM "" WHERE file.mday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.mtime asc
```