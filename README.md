const express = require('express'); 
const app = express(); 
const port = 3000; 
app.get('/', (req, res) => { 
  res.send('Hola, bienvenidos a mi API. en este caso trabajaré en un proyecto final y espero que sea de su agrado dicho proyecto y si tiene éxito será lanzado para todos y cada uno de ustedes, espero se sientan comodo y disfruten de los códigos de este repositorio'); 
}) 

app.listen(port, () => { 
  console.log(`Example app listening at http://localhost:${port}`); 
}) 
process.env.RUNKIT_ENDPOINT_URL;
