# mondule3
module 3 solution
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>module 3 solution</title>
    <style>
*{
box-sizing: border-box;
}
.container{
width: 900px;
border: 3px solid black;
margin: auto;
}
.item{
border: 3px solid gray;

margin: 12px 3px;
padding: 12px 3px;
background-color: rgba(197, 188, 188, 0.897);

}
#fruit{
   float: left;
   width: 48%;
   
border: 3px solid gray;

}
#computer{
    float: right;
   width: 48%;

}
#stationary{
    float: left;
   width: 100%;

}
#glass{
    float: right ;
   width: 100%;

}
p,h1{
    text-align: none;
}
h4{
    text-align: center;
    font-size: 30px;
}
header{
    text-align: center;
    font-size: 24px;
}

    </style>
</head>
<body>
    <h4>our menu</h4>
    <header>
         <br><select name="fruit" id="">
             <option value="fruit">fruit</option>
             <option value="computer">computer</option>
           <option value="stationary">stationary</option>
             <option value="glass">glass</option>
         </select>
      </header>
    <div class="container">
<div id="fruit" class="item" >
    <h2>fruit</h2>
    <p id ="fruit" class="item" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam maiores eos architecto quis magni animi deleniti ea quia incidunt laudantium. Fuga non voluptatibus sint tenetur eligendi aliquam maiores temporibus esse.  rem ipsum dolor sit amet consectetur adipisicing elit. Aperiam reiciendis quia exercitationem molestias totam reprehenderit doloribus, quos repudiandae numquam earum temporibus rem! Porro quo doloribus, at vero illo omnis assumenda! </p>
</div>
<div id="computer" class="item" >
    <h2>computer</h2>
    <p id ="computer" class="item" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam maiores eos architecto quis magni animi deleniti ea quia incidunt laudantium. Fuga non voluptatibus sint tenetur eligendi aliquam maiores temporibus esse.  em ipsum dolor sit amet consectetur adipisicing elit. Commodi molestiae eius culpa, quia dignissimos assumenda rerum cumque sunt accusamus quos ad laborum voluptates reiciendis adipisci. Totam maiores nesciunt est commodi?</p>
</div>
<div id="stationary" class="item" >
    <h2>stationary</h2>
    
    <p id ="stationary" class="item" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam maiores eos architecto quis magni animi deleniti ea quia incidunt laudantium. Fuga non voluptatibus sint tenetur eligendi aliquam maiores temporibus esse.  em ipsum dolor sit amet consectetur adipisicing elit. Commodi molestiae eius culpa, quia dignissimos assumenda rerum cumque sunt accusamus quos ad laborum voluptates reiciendis adipisci. Totam maiores nesciunt est commodi?</p>
</div>
<div id="glass" class="item" >
    <h2>glass</h2>
    
    <p id ="glass" class="item" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam maiores eos architecto quis magni animi deleniti ea quia incidunt laudantium. Fuga non voluptatibus sint tenetur eligendi aliquam maiores temporibus esse.  em ipsum dolor sit amet consectetur adipisicing elit. Commodi molestiae eius culpa, quia dignissimos assumenda rerum cumque sunt accusamus quos ad laborum voluptates reiciendis adipisci. Totam maiores nesciunt est commodi?</p>
</div>

</div>


</body>
</html>
