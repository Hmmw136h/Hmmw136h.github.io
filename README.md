<!DOCTYPE html>
<html>
<head>
    <title>CSC Online Centre</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #1e90ff;
            color: white;
            padding: 20px;
        }

        section {
            padding: 20px;
        }

        .box {
            background: white;
            margin: 20px auto;
            padding: 20px;
            width: 80%;
            max-width: 500px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }

        button {
            background-color: #25D366;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #1ebe5d;
        }
    </style>
</head>
<body>

<header>
    <h1>CSC Online Centre</h1>
    <p>Mobile Services & Printing Solutions</p>
</header>

<section>
    <div class="box">
        <h2>Our Services</h2>
        <p>📱 Mobile Recharge & Services</p>
        <p>🖨 Printing & Photocopy</p>
        <p>📄 Online Applications</p>
    </div>

    <div class="box">
        <h2>Location</h2>
        <p>Ambalam Road, Thara, Cherukunnu</p>
        <p>Pincode: 670331</p>
    </div>

    <div class="box">
        <h2>Opening Hours</h2>
        <p>9:00 AM – 6:00 PM</p>
    </div>

    <div class="box">
        <h2>Contact Us</h2>
        <button onclick="contact()">Call Now</button>
    </div>
</section>

<script>
function contact() {
    alert("Please contact CSC Online Centre directly for services.");
}
</script>

</body>
</html>
