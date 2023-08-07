# Clavia-0711.github.io
Tienda Online Look at me
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda Online Look at me</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <link href="css/estilos.css" rel="stylesheet" >
     
   


</head>

<body>


    <header>

        <div class="navbar navbar-expand-lg navbar-dark bg-info">
            <div class="container">
                <a href="#" class="navbar-brand ">

                    <strong><i>Look At Me</i></strong>&nbsp
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-camera2" viewBox="0 0 16 16">
                        <path d="M5 8c0-1.657 2.343-3 4-3V4a4 4 0 0 0-4 4z" />
                        <path d="M12.318 3h2.015C15.253 3 16 3.746 16 4.667v6.666c0 .92-.746 1.667-1.667 1.667h-2.015A5.97 5.97 0 0 1 9 14a5.972 5.972 0 0 1-3.318-1H1.667C.747 13 0 12.254 0 11.333V4.667C0 3.747.746 3 1.667 3H2a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1h.682A5.97 5.97 0 0 1 9 2c1.227 0 2.367.368 3.318 1zM2 4.5a.5.5 0 1 0-1 0 .5.5 0 0 0 1 0zM14 8A5 5 0 1 0 4 8a5 5 0 0 0 10 0z" />
                    </svg>
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarHeader" aria-controls="navbarHeader" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarHeader">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a href="#" class="nav-link active">Catálogo</a>

                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link ">Contacto</a>

                        </li>
                    </ul>

                   
                    <a href="checkout.php" class="btn btn-dark me-2">
                        Carrito <span id="num_cart" class="badge bg-secondary" >1</span>
                    </a>

                    <a href="login.php" class="btn btn-success" > <i class="fas fa-user"></i> </a>



                </div>

            </div>
        </div>
    </header>

    <main>
        <div class="container">
            <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">
                                <div class="col">
                    <div class="card shadow-sm">
                                       
                
              
              
                       
                       
                    <center><img src="./images/look at me.gif" height="100%" width="100%"></center>
                        <div class="card-body">
                            <h5 class="card-title">Poleras para parejas</h5>
                            <p class="card-text">$16.39</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="btn-group">
                                    <a href="detalles.php?id=1&token=bf072c2eadbfadc7cd53cf14a205624f33357ac7" class="btn btn-danger">Detalles</a>
                                </div>
                                <button class="btn btn-outline-success" type="button" onclick="addProducto(1,'bf072c2eadbfadc7cd53cf14a205624f33357ac7')">Agregar al Carrito</button>
                            </div>
                        </div>
                    </div>
                </div>
                                <div class="col">
                    <div class="card shadow-sm">
                                       
                
              
              
                       
                       
                    <center><img src="./images/look at me.gif" height="100%" width="100%"></center>
                        <div class="card-body">
                            <h5 class="card-title">Pantalones</h5>
                            <p class="card-text">$8.19</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="btn-group">
                                    <a href="detalles.php?id=3&token=b68ac8fa63b0224c48a1ec5033a77a19561758f8" class="btn btn-danger">Detalles</a>
                                </div>
                                <button class="btn btn-outline-success" type="button" onclick="addProducto(3,'b68ac8fa63b0224c48a1ec5033a77a19561758f8')">Agregar al Carrito</button>
                            </div>
                        </div>
                    </div>
                </div>
                                <div class="col">
                    <div class="card shadow-sm">
                                       
                
              
              
                       
                       
                    <center><img src="./images/look at me.gif" height="100%" width="100%"></center>
                        <div class="card-body">
                            <h5 class="card-title">Shorts</h5>
                            <p class="card-text">$8.19</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="btn-group">
                                    <a href="detalles.php?id=6&token=e8a60e261a239252a225ee4dbc3efa32a60e832d" class="btn btn-danger">Detalles</a>
                                </div>
                                <button class="btn btn-outline-success" type="button" onclick="addProducto(6,'e8a60e261a239252a225ee4dbc3efa32a60e832d')">Agregar al Carrito</button>
                            </div>
                        </div>
                    </div>
                </div>
                                <div class="col">
                    <div class="card shadow-sm">
                                       
                
              
              
                       
                       
                    <center><img src="./images/look at me.gif" height="100%" width="100%"></center>
                        <div class="card-body">
                            <h5 class="card-title">Zapatillas</h5>
                            <p class="card-text">$13.66</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="btn-group">
                                    <a href="detalles.php?id=9&token=c7ed1afe30d0c1e5ef3eacd473f4640d7bcea890" class="btn btn-danger">Detalles</a>
                                </div>
                                <button class="btn btn-outline-success" type="button" onclick="addProducto(9,'c7ed1afe30d0c1e5ef3eacd473f4640d7bcea890')">Agregar al Carrito</button>
                            </div>
                        </div>
                    </div>
                </div>
                                <div class="col">
                    <div class="card shadow-sm">
                                       
                
              
              
                       
                       
                    <center><img src="./images/look at me.gif" height="100%" width="100%"></center>
                        <div class="card-body">
                            <h5 class="card-title">Outfit Completo</h5>
                            <p class="card-text">$40.98</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="btn-group">
                                    <a href="detalles.php?id=11&token=2615e9ed3c9e64dfb1d4a913573dba6e5d2b0ab4" class="btn btn-danger">Detalles</a>
                                </div>
                                <button class="btn btn-outline-success" type="button" onclick="addProducto(11,'2615e9ed3c9e64dfb1d4a913573dba6e5d2b0ab4')">Agregar al Carrito</button>
                            </div>
                        </div>
                    </div>
                </div>
                                <div class="col">
                    <div class="card shadow-sm">
                                       
                
              
              
                       
                       
                    <center><img src="./images/look at me.gif" height="100%" width="100%"></center>
                        <div class="card-body">
                            <h5 class="card-title">Accesorios</h5>
                            <p class="card-text">$0.00</p>
                            <div class="d-flex justify-content-between align-items-center">
                                <div class="btn-group">
                                    <a href="detalles.php?id=13&token=4ec1a2defb11d63edcce3457fb1e6c440869595c" class="btn btn-danger">Detalles</a>
                                </div>
                                <button class="btn btn-outline-success" type="button" onclick="addProducto(13,'4ec1a2defb11d63edcce3457fb1e6c440869595c')">Agregar al Carrito</button>
                            </div>
                        </div>
                    </div>
                </div>
                               
                
                



            </div>
    </main>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
    <script>
        function addProducto(id,token){
            let url='clases/carrito.php'
            let formData=new FormData()
            formData.append('id',id)
            formData.append('token',token)

            fetch(url,{
                method:'POST',
                body:formData,
                mode:'cors'
            }).then(response=>response.json())
            .then(data=>{
                if(data.ok){
                    let elemento=document.getElementById("num_cart")
                    elemento.innerHTML=data.numero
                }
            } )

        }
    </script>
</body>

</html>
