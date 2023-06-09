<!DOCTYPE html>
<html>
<head>
  <title>Ethereum Payment Checker</title>
  <!-- Add any necessary CSS or external libraries -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
  <style>
    /* Add your custom CSS styles here */
    .container {
      max-width: 500px;
      margin: 0 auto;
      padding: 20px;
      text-align: center;
    }
    .btn {
      padding: 10px 20px;
      font-size: 16px;
      background-color: #007bff;
      color: #fff;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .result {
      margin-top: 20px;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Ethereum Payment Checker</h1>
    <button class="btn" onclick="checkPayment()">Check Payment</button>
    <div id="result" class="result"></div>
  </div>

  <!-- Include the Ether.js library -->
  <script src="https://cdn.ethers.io/lib/ethers-5.5.3.min.js"></script>
  <!-- Add your JavaScript code here -->
  <script>
    // Your code goes here
  </script>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
  <title>Lion Website</title>
  <style>
    #lion-head {
      width: 200px;
      height: 200px;
      background-color: red;
      border-radius: 50%;
      margin: 0 auto;
      position: relative;
    }

    #lion-head::before {
      content: "";
      position: absolute;
      top: -40px;
      left: 50%;
      transform: translateX(-50%);
      font-size: 18px;
      color: yellow;
    }
  </style>
</head>
<body>
  <div id="lion-head"></div>
  <h1>GET STARTED NOW</h1>
</body>
</html>
