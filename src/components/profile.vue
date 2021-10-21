<template>
    <div>
        <div class="header">
            <img class="logo" v-bind:src="require('./icons/LogoSearchlook.png')" alt="Logo" />
            <span class="head">{{ mainText }} </span>
            
            <div class="left-container">
                <div class="icons">
                    <img v-bind:src="require('./icons/materialIcons/Menu.png')" alt="Menu">
                </div>
                <div class="search-box" v-if="searchBox">
                    <input class="input-field" type="text">
                    <img v-bind:src="require('./icons/materialIcons/LupaBuscador.png')" alt="">
                </div>
                <div class="menu-box" v-if="menubox">
                    <img v-bind:src="require('./icons/materialIcons/LupaBuscador.png')" alt="">
                    <img v-bind:src="require('./icons/materialIcons/LupaBuscador.png')" alt="">
                    <img v-bind:src="require('./icons/materialIcons/LupaBuscador.png')" alt="">
                    <img v-bind:src="require('./icons/materialIcons/LupaBuscador.png')" alt="">
                </div>
            </div>
        </div>
        <div class="main-container">
            <div class="menu-box">
                <img v-bind:src="require('./icons/materialIcons/LupaBuscador.png')" alt="">
                <img v-bind:src="require('./icons/materialIcons/LupaBuscador.png')" alt="">
                <img v-bind:src="require('./icons/materialIcons/LupaBuscador.png')" alt="">
                <img v-bind:src="require('./icons/materialIcons/LupaBuscador.png')" alt="">
            </div>
            <div class="data-container">
                    <table>
                        <thead>
                            <tr>
                                <th>
                                    <div class="select-button">
                                        <div class="outer">
                                            <div class="inner"></div>
                                        </div>
                                        <div class="triangle"></div>
                                    </div>
                                </th>
                                <th><img v-bind:src="require('./icons/MenuPrincipal/Fecha-y-Hora.png')" alt=""></th>
                                <th><img v-bind:src="require('./icons/MenuPrincipal/Nombre-Candidato.png')" alt=""></th>
                                <th><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></th>
                                <th><img v-bind:src="require('./icons/MenuPrincipal/Referencias-Laborales.png')" alt=""></th>
                                <th><img v-bind:src="require('./icons/MenuPrincipal/Referencias-Laborales2.png')" alt=""></th>
                                <th><img v-bind:src="require('./icons/MenuPrincipal/Aprobac.png')" alt=""></th>
                                <th><img v-bind:src="require('./icons/MenuPrincipal/Reenviar.png')" alt=""></th>
                                <th><img v-bind:src="require('./icons/MenuPrincipal/Descarga.png')" alt=""></th>
                                <th><img v-bind:src="require('./icons/MenuPrincipal/Actualizar-Reporte.png')" alt=""></th>
                                <th><img v-bind:src="require('./icons/MenuPrincipal/Borrar.png')" alt=""></th>
                            </tr>
                        </thead>

                        <tbody>
                            <tr>
                                <td class="white-bg">
                                    <div class="select-button">
                                        <div class="outer">
                                            <div class="inner"></div>
                                        </div>
                                    </div>
                                    <img class="icon" v-bind:src="require('./icons/IconosRow/Estrella.png')" >
                                </td>
                                <td>01/02/2021 <br /> 09:01 am</td>
                                <td>Karla Moreno</td>
                                <td>karlamoreno@gmail.com</td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                            </tr>
                            <tr>
                                <td>
                                    <div class="select-button">
                                        <div class="outer">
                                            <div class="inner"></div>
                                        </div>
                                    </div>
                                    <img class="icon" v-bind:src="require('./icons/IconosRow/Estrella.png')" >
                                </td>
                                <td>01/02/2021 <br /> 09:01 am</td>
                                <td>Karla Moreno</td>
                                <td>karlamoreno@gmail.com</td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                            </tr>
                            <tr>
                                <td>
                                    <div class="select-button">
                                        <div class="outer">
                                            <div class="inner"></div>
                                        </div>
                                    </div>
                                    <img class="icon" v-bind:src="require('./icons/IconosRow/Estrella.png')" >
                                </td>
                                <td>01/02/2021 <br /> 09:01 am</td>
                                <td>Karla Moreno</td>
                                <td>karlamoreno@gmail.com</td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                            </tr>
                            <tr>
                                <td>
                                    <div class="select-button">
                                        <div class="outer">
                                            <div class="inner"></div>
                                        </div>
                                    </div>
                                    <img class="icon" v-bind:src="require('./icons/IconosRow/Estrella.png')" >
                                </td>
                                <td>01/02/2021 <br /> 09:01 am</td>
                                <td>Karla Moreno</td>
                                <td>karlamoreno@gmail.com</td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                                <td><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></td>
                            </tr>
                        </tbody>      
                        </table>
            </div>
        </div>
    </div>
</template>


<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap');
    @import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css');

    .triangle {
        width: 0;
        height: 0;
        border-left: 7px solid transparent;
        border-right: 7px solid transparent;
        border-top: 14px solid #edf3fe;
        margin: auto;
        margin-left: 10px;
    }
    .top-icons-row{
        display: flex;
        flex-direction: column;
        height: 9%;
        width: 100%;
        justify-content: center;
    }
    .select-button{
        display: inline-flex;
        width: 25px;
        height: 25px;
        justify-content: center;
    }
    .select-button .outer{
        background-color: #ecf4fe;
        width: 12.88px;
        height: 12.88px;
        border-radius: 100vw;
        padding: 7px;
    }
    .select-button .inner{
        background-color: tomato;
        width: 12.88px;
        height: 12.88px;
        border-radius: 100vw;
        justify-self: center;
    }

    .main-container{
        display: inline-flex;
        width: 97vw;
        height: 84vh;
    }
    .data-container{
        width: calc(90%) !important;
        height: 75vh;
        background-color: #ffffff;
        margin-left: 2vw;
        border-radius: 10px;
        border: 5px solid #eff4fa;
        overflow-y: scroll;
        overflow-x: hidden;
        padding: 20px;
        display: table;
    }
    .menu-box{
        background-color: #f1f1f1;
        display: flex;
        width: 5vw;
        height: 80vh;
        flex-direction: column;
        border-radius: 10px;
    }
    .menu-box img{
        background-color: #2c63c0;
        width: auto;
        height: auto;
        margin: auto;
        border-radius: 100px;
    }
    .header{
        width: 96vw;
        height: 3vw;
        background-color: #2c63c0;
        display: inline-flex;
        border-radius: 5px;
        padding: 10px;
        margin-bottom: 20px;
    }
    .head{
        margin-left: 3vw;
        margin-top: auto;
        margin-bottom: auto;
        font-size: 2.5vw;
        color: white;
        font-family: Calibri, sans-serif;
    }
    .header .logo{
        width: 10vw;
        height: 100%;
    }
    .left-container{
        height: inherit;
        margin-left: auto;
        width: 100px;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }
    .left-container .icons{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }
    .left-container .icons img{
        margin-left: 10px;
    }
    
    body {
        font-family: 'Inter', sans-serif;
        color: #343a40;
        line-height: 1;
        display: flex;
        justify-content: center;
    }

    table {
        border-right-color: #ffffff;
        border-collapse: separate;
        border-spacing: 0 10px; 
        table-layout: auto;
        width: calc(90%); 
    }
    
    th, td {
        padding: 3px 24px;
        text-align: center;
        /* word-wrap: break-word; */
        white-space: nowrap;
    }

    th {
        position: sticky;
        top:0;
    }
    th,td img{
        margin-left: 30%;
    }

    tbody{
        background-color: #fff;
    }
    
    tbody tr{
        margin-top: 20px !important;
    }
    table td:first-child{
        padding: 0px;
        background-color: transparent;
    }
    table td{
        background-color:#eff4fa;
    }
    table td:nth-child(2){
        border-radius: 10px 0 0 10px;
    }
    table td:last-child{
        border-radius: 0 10px 10px 0;
    }
    .icon{
        width: 25px;
        height: 25px;
        margin-left: 10px;
}
</style>


<script>


export default {
    data() {
        return {
            mainText: "Pedro Pedz",
            head: "Buscador"
        }
    },
    methods: {
    },
}
</script>