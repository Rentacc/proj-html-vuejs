<script>
export default{
    props:{
        icon: String,
        title: String,
        description: String,
    }
}


</script>
<template>
            <ul>
                <li>
                <div class="icon"><img :src="icon" alt=""></div>
                </li>
                <li>
                    <div class="title">{{ title }}</div>
                </li>
                <li>
                    <div class="description">{{ description }}</div>
                </li>
            </ul>




</template>


<style scoped>

.icon{
    width: 70px;
}

.title{
    font-size: 25px;
   
}

ul li{
    list-style: none;
}

.card {
  transition: color 0.3s ease; /* Transizione del colore durante l'hover */
}

.card:hover .title {
  color: red; /* Colore del titolo durante l'hover */
}


</style>