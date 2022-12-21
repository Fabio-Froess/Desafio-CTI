<template>
<div>

    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css" integrity="sha512-YWzhKL2whUzgiheMoBFwW8CKV4qpHQAEuvilg9FAn5VJUDwKZZxkJNuGM4XkWuk94WCrrwslk8yWNGmY1EduTA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
        <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
        <title>Inicial</title>
    </head>
    <body>
     <header>
            <section class="user">
            <div class="ContainerUser">
                <div class="fotoUser">
                    <img alt="avatar" src="src/assets/avatar.png">
                </div>
                <div class="DadosUsuario">
                    <h2>Fábio Froes</h2>
                </div>
            </div>
            </section>
    </header>
        

    <section class="container">
        <div class="sidebar">
            <div class="menus_sideBar">
                <ul>

                    <a href="index.html" class="activeMenu">
                        <i class="fas fa-home"></i>
                        <li>Inicio</li>
                    </a>

                    <div class="menuAcordion">
                        <div class="acordion_content">
                            <div class="disponiveis">
                                <a href=""><li>Alunos</li></a>
                                <a href=""><li>Cursos</li></a>
                                <a href=""><li>Atividades</li></a>
                            </div>
                        </div>
                    </div>

                    <div class="aluno">
                    <a href="index.php?view=curso" class="Curso">
                        <i class="fas fa-tasks"></i>
                        <li>Cursos</li>
                    </a>
                    <a href="index.php?view=notas" class="Notas">
                        <i class="fas fa-table"></i>
                        <li>Notas</li>
                    </a>
                    <a href="index.php?view=professores" class="Professores">
                        <i class="fas fa-chalkboard-teacher"></i>
                        <li>Professores</li>
                    </a>
                    </div>
                    <a href="">
                        <font-awesome-icon icon="fas fa-sign-out-alt" />
                        <li>Sair</li>
                    </a>
                </ul>
            </div>
        </div>
            <main>
               

                <h1 class="Centralizar">Sistema de gerenciamento de módulos avaliativos</h1>

                

                <table>
                    <thead>  <!--Cabecalio da tabela-->
                        <tr>                     <!--Título da tabela-->
                            <th>ID</th>
                            <th>Nome </th>
                            <th>CPF</th>
                            <th>Data De Nascimento</th>
                            <th>Módulo</th>
                            <th>Situação</th>
                            <th>Ações</th>
                            
                        </tr>
                        </thead>
                    
                    <tbody>  <!--Corpo da tabela-->
                        <tr>                      <!--1 linha da tabela-->
                            <td>10001</td>
                            <td>Fábio Froes Froes Ferreira Caires</td>
                            <td>068.025.037-30</td>
                            <td>27/10/1998 - 23:59</td>
                            <td>Manutenção</td>
                            <td>Ativo</td>
                            <td>
                                <a href="#" class="icon">
                                    <i class="fas fa-ban fa-lg"></i>
                                </a>
                               <a href="#" class="icon1">
                                     <i class="fas fa-pen-square fa-lg"></i>
                               </a>
                            </td>
                        </tr>
                        <tr>                      <!--2 linha da tabela-->
                            <td>10002</td>
                            <td>Adriano Fernandes</td>
                            <td>024.021.478.65</td>
                            <td>17/03/1995 - 23:59</td>
                            <td>Manutenção</td>
                            <td>Ativo</td>
                            <td>
                                <a href="#" class="icon">
                                    <i class="fas fa-ban fa-lg"></i>
                                </a>
                               <a href="#" class="icon1">
                                     <i class="fas fa-pen-square fa-lg"></i>
                               </a>
                            </td>
                        </tr>
                        <tr>                      <!--3 linha da tabela-->
                            <td>10003</td>
                            <td>Edmilson Bastos</td>
                            <td>654.159.753.12</td>
                            <td>28/10/2021 - 23:59</td>
                            <td>Manutenção</td>
                            <td>Inativo</td>
                            <td>
                                <a href="#" class="icon">
                                    <i class="fas fa-ban fa-lg"></i>
                                </a>
                               <a href="#" class="icon1">
                                     <i class="fas fa-pen-square fa-lg"></i>
                               </a>
                            </td>
                        </tr>
                        <tr>                      <!--4 linha da tabela-->
                            <td>10004</td>
                            <td>Emmerson Sobrino</td>
                            <td>167.196.145.10</td>
                            <td>31/10/2021 - 23:59</td>
                            <td>Manutenção</td>
                            <td>Ativo</td>
                            <td>
                                <a href="#" class="icon">
                                    <i class="fas fa-ban fa-lg"></i>
                                </a>
                               <a href="#" class="icon1">
                                     <i class="fas fa-pen-square fa-lg"></i>
                               </a>
                            </td>
                        </tr>
                        <a class="btn">
                    <i class="fas fa-plus-circle"> NOVA ATIVIDADE</i>
                </a>
                    </tbody>
                        
                </table>

               
            </main>
    </section>
    </body>
    



</div>



</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style>

* {
    margin: 0;
    padding: 0;
    border: 0;
    box-sizing: border-box;
    vertical-align: baseline;
}
  
a {
    text-decoration: none;
}
  
ul {
    list-style: none;
}
  
button {
    cursor: pointer;
}


.user{
    width: 100%;
    height: auto;
    background-color: rgb(236, 236, 236);
}

.ContainerUser{
    display: flex;
    padding: 10px;
    padding: 15px 10px 10px 20px;
    width: 100%;
    margin: 0 auto;
}

.fotoUser img{
    width: 20px;
}


.DadosUsuario h2{
    font-size: 15px;
    font-family: Arial, Helvetica, sans-serif;
    color: #3358DD;
    text-transform: uppercase;
    padding-top: 5px;
}

.DadosUsuario h3{
    font-family: Arial, Helvetica, sans-serif;
    color: #808080;
    font-weight: 100;
}

.container{
    display: flex;
    flex-direction: row;
    width: 100%;
    height: 100%;
}

.sidebar{
    background-color: #3358DD;
    min-height: 100vh;
    width: 15%;
}

.menus_sideBar ul i{
    display: none;
}

.menus_sideBar ul li{
    color: #fff;
    font-size: 17px;
    font-family: Arial, Helvetica, sans-serif;
}

.menuAcordion > .acordion_content a{
    color:#fff;
}

.menuAcordion > .acordion_content ul li:hover{
    background: white;
    color: #000;
}

.menus_sideBar ul a{
    text-decoration: none;
}

.menus_sideBar ul li{
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 20px;
    transition: 0.8s;
}

.menus_sideBar button{
    border: 0;
    border-radius: 0;
    width: 100%;
    height: 40px;
    color: #fff;
    background: #3358DD;
    font-size: 17px;
    font-family: Arial, Helvetica, sans-serif;
    text-align: left;
    padding-left: 20px;
    transition: 0.8s;
    cursor: pointer;
}

.aluno {
    display: none;
}

.menus_sideBar button:hover{
    background: white;
    color: #3358DD;
}

.menus_sideBar ul li:hover{
    background: white;
    color: #3358DD;
}

.activeMenu li{
    color: #fffb00 !important;
}
.activeMenu:hover li{
    color: #3358DD !important;
}


table, th, td {
    border: 1px solid #000;
    text-align: center;
    padding: 0.8rem;
    margin: 15px;
    
  }
table{
    border-collapse: collapse;
}

.Centralizar{
    text-align: center;
    margin: 50px;
    font-size: 45px;
}

.btn{
    
    padding:10px;
    height:45px;
    font-size: 18px;
    color: white;
    background: #209915;
    border-radius: 5px;
    cursor: pointer;
    align-items: center;
    position: relative;
    left: 20%;
}

.icon{
    color: red;
    padding-right: 10px;

}
.icon1{
    color: #209915;
    padding-right: 10px;

}

@media (max-width: 900px) {
    .banners {
      flex-direction: column;
      align-items: center;
    }
  
    .bannerPrincipal img {
      max-width: 400px;
    }

    .menus_sideBar ul li {
        display: none;
    }

    .menus_sideBar ul i{
        color: #fff;
        padding-top: 15px;
        padding-bottom: 10px;
        text-align: center;
        transition: 0.8s;
        display: block;
    }

    .menus_sideBar ul i:hover{
        background: white;
        color: #3358DD;
    }

    .activeMenu i{
        color: #fffb00 !important;
    }
    .activeMenu:hover i{
        color: #3358DD !important;
    }
}
</style>