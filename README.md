<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment: 01 & 02</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            position: relative;
            background-image: url('https://media.istockphoto.com/vectors/chinese-background-vector-id488178793?k=6&m=488178793&s=612x612&w=0&h=Yr_W89G0lYaVw7NSyYGG5jmPFCD08VzTkSJultCeM0M='); /* New background image */
            background-size: cover; /* Cover the full page */
            background-position: center;
            background-repeat: no-repeat;
            height: 100vh; /* Ensure the height covers the full viewport */
            display: flex;
            justify-content: center; /* Horizontally center content */
            align-items: center; /* Vertically center content */
            text-align: center;
        }

        .content {
            display: flex;
            flex-direction: column; /* Stack elements vertically */
            align-items: center;
            z-index: 1;
        }

        h1 {
            font-size: 48px;
            color: #333;
            margin: 0;
        }

        h2 {
            font-size: 20px;
            color: red;
            margin: 10px 0; /* Add some space between the h1 and h2 */
        }

        /* Watermark style */
        .watermark {
            font-size: 100px;
            color: rgba(0, 0, 0, 0.1); /* Semi-transparent */
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%); /* Center the watermark */
            pointer-events: none; /* Make sure the watermark doesn't interfere with clicking */
        }

        /* Button Style */
        .button-91 {
            color: #fff;
            padding: 15px 25px;
            background-color: #38D2D2;
            background-image: radial-gradient(93% 87% at 87% 89%, rgba(0, 0, 0, 0.23) 0%, transparent 86.18%),
                              radial-gradient(66% 66% at 26% 20%, rgba(255, 255, 255, 0.55) 0%, rgba(255, 255, 255, 0) 69.79%, rgba(255, 255, 255, 0) 100%);
            box-shadow: inset -3px -3px 9px rgba(255, 255, 255, 0.25),
                        inset 0px 3px 9px rgba(255, 255, 255, 0.3),
                        inset 0px 1px 1px rgba(255, 255, 255, 0.6),
                        inset 0px -8px 36px rgba(0, 0, 0, 0.3),
                        inset 0px 1px 5px rgba(255, 255, 255, 0.6),
                        2px 19px 31px rgba(0, 0, 0, 0.2);
            border-radius: 14px;
            font-weight: bold;
            font-size: 16px;
            border: 0;
            user-select: none;
            -webkit-user-select: none;
            touch-action: manipulation;
            cursor: pointer;
            margin-top: 20px; /* Add some margin to separate from the title */
        }

        .button-91:hover {
            background-color: #30B3B3; /* Darker background on hover */
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>WELCOME SIR!!!</h1>
        <h2>Assignment: 01 & 02</h2>

        <!-- View My Assignment Button -->
        <div class="view-assignment">
            <button class="button-91" onclick="window.open('https://drive.google.com/file/d/1rGG999t2W1xA6uDwXmwq23LQphdYYGq0/view?usp=drivesdk', '_blank')">View My Assignment</button>
        </div>
    </div>

    <!-- Watermark -->
    <div class="watermark">web technology</div> 
</body>
</html>
