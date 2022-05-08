# rinbow-image

#HTML:=

                  <!DOCTYPE html>
<html>

<head>
      <link rel="stylesheet" href="madan.css">
</head>
<body>

<img src="C:\Users\LEGION\Downloads\WhatsApp Image 2022-05-08 at 12.51.33 PM.jpeg" class="blob"  />

    </body>



    </html>
    
    #CSS:=
    
                 .blob{
    animation:hue-animation 5s alternate infinite;
    animation-delay: .5s;
    height: 100%;
    width: 300px;
   

}
@keyframes hue-animation{
    100%{
      filter: hue-rotate(360deg);
    }
    500%{
        filter: hue-rotate(360deg);
    }
}

    
    
    
