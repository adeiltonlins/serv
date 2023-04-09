# serv
app.get('/', (req, res) => {
    return res.send("Estou usando o metodo GET");
})

app.post('/', (req, res) => {
  
    return res.send("Estou usando o método post");
  })

  app.put('/', (req, res) => {
  
    return res.send("Estou usando o método put");
  })

  app.delete('/', (req, res) => {
  
    return res.send("Estou usando o método delete");
  })

app.listen(8080,() =>{
  //  console.log("Servidor funcionando na porta 8080 ") //o que aparece no terminal
})
