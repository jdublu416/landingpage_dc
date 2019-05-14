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
    background-color: #8193ab;
    opacity: .6;
    height: 120px;
    
}

.logo{
    width:20%;
    font-size: 1.5em;
    padding: 25px 50px;
}
.logo span{
color: hsl(203, 26%, 28%);


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
    
}

.nav-list-item a {
    color: black;
    text-decoration: none;
    
}
</style>

