
Form - Input Elements
=====================


Source code: 

```html

    <form name="adventure" action="https://httpbin.org/post" method="post">
      <fieldset>
        <div>
          <label>Full name:</label>
          <input type="text" name="fullname">
        </div>

        <div>
          <label>Email:</label>
          <input type="email" name="email">
        </div>

        <div>
          <label>Password:</label>
          <input type="password" name="password">
        </div>
      </fieldset>

      <fieldset>
        <div>
          <label>Adventure name:</label>
          <input type="text" name="adv-name" placeholder="Name this adventure">
        </div>

        <div>
          <label>Type of bicycle:</label>
          <select name="bike">
            <option value="road">Road</option>
            <option value="road">Mountain</option>
            <option value="road">Cyclocross</option>
          </select>
        </div>

        <div>    
          <label>Choose a date:</label>
          <input type="date" name="date">
        </div>

        <div>
          <input type="checkbox" name="cb-agree" value="agree">
          I am prepared to lead this adventure.
        </div>
      </fieldset>
      
      <button type="submit">Save this adventure</button>
    </form>

```


Fieldset #1
-----------

### Full name

`<input>` element
- Input field is a text box: `type="text"`
- Name of input field: `name="fullname"`


### Email

`<input>` element
- Input field is a text box for an email address: `type="email"`
- Name of the input field: `name="email"`


### Password

`<input>` element
- Input field is a text box designed to hide a password: `type="password"`
- Name of the input field: `name="password"`



Fieldset #2
-----------

### Adventure name

`<input>` element
- Input field is a text box: `type="text"`
- Name of input field: `name="adv-name"`
- Placeholder text: `placeholder="Name this adventure"`


### Type of bicycle

`<select>` element
- Name of the selection choice: `name="bike"`
- Selection choice must be one of the `<option>` elements below:
  - Road 
  - Mountain
  - Cyclocross
- Value of the selected option: `value="road"`


### Choose a date

`<input>` element
- Input field will be in the form of a date (mm/dd/yyyy): `type="date"`
- Name of the input field: `name="date"`


### I am prepared to lead this adventure. 

`<input>` element
- Input element is a checkbox (agree or disagree): `type="checkbox"`
- Name of input element: `name=cb-agree`
- Value of the input element: `value="agree"`


Button
------

### Save this adventure

`<button>` element
- Button type is for submitting form: `type="submit"`


