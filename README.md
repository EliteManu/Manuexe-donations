# Manuexe-donations
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
<title>Manuexe Donations | Official Donation Page</title>

    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Manuexe Donations</h1>
<p>Official Local Bank Transfer Donation Page</p>
</header>

<section class="donation-box">

    <h2>Bank Transfer Details</h2>

    <div class="bank-details">
        <div class="bank-details">
    <p><strong>Bank Name:</strong>Palmpay </p>
    <p><strong>Account Name:</strong> Nnokam Sarima</p>
    <p><strong>Account Number:</strong> 9027642185</p>
</div>


    <hr>

    <h3>Confirm Your Donation</h3>

    <form id="donationForm">
        <input type="text" placeholder="Full Name" required>
        <input type="number" placeholder="Amount Sent (₦)" required>
        <input type="text" placeholder="Transaction Reference (optional)">
        <button type="submit">Submit Confirmation</button>
    </form>

    <p class="note">💙 After transferring, please submit confirmation.</p>

</section>

<footer>
    <p>© 2026 Manuexe. All rights reserved.</p>
</footer>

<script src="script.js"></script>
</body>
</html>
<a 
  href="https://wa.me/2349027642185?text=Hello%20Manuexe,%20I%20have%20made%20a%20bank%20transfer.%20Here%20are%20my%20details:"
  class="whatsapp-btn"
  target="_blank"
>
    📲 Confirm Payment on WhatsApp
</a>
/* RESET */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

/* BODY */
body {
    background-color: #f4f6f8;
    text-align: center;
    min-height: 100vh;
}

/* HEADER */
header {
    background-color: #111827;
    color: #ffffff;
    padding: 30px 15px;
}

header h1 {
    font-size: 36px;
    margin-bottom: 8px;
}

header p {
    font-size: 16px;
    opacity: 0.9;
}

/* DONATION BOX */
.donation-box {
    background-color: #ffffff;
    width: 90%;
    max-width: 400px;
    margin: 40px auto;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 8px 20p
document.getElementById("donationForm").addEventListener("submit", function(e) {
    e.preventDefault();

    alert(
        "Thank you for donating to Manuexe 💙\n" +
        "Your bank transfer confirmation has been received."
    );

    this.reset();
});

