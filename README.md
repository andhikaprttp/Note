# Note🐣
simple note with javascript
> Live preview web 👇
<a href="https://tiamardiana-note.vercel.app/">tiamardiana-note.vercel.app</a>

> Demo Android apk 📱
<a href="https://fdroid.com">Tia Note apk</a>

# Fitur📣
- Buat Catatan
- Menggambar `` beta ``

# Bagaimana cara kerjanya🐱

fungsi menyimpan data 

```javascript

// fungsi menampilkan data stored di local storage
function displayNotes(){
	let notesObj;
	let notesString = localStorage.getItem('notes');
	
	if(notesString == null){
		notesObj = [];
	}
	else{
		notesObj = JSON.parse(notesString);
	}
	
	let html = '';
	
	notesObj.forEach(function(element,index){
		html += `

```


<hr>

# Use🐥

- ``klik`` <a href="https://tiamardiana-note.vercel.app/">tiamardiana-note.vercel.app</a>
<br>

![Screenshot_20220608-211440](https://user-images.githubusercontent.com/79065496/172640831-349c5db4-e831-4b1e-89bc-48ecda252f76.png)

- typing at text area
- ``klik`` <b>Buat</b>
>![Screenshot_20220608-211506](https://user-images.githubusercontent.com/79065496/172642332-9bf148bb-da59-4ab9-bf02-d13cdfa5a8ed.png)

