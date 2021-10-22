<template>
    <div>
        <div class="header">
            <img class="logo" v-bind:src="require('./icons/LogoSearchlook.png')" alt="Logo" />
            <span class="head">{{ mainText }} </span>
            
            <div class="left-container">
               
                    <div   class="icons" >
                    <img v-bind:src="require('./icons/materialIcons/Menu.png')" alt="Menu">
                </div>
             
                <div class="search-box" >
                    <input class="input-field" type="text">
                    <img v-bind:src="require('./icons/materialIcons/LupaBuscador.png')" alt="">
                </div>
                <div class="menu-box" >
                    
                    <img v-bind:src="require('./icons/DesktopIcons/Ayuda1.png')" alt="">
                    <img v-bind:src="require('./icons/DesktopIcons/Consultar.png')" alt="">
                    <img v-bind:src="require('./icons/DesktopIcons/Cupones1.png')" alt="">
                    <img v-bind:src="require('./icons/DesktopIcons/Perfil1.png')" alt="">
                </div>
            </div>
        </div>
        <div class="main-container">
            <div class="menu-box" v-if="seen" id="hide">
                <img v-bind:src="require('./icons/DesktopIcons/Ayuda1.png')" alt="">
                    <img v-bind:src="require('./icons/DesktopIcons/Consultar.png')" alt="">
                    <img v-bind:src="require('./icons/DesktopIcons/Cupones1.png')" alt="">
                    <img v-bind:src="require('./icons/DesktopIcons/Perfil1.png')" alt="">
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
                              
                                
                                  
                                        
                                            <th><div class="head3"><img v-bind:src="require('./icons/MenuPrincipal/Fecha-y-Hora.png')" alt=""></div></th>
                                <th><div class="head3"><img v-bind:src="require('./icons/MenuPrincipal/Nombre-Candidato.png')" alt=""></div> </th>
                                <th><div class="head3"><img v-bind:src="require('./icons/MenuPrincipal/Correo-Candidato.png')" alt=""></div></th>
                                  
                                       
                                
                                <th><img v-bind:src="require('./icons/MenuPrincipal/Referencias-Laborales.png')" alt=""></th>
                                  <th><img v-bind:src="require('./icons/MenuPrincipal/Referencias-Laborales.png')" alt=""></th>
                                    <th><img v-bind:src="require('./icons/MenuPrincipal/Referencias-Laborales.png')" alt=""></th>
                               
                               
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
                                     <img class="icon" v-bind:src="require('./icons/star.png')" >
                                </td>
                                <td>01/02/2021 <br /> 09:01 am</td>
                                <td>Karla Moreno</td>
                                  <td><div class="mail">karlamoreno@gmail.com</div></td>
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
                                   <img class="icon" v-bind:src="require('./icons/star.png')" >
                                </td>
                                <td>01/02/2021 <br /> 09:01 am</td>
                                <td>Karla Moreno</td>
                                <td><div class="mail">karlamoreno@gmail.com</div></td>
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
                                     <img class="icon" v-bind:src="require('./icons/star.png')" >
                                </td>
                                <td>01/02/2021 <br /> 09:01 am</td>
                                <td>Karla Moreno</td>
                                <td><div class="mail">karlamoreno@gmail.com</div></td>
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
                                    <img class="icon" v-bind:src="require('./icons/star.png')" >
                                </td>
                              
                                    <td>01/02/2021 <br /> 09:01 am</td>
                                <td>Karla Moreno</td>
                                  <td><div class="mail">karlamoreno@gmail.com</div></td>
                              
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


body{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
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
       display: none;
        
    } 
    .menu-box img{
       
        width:auto;
        height: auto;
        margin: auto;
      
    }
    .header{
       width:100%;
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
        width: 500px;
        display: flex;
        flex-direction: row;
       
        justify-content: space-between;
       
    }
    
    .left-container .icons img{
        margin-left: 10px;
        display: none;
    }
     .search-box input{
        width: 500px;
        height: 30px;
     margin-left: -20px;
        
       
        
    }
    .search-box img{
        position: absolute;
        right: 30px;
        top: 75px;
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
        padding: 4px 24px;
       
        /* word-wrap: break-word; */
        white-space: nowrap;
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

.nav3{
   position: absolute;
   left: 150px;
}


@media screen and (max-width: 1308px) {
   th,td, img{
       margin-left: -10px;
        width: 35px;
    }


    

  
}



@media screen and (max-width: 1230px) {
     th,td, img{
        margin-left: -15px;
        width: 32px;
    }
    td{
        font-size: 13px;
    }
.menu-box{
    width: 4vw;
    height: 80vh;
}
.menu-box img{

width: 100%;
}

}



@media screen and (max-width: 1080px) {
     th,td, img{
        margin-left: -18px;
        width: 27px;
    }
    td{
        font-size: 12px;
    }
}

@media screen and (max-width: 1001px) {
     th,td, img{
        margin-left: -20px;
        width: 25px;
    }
    td{
        font-size: 11px;
    }


}

@media screen and (max-width: 976px) {
     th,td, img{
        margin-left: -50px;
        width: 24px;
    }
    td{
        font-size: 11px;
    }

    
     .left-container .icons img{
        display: block;
        right: 8%;
        position: absolute;
    } 

    .header{
        position:absolute;
        top: 0%;
    }
    .search-box{
        position: relative;
        top: 160%;
        
    }

    .search-box img{
        top: 40%;
    }

    .head , .logo{
        margin-left: 10px;
    }





    .data-container{
       position: relative;
       top: 50px;
    }
}

@media screen and (max-width: 882px) {
     th,td, img{
        margin-left: -60px;
        width: 22px;
    }
     td {
        padding: 4px 18px;
       
        /* word-wrap: break-word; */
        white-space: nowrap;
    }


    
    
}


@media screen and (max-width: 851px) {
    th ,td img{
        margin-left: -50px;
        width: 22px;
    }
   

  

  
.menu-box img{
    width: 22px;
}

 .select-button .outer{
     width: 10px;
     height: 10px;
 }
 .select-button .inner{
height: 10px;
     width: 10px;
 }




    
}



@media screen and (max-width: 843px) {

       th, td,img{
       
        width: 20px;
       

    }

   



   

   

}
@media screen and (max-width: 810px) {
   

   td, th, img{
       
        width: 20px;

    }

    td{
        font-size: 10px;
    }

    .select-button{
        margin-left: 12px;
    }
    
}

@media screen and (max-width: 772px) {
  .data-container{
      position: relative;
      left: -30px;
  }
}

@media screen and (max-width: 765px) {
    
   

    table{
      
         width: calc(70%); 
    }

  td , tr  , img{
     
      padding-left:-100px;
  }

   
}


@media screen and (max-width: 739px) {
      th,td, img{
       
        width: 19px;
       
    }

    th, td {
        padding: 4px 18px;
       
        /* word-wrap: break-word; */
        white-space: nowrap;
    }

td img{
  width: 20px;

}




  img{
      padding: 4px 15px;
  }

    .menu-box img{
    width: 8px;
}

 .select-button .outer{
     width: 5px;
     height: 5px;
 }
 .select-button .inner{
height: 5px;
     width: 5px;
 }

 .menu-box{
    width: 20px;
 }
}
    

    @media screen and (max-width: 717px) {


        .search-box input{
            width: 300px;
            height: 30px;
           
        }

        .head{
            font-size: 12px;
          
            width: 300px;
        }



.mail{
  
    position: relative;
    left: -28px;
  
}

td img{
    width: 15px;
    margin-left: -102px;
    padding: 3px 0px;
}

  th,td, img{
       padding: 3px 18px;
        width: 15px;
       margin-left: -102px;
    }


.head3{
    position: relative;
    left: 30px;
}
    }
@media screen and (max-width: 663px) {
   th,td, img{
       
        width: 15px;
       
    }



    .icon{
        width: 15px;
        height: 15px;
    }

    .search-box{
        left: -40px;
    }

    th, td {
        padding: 4px 18px;
       
        /* word-wrap: break-word; */
        white-space: nowrap;
    }
     .select-button .outer{
     width: 3px;
     height: 3px;
 }
 .select-button .inner{
height: 3px;
     width: 3px;
 }

 .menu-box{
    width: 15px;
 }
}

@media screen and (max-width: 619px) {
    th,td, img{
       
        width: 15px;
       
    }
 .mail{
     margin: 0 12px;
 }

    th, td {
        padding: 4px 16px;
       
        /* word-wrap: break-word; */
        white-space: nowrap;
    }
}

@media screen and (max-width: 575px) {
    th,td, img{
       
        width: 10px;
       
    }

    th, td {
        padding: 4px 14px;
       
        /* word-wrap: break-word; */
        white-space: nowrap;
    }
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