<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
    <style>
        *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body
{
    font-size: 14px;
    background: #f2f2f2;
}
.wrapper{
    background: white;
    width: 500px;
    padding: 25px;
    margin: 50px auto 0;
    border-top: 5px solid blue ;
    box-shadow: 0 0 7px 5px rgba(0, 0, 0, 0.5);
}

    </style>
</head>
<body>
    <h2>Registration form</h2>
    <form action="https://formspree.io/f/xwkgyelk" method="post" class="wrapper">
        <div>
            <label for="Fullname">FullName:</label>
            <input type="text" name="Fullname" id="Fullname" placeholder="FullName" required>
        </div> <br>
        <div>
            <label for="Email">Email:</label>
            <input type="email" name="Email" id="Email" placeholder="Email" required>
        </div> <br>
        <div>
            <label for="Date_of_Birth">Date of Birth:</label>
            <input type="date" name="Date_of_Birth" id="Date_of_Birth" required>
        </div> <br>
        <div>
            <label for="Gender">Gender:</label>
            <input type="radio" name="Gender" id="Gender" value="Male">Male
            <input type="radio" name="Gender" id="Gender" value="Female">Female
        </div> <br>
        <div>
            <label for="Religion">Religion:</label>
            <input type="radio" name="Religion" id="Religion" value="Islam" checked>Islam
            <input type="radio" name="Religion" id="Religion" value="Hindu">Hindu
        </div> <br>
        <div>
            <label for="Division">Division:</label>
            <select name="Division" id="Division" class="Division" required>
                <option selected value="">Select a division</option>
                <option value="Dhaka">Dhaka</option>
                <option value="Chattogram">Chattogram</option>
                <option value="Barishal">Barishal</option>
                <option value="Khulna">Khulna</option>
                <option value="Rajshahi">Rajshahi</option>
                <option value="Rangpur">Rangpur</option>
                <option value="Mymensingh">Mymensingh</option>
                <option value="Sylhet">Sylhet</option>
            </select>
        </div> <br>
        <div>
            <label for="Message">Message:</label>
            <textarea name="message" id="message" cols="30" rows="10" placeholder="Right your message detailsy">Right details</textarea>
        </div> <br>
        <div> 
            <input type="submit" value="Register">
            <input type="reset" value="Clear">
        </div>
    </form>
</body>
</html>
