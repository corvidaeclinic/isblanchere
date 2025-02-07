<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="style.css">

    <title>Document</title>
</head>

<body>
    <img id="blanc" src="./BLANC IS HERE.png">
    <!-- Blanc is here! -->
    <div class="textbox">
        <div class="header">
            <img src="https://gifcity.carrd.co/assets/images/gallery294/82453da5.gif?v=47652796">
            <p>welcome...!!!</p>
        </div>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi maxime amet unde ratione dicta labore ullam
            vel atque nostrum reprehenderit, perspiciatis sapiente accusantium repellat fugiat velit! Tempore minima
            modi iste.</p>
    </div>

    <div class="textbox">
        <div class="header">
            <img src="https://api.violets-purgatory.dev/v1/pfp">
            <p>Is blanc here?!</p>
        </div>
        <p>No</p>
    </div>


    <div class="textbox">
        <div class="header">
            <img src="https://api.violets-purgatory.dev/v1/pfp">
            <img src="https://api.violets-purgatory.dev/v1/pfp">
            <p>That's an image of Teto</p>
            <img src="https://api.violets-purgatory.dev/v1/pfp">
            <img src="https://api.violets-purgatory.dev/v1/pfp">
            <img src="https://api.violets-purgatory.dev/v1/pfp">
        </div>
        <p>No</p> 
    </div>

    <div class="textbox">
        <div class="header">
            <img src="https://api.violets-purgatory.dev/v1/pfp">
            <img src="https://api.violets-purgatory.dev/v1/pfp">
            <img src="https://api.violets-purgatory.dev/v1/pfp">
            <img src="https://api.violets-purgatory.dev/v1/pfp">
            <img src="https://api.violets-purgatory.dev/v1/pfp">
        </div>
        <p>KASANE TETO!!!!</p>
    </div>
</body>

</html>
[8:43 PM]
p {
    margin: 0;
    padding: 2px;

    font-size: .9rem;
    color: #ecaccb;

    font-family: -apple-system, system-ui, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif;
    /* Font list, color, and size are taken directly from tinyhouse
    replace with better ones if you want!! */
}

.textbox {
    background-color: white;
    box-shadow: 4px 4px 0px rgba(35, 35, 35, 0.18);
    border: 2px ridge #ecaccb;
    max-width: 300px;
    display: inline-block;
    margin: 10px;

    .header {
        width: 100%;
        
        border-bottom: 1px solid #edd0e3;
        background-color: #fde9f6;
        display: flex;
        padding: 5px 0px;

        p {
            display: inline-block;
            padding: 0 4px;
            font-style: italic;
        }

        img {
            padding: 0px 4px;
            max-width: 20px;
        }
    }

    p {
        padding: 8px;
    }
}

#blanc {
    max-width: 15%;
    position: fixed;

    bottom: 5px;
    right: 5px;
    
    z-index: 3;
}
