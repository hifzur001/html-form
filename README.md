<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Forms</title>
    <link rel="stylesheet" href="style.css" type="text/css">
    <style>
        body {
            background-image: linear-gradient(aqua, red);
            background-position: top;
            background-size: cover;
            background-attachment: fixed;
            font-family: 'Times New Roman', Times, serif;
        }
    </style>
</head>

<body>
    <fieldset>
        <legend>Registration Form</legend>
        <h1 style="text-align: center;">Registration</h1>

        <form action="contact.php" method="post"></form>
        <table>
            <tr>
                <td tabindex=""><label for="name">Name</label></td>
                <td><input type="text" id="name" placeholder="Your Name" required></td>
            </tr>
            <tr>
                <td><label for="age">Age</label></td>
                <td><input type="text" id="age" size="3" placeholder="Age" required></td>
            </tr>
            <tr>
                <td><label for="date of birth">DOB</label></td>
                <td><input type="date" name="date of birth" id="date of birth" placeholder="Enter Your DOB" required>
                </td>
            </tr>
            <tr>
                <td><label for="education">Education</label></td>
                <td><input type="education" name="education" id="education" class="" placeholder="Your Education"
                        size="50" required>
                </td>
            </tr>
            <tr>
                <td><label for="country">Country</label></td>
                <td><input type="text" id="country" value="India" disabled></td>
            </tr>
            <tr>
                <td><label for="address">Address</label></td>
                <td><input type="text" name="address" id="address" placeholder="Enter Your Valid Address" size="70"
                        required></td>
            </tr>
            <tr>
                <td><label for="pincode">Pincode</label></td>
                <td><input type="text" name="pincode" id="pincode" size="4" maxlength="6" placeholder="Pincode"
                        required>
                </td>
            </tr>
            <tr>
                <td><label for="create password">Password</label></td>
                <td><input type="password" name="password" id="password" placeholder="Password"></td>
            </tr>
            <tr>
                <td></td>
                <td>
                    <button type="submit">Submit</button>
                    <button type="reset">Reset</button>
                </td>
            </tr>
        </table>
    </fieldset>


</body>

</html>
