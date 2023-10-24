# beastboysack
# This is my first github repository 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment Form</title>
    <link rel="stylesheet" href="payment_form_style.css">
</head>
<body>
    <div class="container">
 <form action="">
    <h1 class="main_heading"> Payment Form</h1> 
    <hr>
    <p>Required Fields are followed by *</p>

    <h2>User Information</h2>
    <p>Name: * <input type="text" name="name" required></p>
    <fieldset>
        <legend>Gender * </legend>
<p>
    Male <input type="radio" name="gender" id="male" required> Female <input type="radio" name="gender" id="female" required>

</p>
</fieldset>
<p>Address: <textarea name="address" id="address" cols="50" rows="6"></textarea></p>
<p>Email: * <input type="email" name="email" id="email" required></p>
<p>Pincode: * <input type="number" name="pincode" id="pincode" required></p> 
    <h2>Payment Information</h2>
    <p>Card Type: *
        <select name="card_type" id="card_type" required>
            <option value="">--Select a Card Type--</option>
            <option value="visa">Visa</option>
            <option value="rupay">Rupay</option>
            <option value="mastercard">Mastercard</option>

        </select>

    </p>
    <p>
        Card Number * <input type="number" name="card_number" id="card_number" required>
    </p>
    <p>
        Expiration Date: * <input type="date" name="exp_date" id="exp_date" required>
    </p>
    <p>CVV * <input type="password" name="cvv" id="cvv" required></p>
    <input type="submit" value="Pay Now">

 </form>   
</div>
</body>
</html>


<style>
*{
    box-sizing: border-box;
}

body{
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    margin: 15px 30px;
    font-size: 17px;
    padding: 8px;

}

.container {
    background-color:#f2f2f2;
    padding: 5px 20px 15px 20px;
    border: 2px solid lightgray;
    border-radius: 4px;

}

input[type="text"],
input[type="email"],
input[type="number"],
input[type="password"],
input[type="date"],
select,
textarea{
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 5px;
    margin: 10px;
}

fieldset{
    background-color: #fff;
    border: 1px solid #ccc;
}

.main_heading{
    text-align: center;
}
h1{
    
}

input[type="submite"] {
    background-color: #4daea1;
    color: white;
    padding: 12px 20px;
    border-radius: 4px;
    cursor: pointer;
    width: 50%;

}
input[type="submit"] value:hover {
    background-color: lightgreen;
}

</Style>



