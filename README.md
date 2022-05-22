<style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Hind', sans-serif;
            
        }
        .contact{
            position: relative;
            min-height: 100vh;
            padding: 50px 100px;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        .contact .content{
            max-width: 800px;
            text-align: center;
        }
        .contact .content h2{
            font-size: 36px;
            font-weight: bold;
            color: #5d781b;
        }

        .contact .content p {
            
            font-weight: 200px;
            color: #5d781b;
            
        }

        .container{
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 30px;
            
        }
        .container .contactinfo{
            width: 50%;
            display: flex;
            flex-direction: column;
        }
        .container .contactinfo .box{
            position: relative;
            padding: 20px 0px;
            display: flex;
        }
        .container .contactinfo .box .icon{
            min-width: 60px;
            height: 60px;
            justify-content: center;
            align-items: center;
            border: 50%;
            font-size: 22px;
        }
        .container .contactinfo .box .text{
            display: flex;
            margin-left: 20px;
            font-size: 16px;
          
            flex-direction: column;
            font-weight: 300px;
        }

        .container .contactinfo .box .text h2{
            color: #5d781b;
            font-weight: 500px;
        }

        .contactform{
            width: 40%;
            padding: 40px;
            background:white ;
        }
        .contactform h2{
            font-size: 30px;
            font-weight: 500;
        }

        .contactform .inputbox{
            position: relative;
            width: 100%;
            margin-top: 10px;
        }
        .contactform .inputbox input , .contactform .inputbox textarea{
            width: 100%;
            padding: 5px 0;
            font-size: 16px;
            margin: 10px 0;
            border: none;
            border-bottom: 2px solid #5d781b ;
            outline: none;
            resize: none;
        }
        .contactform .inputbox span{
            position: absolute;
            left: 0;
            padding: 5px 0;
            font-size: 16px;
            margin: 10px 0;
            pointer-events: none;
            transition: 0.5s;
            color: #666;

        }
        .contactform .inputbox input:focus ~ span,
        .contactform .inputbox input:valid ~ span,
        .contactform .inputbox textarea:focus ~ span,
        .contactform .inputbox textarea:valid ~ span
        {
            color: #e91e63;
            font-size: 12px;
            transform: translateY(-20px);
        }

        .contactform .inputbox input[type="submit"]{
            width: 100px;
            background:#5d781b ;
            border: none;
            cursor: pointer;
            padding: 10px;
            font-size: 18px;
        }
      @media(max-width:991px){
          .contact{
              padding: 50px;
          }
          .container{
              flex-direction: column;
          }
          .container .contactinfo{
              margin-bottom: 40px;
          }
          .container .contactinfo,.contactform {
              width: 100%;

          }

      }
    </style>
