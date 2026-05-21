# Shooting-game
 A game that I've created ( btw this is my first repository.)
 Creator: Harshit Singh Negi
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Star Hunter</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    overflow:hidden;
    background:black;
    color:white;
}

canvas{
    background:black;
    display:none;
    cursor:none;
}

#menu{
    position:absolute;
    inset:0;
    display:flex;
    justify-content:center;
    align-items:center;
    flex-direction:column;
    gap:20px;
    background:black;
    z-index:20;
}
