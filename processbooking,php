<!DOCTYPE html>
<html lang="en">
<head>
	<title>Booking Confirmation</title>
    <meta charset="utf-8">
</head>
<body> 
    <h1>Rohirrim Booking Confirmation</h1>
    
<?php

$firstname = $_POST['firstname'];
$lastname = $_POST['lastname'];
echo "<p>Welcome " . $firstname . " " . $lastname . ".</p>";

$bookings = array();

if (isset($_POST["accom"])) {
    $bookings[] = "Accommodation";
}
if (isset($_POST["4day"])) {
    $bookings[] = "4 Day Tour";
}
if (isset($_POST["10day"])) {
    $bookings[] = "10 Day Tour";
}

$count = count($bookings);

if ($count > 0) {

    if ($count == 1) {
echo "<p>You are now booked on " . $bookings[0] . "</p>";    }

    if ($count == 2) {
        echo "<p>You are now booked on " . $bookings[0] . " and " . $bookings[1] . "</p>";
    }

    if ($count == 3) {
        echo "<p>You are now booked on " . $bookings[0] . ", " . $bookings[1] . " and " . $bookings[2] . "</p>";
    }

} else {
    echo "<p>You did not select any booking.</p>";
}


 if (isset($_POST["species"])) {
    echo "<p>Species: " . $_POST["species"] . "</p>";
}   

if (isset($_POST["age"])) {
    echo "<p>Age: " . $_POST["age"] . "</p>";
}

if (isset($_POST["food"])) {
    echo "<p>Food Preference: " . $_POST["food"] . "</p>";
}

if (isset($_POST["partysize"])) {
    echo "<p>Number of Travellers: " . $_POST["partysize"] . "</p>";
}

?>

</body>
</html>