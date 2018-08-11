# HTML Form Elements


## TextArea

The `<textarea>` element defines a multi-line input field 
```html
<textarea name="message" rows="10" cols="30">
The cat was playing in the garden.
</textarea>
```

## Radio Button

Radio buttons let a user select ONE of a limited number of choices:
```html
<form>
  <input type="radio" name="gender" value="male" checked> Male<br>
  <input type="radio" name="gender" value="female"> Female<br>
  <input type="radio" name="gender" value="other"> Other
</form>
```


## Select 
The `<select>` element defines a drop-down list:
```html
<select name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>
```

## CheckBox

Checkboxes let a user select ZERO or MORE options of a limited number of choices.

```html
<form>
  <input type="checkbox" name="vehicle1" value="Bike"> I have a bike<br>
  <input type="checkbox" name="vehicle2" value="Car"> I have a car 
</form>
```