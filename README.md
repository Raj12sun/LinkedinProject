*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    overflow: hidden;
}
body{
    background-image: url("https://images.unsplash.com/photo-1453614512568-c4024d13c247?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1032&q=80");
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
    width: 100vw;
    padding: 30px;
}
nav {
    display: flex;
    justify-content: space-between;
}
.logo{
    color: blue;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 25px;
    font-weight: 900;
    margin-left: 50px;
}
nav ul{
    display: flex;
    gap: 50px;
}
nav ul li a{
    text-decoration: none;
    color:blue;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 20px;
    font-weight: 800;
}
nav ul li a:hover{
    color: red;
    background-color: yellow;
}
nav button{
    width: 90px;
    height: 30px;
    margin-right: 100px;
    background-color: rgb(251, 18, 18);
    color: white;
    border: none;
    border-radius: 10px;
}
nav button:hover{
    background-color: yellow;
    color:black;
    cursor: pointer;
}
.main-section{
    padding-top: 200px;
    text-align: center;
}
.main-section h1{
    color:rgb(248, 248, 14);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 55px;
    font-weight: 900;
    
}
.main-section button{
    margin-top: 40px;
    height: 35px;
    width: 150px;
    background-color: rgb(251, 18, 18);
    color: white;
    border: none;
    border-radius: 10px;
} 
.main-section button:hover{
    background-color: pink;
}
