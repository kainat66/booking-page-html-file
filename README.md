<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BOOKING</title>
    <link rel="icon" href="Vector (2).png" >
    <style>
        
        nav{
    height: 60px;
    width: 1530px;
    background: white;
    padding: 20px;
    position:sticky;
    top: 0;
}
nav ul{
    float: right;
    margin-right: 40px;
}
nav li{
    display: inline-block;
    margin: 0 30px;
    line-height: 50px;

}
nav a{
    font-size: 25px;
    text-decoration: none;
    color: #005E98;
}
nav a :hover{
    border: 4px solid #005E98;
    background-color: #005E98;
    color: white;
    padding: 5px;
    border-radius: 25px;
}
h1{
    color: #005E98;
}
form{
    font-size: 25px;
    color: #005E98;
    
}
fieldset{
    width: 1480px;
    padding-left: 50px;
    
}
legend{
    font-size: 50px;
}
.button{
    height: 35px;
    width: 120px;
    background-color: #005E98;
    color: aliceblue;
    border: 2px solid #005E98;
}
a{
    color: #005E98;
    text-decoration: none;
}
.item{
    border: 2px solid #005E98;
}
.item2{
    border: 2px solid #005E98;
}

    </style>
  
<body>
    
    <nav>
        <img src="Vector (3).png" height="70PX"/>
        <UL>
            <li > <a href="DELTA.HTML" ><b>HOME</b></a></li> 
            <li > <a href="booking.html" ><b>BOOKING</b></a></li> 
            <li> <a href="services.html" ><b>SERVICES</b></a></li> 
            <li> <a href="login.html" ><b>LOGIN</b></a></li> 
            <li> <a href="about us.html" ><b>ABOUT US</b></a></li> 
         
        </UL>  
    </nav>
   <form>
    <fieldset class="item2">
        <legend><b>Booking</b></legend>
        Name: <input class="item" type="text"/><br/>
        <br/>
        Address: <input   class="item"type="text"/>
        <br/>
        <br/>
        Event name: <input  class="item" type="text"/>
        <br/>
        <br/>
        Venue: <input    class="item"type="text"/>
        <br/>
        <br/>
        No of Guest: <input  class="item"type="number"/>
        <br/>
        <br/>
        Contact NO: <input   class="item"type="text"/>
        <br/>
        <br/>
        Theme colour: <input  class="item"type="color"/>
        <br/>
        <br/>
        Payment:
     <input   class="item"type="radio" value="online payment" name="payment"/>online Payment
     <input  class="item" type="radio" value="cash" name="payment"/>cash
     <br/>
     
     <h4><a href="online payment.html">for online payment click here</a></h4>
     <br/>
     <button class="button"     type="button" onclick="location.href='order booked.html'"  >submit</button>         &nbsp&nbsp&nbsp&nbsp&nbsp <button class="button"     type="button" onclick="location.href='order cancel.html'"  >CANCEL</button>  

    </fieldset>
   </form>
    
</body>
</html>
