<label class="control-label col-md-3">id_wilayah</label> 
	<div class="col-md-9"> 
	
	
	<select name="id_wilayah" class="form-control">
			<option value="id_wilayah"></option>
			<?php foreach($tr_wilayah as $store)
			
			{ ?>
			<option> <?=$store->id_wilayah;?></option>		
			
			<?php } ?>
	</select>
	
	
	
<span class="help-block"></span>
</div>


<label class="control-label col-md-3">kewarganegaraan</label>
<div class="col-md-9">
	<select name="kewarganegaraan" class="form-control">
			<option value="kewarganegaraan"></option>
			<?php foreach($tr_negara as $stores) { ?>
			<option> <?=$stores->id_negara;?></option>			<?php } ?>
	</select>	
<span class="help-block"></span>
</div>
