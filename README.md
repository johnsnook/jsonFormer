## jsonFormer

This jquery plugin or widget or whatever they're called now, takes a json object and builds a form inside the element you specify.
You can then make changes to the data in the form and request 
$('#form-container').jsonFormer({
    title: "Just point me at a div and pass me an object",
    jsonObject: {"name":"john", "charisma": 100, "handsome":true};
});

To get the modified object use
var newObj = $('#form-container').jsonFormer('formData');

if you just want the differences use
var diffObj = $('#form-container').jsonFormer('getDiff');

### Support or Contact

Having trouble with my plugin? Email me at jsnook@gmail.com and I might just check my email that very same month!
