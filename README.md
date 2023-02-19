<!DOCTYPE html>
<html lang="en"
 <head>
    <title>annn</title>
    <style>
        body{
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 90vh;
        }
        .container{
            background-color: rgb(245, 195, 203);
            padding: 1rem;
            border-radius: 10px;
            width: 300px;
        }
        .btn{
            padding: 0.5rem 2rem;
            border: none;
            outline: none;
            font-weight: bold;
            border-radius: 10px;
        }
        .btnPrimary{
            color: white;
            background-color: purple;
        }
        .btnSecondary{
            padding: 0.5rem 1rem;
            background-color: rgb(248, 118, 140);
        }
        .moving:hover{
            margin-left: 70px;
        }
    </style>
 </head>
 <body>
  <section class="container">
    <h2 class="text">ព្រមធ្វើសង្សារខ្ញំុអត់?💕</h2>
    <button class="btn btnPrimary">YES</button>
    <button class="btn btnSecondary moving">NO</button>
  </section>
  <script>
    const btnAgree = document.querySelector(".
    btnPrimary");
    const btnDisagree = document.querySelector(".
    btnSecondary");
    const text = document.querySelector(".text");

    btnAgree.addEventListener(click) ()=>{
        text.innerText = "លូវយើងជាសង្សារនិងគ្នាហើយ😘;"
    });
    btnDisagree.addEventListener("mouseover", ()=>{

    })
  </script>
 </body>
</html>
