<template>
    <div class="header-comp-nav">
       <h1 class="logo">Data<span>Concepts</span></h1>
       <nav class='nav-bar-header'>
           <ul class="nav-list">
               <li class='nav-list-item'><a href="#">Work</a></li>
               <li class='nav-list-item'><a href="#">Services</a></li>
               <li class='nav-list-item'><a href="#">Insights</a></li>
               <li class='nav-list-item'><a href="#">Careers</a></li>
               <li class='nav-list-item'><a href="#">About</a></li>
               <li class='nav-list-item'><a href="#">Contact</a></li>
           </ul>
       </nav>
    </div>
</template>
<script>
export default {
    name: "Header"
}
</script>

<style scoped>
.header-comp-nav{
    /* background-color: #282f38; */
    background-image: linear-gradient(left, #516683, black);
    opacity: .6;
    height: 120px;
    margin-top:0;
    
}

.logo{
    width:30%;
    font-size: 1.5em;
    padding: 25px 50px;
    color:whitesmoke;
}
.logo span{
color: hsl(27, 80%, 52%);
opacity:0.8;


}
nav{
    float: right;
}
ul{
    text-decoration: none;
}

.nav-list-item{
    display:inline-block;
    text-decoration:none;
    padding: 5px 10px;
    text-transform: uppercase;
    color:whitesmoke;
    
}

.nav-list-item a {
    color: whitesmoke;
    text-decoration: none;
    
}
</style>

