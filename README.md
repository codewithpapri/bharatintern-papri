# bharatintern-papri
  type="image/x-icon"
    />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Registration Successful</title>
  </head>
  <body
  >
    <title>Registration Complete</title>

    <style>
      /* Apply glassmorphism effect to the container */
      .container {
        background: rgba(255, 255, 255, 0.823); /* Set a semi-transparent white background */
        backdrop-filter: blur(10px); /* Apply a blur effect to the background */
        border-radius:15px; /* Rounded corners */
        padding: 30px;
        text-align: center;
      }

      /* Center the container vertically and horizontally */
      body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh; /* Ensure full viewport height */
        background-color: rgb(233, 233, 233);
      }
        body {
            background: linear-gradient(to right, #800080, #4B0082); 
            font-family: 'Times New Roman', Times, serif, sans-serif;
            margin: 0;
            overflow: hidden; 
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh; 
            position: relative;
        }

        .bubble {
            position: absolute;
            background-color: rgba(255, 255, 255, 0.5); 
            border-radius: 50%;
            animation: float 4s infinite; 
        }

        .bubble1 {
            width: 40px;
            height: 40px;
            top: 30%;
            left: 10%;
        }

        .bubble2 {
            width: 60px;
            height: 60px;
            top: 10%;
            left: 60%;
        }

        .bubble3 {
            width: 50px;
            height: 50px;
            top: 80%;
            left: 30%;
        }

        .bubble4 {
            width: 80px;
            height: 80px;
            top: 20%;
            left: 40%;
        }

        .bubble5 {
            width: 70px;
            height: 70px;
            top: 80%;
            left: 90%;
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-30px);
            }
        }

        .container {
            text-align: center;
            padding: 60px;
            background-color: rgba(255, 255, 255, 0.3); 
            border-radius: 20px; 
        }

        h1, p {
            color: #ffffff; 
            font-size: 30px; 
        }
    </style>
  </head>
  <body>
    <div class="bubble bubble1"></div>
    <div class="bubble bubble2"></div>
    <div class="bubble bubble3"></div>
    <div class="bubble bubble4"></div>
    <div class="bubble bubble5"></div>

    <div class="container">
      <h1>Registration Successful</h1>
      <h1> 🎉 Registration Successful !!</h1>
      <p>Thank you for registering.</p>
    </div>
  </body>
