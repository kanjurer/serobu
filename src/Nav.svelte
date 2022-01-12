<script>

</script>

<style>
nav{
    display: flex;
    background-color: white;
    justify-content: space-between;
}

nav ul{
    list-style: none;
    display: flex;
    justify-content: space-evenly;
}

nav ul li{
    margin: 0px 10px;
}
nav ul li a{
    text-decoration: none;
    color: black;
}
nav ul li a:hover {
    color: gold;
}

#logo{
    max-width: 200px;
}

#post-button{
    border-radius: 50px;
    width:150px;
    margin: 10px;
    background-color: gold;
}
</style>

<nav>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Listings</a></li>
        <li><a href="#">About</a></li>
    </ul>
    <a href="#"><img id="logo" src = "logo.png" alt="logo" /></a>
    <button id="post-button">Post</button>
</nav>