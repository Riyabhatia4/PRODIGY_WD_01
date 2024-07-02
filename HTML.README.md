# PRODIGY_WD_01
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Respnsive Navbar</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        
        <ul class="sidebar">
        <li onclick="hidesidebar"><a href="#"><svg xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 50 50" width="26" height="26"><path d="M 7.71875 6.28125 L 6.28125 7.71875 L 23.5625 25 L 6.28125 42.28125 L 7.71875 43.71875 L 25 26.4375 L 42.28125 43.71875 L 43.71875 42.28125 L 26.4375 25 L 43.71875 7.71875 L 42.28125 6.28125 L 25 23.5625 Z"/></svg></a></li>
        <li><a href="#">ABOUT</a></li>
        <li><a href="#">PRODUCTS</a></li>
        <li><a href="#">BLOGS</a></li>
        <li><a href="#">LOGIN</a></li>
    </ul>
        <ul>
            <li><a href="#">HOME</a></li>    
            <li class="hideOnMobile"><a href="#">ABOUT</a></li>
            <li class="hideOnMobile"><a href="#">PRODUCTS</a></li>
            <li class="hideOnMobile"><a href="#">BLOGS</a></li>
            <li class="hideOnMobile"><a href="#">LOGIN</a></li>
            <li class="menu-button" onclick=showsidebar()><a href="#"><svg width="26" height="26" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" fill="none">
                <path fill="#000000" fill-rule="evenodd" d="M19 4a1 1 0 01-1 1H2a1 1 0 010-2h16a1 1 0 011 1zm0 6a1 1 0 01-1 1H2a1 1 0 110-2h16a1 1 0 011 1zm-1 7a1 1 0 100-2H2a1 1 0 100 2h16z"/>
              </svg></a></li>
        </ul>
 </nav>  
    <script>
        function showsidebar(){
            const sidebar = document.querySelector('.sidebar') 
            sidebar.style.display = 'flex'
        }
        function hidesidebar(){
            const sidebar = document.querySelector('.sidebar') 
            sidebar.style.display = 'none'
        }
        </script>          
</body>
</html>
