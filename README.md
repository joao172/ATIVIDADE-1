# ATIVIDADE-1
FORMULARIO 
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>replit</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>

<body>
 
 <form>
   <h2>FORMULARIO</h2>
   <fieldset>
     <legend>Dados pessoais</legend>
     <label>Nome:</label>
     
     <input type="text" id="Nome" value="" placeholder="Escreva aqui."><br>
     <br><label>Data de nascimento</label>
     
     <input type="date" id="Data de nascimento" value=""><br>
    <br> <label>Endereço:</label>
     
     <input type="text" id="Endereço" value=""  placeholder="RUA E NÚMERO" >
    
     <label>Bairro:</label>
     <input type="text" id="Bairro:" value="" placeholder="">
     
     <label>Cidade:</label>
     <input type="CEP" id="Cidade:" value="">
     <br>
    
     <br><label>CEP:</label>
      <input type="text" name="cep" size="5" maxlength="5" placeholder="XXXXX"> - <input type="text" name="cep2" size="3" maxlength="3" placeholder="XXX"> &nbsp;
     <label>Estado:</label>
    <select name="estado-brasil">
      <option value="invalido"></option>
      <option value="CE">Ceará</option> 
    <option value="RJ">Rio de Janeiro</option>
      <option value="PE">Pernambuco</option>
      <option value="PI">Piauí</option>
      <option value="RN">Rio Grande do Norte</option>
      </select>
     
     </fieldset>
   <br>
   <fieldset>
     <legend>Dados Profissionais</legend>
     <p>Natureza de Cargo</p>
     
     <input type="radio" id="Motorista" name="Natureza de cargo" value="Motorista">
     <label for="Motorista">Motorista</label>
     <input type="radio" id="Vendedor" name="Natureza de cargo" value="Vendedor">
     <label for="vendedor">Vendedor</label>
     <input type="radio" name="Natureza de cargo" id="Serviços Gerais" value="Serviços Gerais">
     <label for="Serviços Gerais">Serviços Gerais</label>
     
     <input type="radio" name="Natureza de Cargo" id="Recepção" value="Recepção">
     <label for="Recepção">Recepção</label>
     <p>Área de Interesse</p>
     <input type="checkbox" name="Área de interesse" id="Clínica" value="Clínica">
     <label for="Clínica">Clínica</label>

     <input type="checkbox" name="Área de interesse" id="Shopping" value="Shopping">
     <label for="Shopping">Shopping</label>
     <input type="checkbox" name="Área de interesse" id="Loja" value="Loja">
     <label for="Loja">Loja</label>
     <input type="checkbox" id="Mercantil" value="Mercantil">
     <label for="Mercantil">Mercantil</label>
     <br>
     <hr>
     <legend>Mini-curriculo</legend>
     <textarea id="swal-input2" rows="15"> </textarea>
     <br>
    <INPUT type="reset"  name="b2" value="Limpar">
<INPUT type="submit" name="b1" value="Enviar">
   
   </fieldset>
   
 </form>
 
</body>

</html>
