<template>
    <div id="mynav" class="sidenav sticky-top">
        <a href="" id="whatsapp">WhatsApp <i class="bi bi-whatsapp text-light"></i></a>
        <a href="" id="facebook">Facebook <i class="bi bi-facebook text-light"></i></a>
        <a href="" id="instagram">Instagram <i class="bi bi-instagram text-light"></i></a>
        <a href="" id="linkedin">LinkedIn <i class="bi bi-linkedin text-light"></i></a>
    </div>
</template>

<style scoped>
#mynav a {
    position:absolute;
    left: -166px;
    transition: 0.3s;
    padding: 15px;
    width: 200px;
    text-decoration: none;
    font-size: 15px;
    color: white;
    border-radius: 0 5px 5px 0;
    margin-top: 100px;
    text-align: right;
}

#mynav a:hover{
    left:-0;
}

#whatsapp{
    top:300px;
    background-color: rgb(20, 20, 20);
}
#facebook{
    top:360px;
    background-color: rgb(20, 20, 20);
}
#instagram{
    top:420px;
    background-color: rgb(20, 20, 20);
}
#linkedin{
    top:480px;
    background-color: rgb(20, 20, 20);
}

@media only screen and (max-width: 767px){
    #whatsapp{
    top:150px;
    background-color: rgb(20, 20, 20);
}
#facebook{
    top:210px;
    background-color: rgb(20, 20, 20);
}
#instagram{
    top:270px;
    background-color: rgb(20, 20, 20);
}
#linkedin{
    top:330px;
    background-color: rgb(20, 20, 20);
}
}
</style>