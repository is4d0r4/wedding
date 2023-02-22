<template>
        <navbar>
            <h2 class="logo">Ciel e Isa</h2>
                <ul>
                    <li><a href="#">10 de junho - 18:30h</a></li>
                    <li><a href="#">Espaço dos Fiéis, Portão, nº 18</a></li>
                    <button type="button">Noivado/Chá de Casa Nova</button>
                </ul>
        </navbar>
</template>
<script>
export default {

}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300&family=Dancing+Script:wght@400;600&family=Great+Vibes&display=swap');

    navbar{
        /* background-color: #FF9B43; */
        background-image: linear-gradient(to right, #FF9B43 , #fdba7f);
        display: flex;
        align-items: center;
        justify-content:space-between;
        padding-top: 2px;
        padding-left: 10%;
        padding-right: 10%;
    }

    .logo{
        font-size: 38px;
        color: white;
        text-shadow: 1px 2px #e67c1f;
        font-family:'Dancing Script', cursive;
    }

    navbar ul li {
        font-family: 'Comfortaa', cursive;
        list-style-type: none;
        display: inline-block;
        padding: 10px 20px;
    }

    navbar ul li a {
        font-size: 18px;
        color: white;
        font-family: 'Comfortaa', cursive;
        text-decoration: none;
    }

    navbar ul li a:hover {
        color: #376367;
        transition: .3s;
        font-family: 'Comfortaa', cursive;
        text-decoration: none;
    }
    
    button {
        border: none;
        background: #FD671A;
        padding: 12px 30px;
        border-radius: 30px;
        font-family: 'Comfortaa', cursive;
        font-weight: bold;
        color: white;
    }

    button:hover {
        background: #973d11;
    }
</style>