## to use html to get form file and upload data
>  add this property in html file

```
encrypt="multipart/form-data" 
```
> in postman to upload file or get file must use 

```
form-data
```

> in express

```
app.use(express.urlencoded({ extended: true }))
```

**html form part**

```
<form action="/upload" method="POST" enctype="multipart/form-data">
      <label for="img">upload image:</label>

      <input type="file" name="imgNameFromInputField" id="img" />

      <button>submit</button>
</form>
```
