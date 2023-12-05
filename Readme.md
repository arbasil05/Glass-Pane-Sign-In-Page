# Simple Form Using HTML and CSS :

In this repository, you'll find a simple form I created using HTML and CSS. As my inaugural project, I encountered various challenges and learned valuable lessons along the way. I'm excited about the progress I've made, and I'm optimistic about the improvements that lie ahead in my coding journey.

# Preview :

![Result](https://github.com/arbasil05/Glass-Pane-Sign-In-Page/assets/144218037/9c42906f-038f-4972-9d63-79c292735767)



# HTML Code :

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms</title>
    <link rel="stylesheet" href="style/forms.css">
</head>
<body>
    <div class="container">
        <p class="Title">Sign in</p>
        <p class="subtitle">Welcome :)</p>
        <input type="email" class="Email" placeholder="Email or Phone">
        <input type="password" class="password" placeholder="Password">
        <p class="bottom-text">Forgot password?</p>
        <button class="button">Sign in</button>
    </div>
  
</body>
</html>

```

# CSS Code :
```
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

}
body{
    background-image: url("images/form\ bg.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
}
.container{
    height: 517.975px;
    width: 352px;
    border: solid 1px black;
    margin: auto;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
    padding:  24px;
    position: absolute;
    background: rgba(219, 214, 214, 0.8);
    backdrop-filter: saturate(150%) blur(10px);
    border: none;
    border-radius: 20px;
    flex-wrap: wrap;
    
    
}
.Email{
    height: 52px;
    width: 100%;
    padding: 10px; 
    border-radius: 4px;
    border: none;
}
.Email:active{
    border: none;
}
.password{
    margin-top: 20px;
    height: 52px;
    width: 100%;
    padding: 10px; 
    border-radius: 4px;
    border-style: solid;
    border: none;
}
.Title{
    color:#e12159;
    font-size: 3.2rem;
    font-weight: 600;
   /* margin-left: -140px;*/
    
    
}
.subtitle{
    font-size: 0.9rem;
    line-height: 1.42857;
    font-weight: 400;
    color:#e12159;
    /*margin-left: -70px;*/
    
}
.button{
    width: 256px;
    height: 52px;
    padding-left: 24px;
    padding-right: 24px;
    background-color: #e12159;
    color: white;
    border: none;
    border-radius: 80px;
    transition: background-color 0.5s;
}
.button:hover{
    cursor: pointer;
    background-color: #0073b194;
}
.bottom-text{
    color: #e12159;
    font-weight: 600;
    transition: color 0.5s;
}
.bottom-text:hover{
    cursor: pointer;
    color: #0073b194;
}


```

# References : 
## Background image:
- [Background image](https://www.pexels.com/photo/photo-of-foggy-forest-1367192/)

## Backdrop filter aka Glassy effect: 
- [Backdrop-Filter](https://css-tricks.com/backdrop-filter-effect-with-css/)

