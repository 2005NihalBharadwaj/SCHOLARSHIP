<!DOCTYPE html>
<html lng="en">



<head>


  <title> Registration Form </title>

  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet"    href="scholarship.css">  
</head>


<form>

  <header>


    <p>

    <div class="h1">

      <marquee> Register for SCHOLARSHIP </marquee>
    </div>
    </p>
  </header>

  <br>
  <hr>
  <h2> Introduction </h2>

  <p>
    First Name :-
    <input type="text"     placeholder="Ram">                 Last Name :-
    <input style="margin-top:10px;" type="text"     placeholder="Kumar">    
  </p>

  <br>
  <p>Class :-
    <input type="number" placeholder="ex. 10">    
  </p>

  <br>
  <p> Father's Name:-
    <input type="text" placeholder="Mr. Ram Kumar">    
  </p>

  <br>
  <p> Mother's Name:-
    <input type="text" placeholder="Mrs. Sita Devi">    
  </p>

  <br>
  <fieldset>

    <legend>Gender</legend>


    <p>GENDER :-
      <input type="radio" name="gender"> MALE
      <input type="radio" name="gender"> FEMALE
      <br>      
    </p>
    </di>
  </fieldset>



  <hr>
  <h2> Contact details </h2>

  <div class="www">

    <p>Phone Number :-
      <select>


        <option> +91 </option>


        <option> +92 </option>


        <option> +93 </option>


        <option> +94 </option>


        <option> +95 </option>

      </select>

      <input type="number" placeholder="12345***">      
    </p>

    <br>
    <p>Whatsapp Number:-
      <input type="number" placeholder="12345***">      
    </p>


    <p>Email :-
      <input type="email" placeholder="xyz@gmail.com">      
    </p>

    <br>
    <p>
      Address :-
      <input type="text" placeholder="club road Muzaffarpur">      
    </p>
  </div>


  <hr>
  <h2>Payment Details</h2>

  <div class="www">

    <p>Account Number:-
      <input type="number">    
    </p>

    <p>Card Number :-
      <select>

        <Option>Visa </Option>

        <Option>Rupay </Option>

        <Option>Master </Option>
      </Select>

      <input type="number">      
    </p>

    <br>
    <p>
      CVV :-
      <input type="number" placeholder="123">      
    </p>

    <br>
    <p>
      Expiary Date :-
      <input type="date">      
    </p>
  </div>

  <hr>


  <input type="submit" value="SUBMIT" class="but" onclick="submit()" style="border:1px solid grey; border-radius:40px; width:49%; ">
  <input type="reset" value="RESET" class="but" style="border:1px solid grey; border-radius:40px; width:49%; float:right;">





</form>

</html>

