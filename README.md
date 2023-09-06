# Formulario
 
<form class="form-horizontal">
<fieldset>

<!-- Form Name -->
<legend>CADASTRO DE USUÁRIO</legend>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="textinput">Nome</label>  
  <div class="col-md-5">
  <input id="textinput" name="textinput" type="text" placeholder="Digite seu Nome" class="form-control input-md" required="">
    
  </div>
</div>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="textinput">Sobrenome</label>  
  <div class="col-md-5">
  <input id="textinput" name="textinput" type="text" placeholder="Digite seu Sobrenome" class="form-control input-md">
    
  </div>
</div>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="textinput">Telefone</label>  
  <div class="col-md-5">
  <input id="textinput" name="textinput" type="text" placeholder="Digite seu Telefone" class="form-control input-md" required="">
    
  </div>
</div>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="textinput">E=mail</label>  
  <div class="col-md-5">
  <input id="textinput" name="textinput" type="text" placeholder="Digite seu E-mail" class="form-control input-md">
    
  </div>
</div>

<!-- Multiple Radios -->
<div class="form-group">
  <label class="col-md-4 control-label" for="radios">Sexo</label>
  <div class="col-md-4">
  <div class="radio">
    <label for="radios-0">
      <input type="radio" name="radios" id="radios-0" value="1" checked="checked">
      Masculino
    </label>
	</div>
  <div class="radio">
    <label for="radios-1">
      <input type="radio" name="radios" id="radios-1" value="2">
      Feminino
    </label>
	</div>
  <div class="radio">
    <label for="radios-2">
      <input type="radio" name="radios" id="radios-2" value="3">
      Prefiro não dizer
    </label>
	</div>
  </div>
</div>

<!-- Select Basic -->
<div class="form-group">
  <label class="col-md-4 control-label" for="selectbasic">Escolaridade</label>
  <div class="col-md-4">
    <select id="selectbasic" name="selectbasic" class="form-control">
      <option value="1">Ensino Fundamental</option>
      <option value="2">Ensino Médio</option>
      <option value="3">Ensino Superior</option>
    </select>
  </div>
</div>

<!-- Multiple Radios (inline) -->
<div class="form-group">
  <label class="col-md-4 control-label" for="radios">Escolaridade</label>
  <div class="col-md-4"> 
    <label class="radio-inline" for="radios-0">
      <input type="radio" name="radios" id="radios-0" value="1" checked="checked">
      Completo
    </label> 
    <label class="radio-inline" for="radios-1">
      <input type="radio" name="radios" id="radios-1" value="2">
      incompleto
    </label>
  </div>
</div>

<!-- Textarea -->
<div class="form-group">
  <label class="col-md-4 control-label" for="textarea">Comentário</label>
  <div class="col-md-4">                     
    <textarea class="form-control" id="textarea" name="textarea">Digite seu Comentário</textarea>
  </div>
</div>

<!-- File Button --> 
<div class="form-group">
  <label class="col-md-4 control-label" for="filebutton">Foto</label>
  <div class="col-md-4">
    <input id="filebutton" name="filebutton" class="input-file" type="file">
  </div>
</div>

<!-- Button -->
<div class="form-group">
  <label class="col-md-4 control-label" for="singlebutton">Enviar</label>
  <div class="col-md-4">
    <button id="singlebutton" name="singlebutton" class="btn btn-info">Enviar</button>
  </div>
</div>

</fieldset>
</form>
