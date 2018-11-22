# vize
<!DOCTYPE html>
<html>
<head>
<title>CV HAZIRLAMA</title>
</head>
<body>
	
    <div class="container">
      <h2>İŞ KAYIT FORMU</h2>
      <form role="form" accept-charset="utf-8" action="ReadFormData" method="get">
      	<div class="container-fluid" align="right">
		</div><br>
        <div class="form-group"><br>
        	<label for="ex1">Adınız:</label>
        	<input class="form-control" id="ex1" type="text" name="Sinan Serkan">
        </div>
        <div class="form-group">
        	<label for="ex2">Soyadınız:</label>
        	<input class="form-control" id="ex2" type="text" name="ÇAĞLI"><br>
      	</div>
      	<div class="form-group">
        	<label for="ex3">Doğum Tarihiniz:</label>
        	<input class="form-control" id="ex3" type="date" name="02/07/1993">
      	</div>
     	 <div class="form-group">
      		<label for="ex-4">Yaşınız:</label>
      		<input class="form-control" id="ex-4" type="number" name="24">
      	</div>
      	<div class="form-group">
      		<label for="cinsiyet"> Cinsiyet: </label>
      		&nbsp&nbsp
			<input type="radio" name="erkek" /> Erkek
			&nbsp&nbsp&nbsp
			<input type="radio" name="bayan" /> Bayan<br>
		</div>
      	<div class="form-group">
      		<label for="sel2">Yetenekleriniz:</label>
      		<input type="checkbox" name="android" /> Android  &nbsp&nbsp
			<input type="checkbox" name="java"  /> Java&nbsp&nbsp
			<input type="checkbox" name="jsp"/>  JSP&Servlet&nbsp&nbsp
			<input type="checkbox" name="html"/> HTML5/CSS3&nbsp&nbsp
			<input type="checkbox" name="bootstrap"/> Bootstrap&nbsp&nbsp
			<input type="checkbox" name="ajax"/> AJAX&nbsp&nbsp
			<input type="checkbox" name="jquery"/>  JQuery&nbsp&nbsp
			<input type="checkbox" name="hibernate"/> Hibernate&nbsp&nbsp
			<input type="checkbox" name="sqlite"/> SQLite Database
	  	</div>
	  	<div class="form-group">
      		<label for="ex-5">Adresiniz:</label>
      		<input class="form-control" id="ex-5" type="text" name="Dokuz Eylül Üniversitesi İşletme Fafültesi">
      	</div>
	  	<div class="form-group">
      		<label for="comment">Eklemek İstedikleriniz:</label>
      		<textarea class="form-control" rows="5" id="comment" name="hakkınızda ekstra bilgi"></textarea>
    	</div>
        <button type="submit" class="btn btn-primary" align="center" >Kaydet</button>
</form>
</body>
</html>
