<!DOCTYPE html>
<html lang="en">
      <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <meta name="description" content="" />
        <meta name="author" content="Yonatan Furman-Full Stack John Bryce 4587/87" />
        <meta name="generator" content="Hugo 0.88.1" />
        <title>My Shopping Cart</title>
    
        <link
          rel="canonical"
          href="https://getbootstrap.com/docs/5.1/examples/album/"
        />
        <link
          href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
          rel="stylesheet"
          integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
          crossorigin="anonymous"
        />
        <link
          rel="stylesheet"
          href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css"
        />
        <script
          src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
          integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
          crossorigin="anonymous"
        ></script>
    
        <!-- Bootstrap core CSS -->
        <link href="../assets/dist/css/bootstrap.min.css" rel="stylesheet" />
    
        <style>
            #mainId{
              background: linear-gradient(to left bottom #ffd2,#dbdd,#ff5);

            }
            #bodyId{
                background: linear-gradient(to left bottom 130,79,180);
            }
          .bd-placeholder-img {
            font-size: 1.125rem;
            text-anchor: middle;
            -webkit-user-select: none;
            -moz-user-select: none;
            user-select: none;
          }
    
          @media (min-width: 768px) {
            .bd-placeholder-img-lg {
              font-size: 3.5rem;
            }
          }

          img{
              width:186;
              height: 286;
          }
        </style>
      </head>
      <body id="bodyId">
        <header>
          <div class="collapse bg-dark" id="navbarHeader">
            <div class="container">
              <div class="row">
                <div class="col-sm-8 col-md-7 py-4">
                  <h4 class="text-white">About</h4>
                  <p class="text-muted">
                   Js mission- used Bootstrap and js Shopping Cart list.
                  </p>
                </div>
                <div class="col-sm-4 offset-md-1 py-4">
                  <h4 class="text-white">Contact</h4>
                  <ul class="list-unstyled">
                    <li>
                      <a href=" https://wa.me/+972586272326" class="text-white"
                      ></a>
                    </li>
                    <li>
                      <a
                        class="text-white"
                        ><i class="bi bi-facebook"></i
                      ></a>
                    </li>
                    <li>
                      class="text-white"
                        ><i class="bi bi-envelope"></i
                      ></a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div class="navbar navbar-dark bg-dark shadow-sm">
            <div class="container">
              <a href="#" class="navbar-brand d-flex align-items-center">
                <strong>My Shopping List</strong>
              </a>
              <button
                class="navbar-toggler"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#navbarHeader"
                aria-controls="navbarHeader"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="navbar-toggler-icon"></span>
              </button>
            </div>
          </div>
        </header>
    
        <main style="background: linear-gradient(to bottom left ,#dbdd,#ff5,#ffd2);">
          <section class="py-5 text-center container">
            <div class="row py-lg-5">
              <div class="col-lg-6 col-md-8 mx-auto">
                <h1 class="fw-light">Add Product</h1>
                <div style="padding: 10px">
                  <div id="Category">
                    <select id="category" class="form-select" aria-label="Default select example" required>
                        <option value="Drinks">Drinks</option>
                        <option value="Meat">Meat</option>
                        <option value="Dairy">Dairy</option>
                        <option value="Snacks">Snacks</option>
                        <option value="Basic">Basic</option>
                      </select>
                  </div>
                  <div  class="input-group mb-3" style="margin-top: 8px;">
                    <span  id="inputGroup-sizing-default">Product Name</span>
                    <input id="productName" type="text" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default" required>
                  </div>
                  <div class="input-group mb-3" style="margin-top: -0.5rem;">
                    <span  id="inputGroup-sizing-default">Price</span>
                    <input id="price" type="text" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default" pattern="\d*" maxlength="3" required>
                  </div>
                  <div class="input-group mb-3" style="margin-top: -0.5rem;">
                    <span  id="inputGroup-sizing-default">Image</span>
                    <input  id="img" type="text" value=" " class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
                  </div>
                   </div>
                   
                  <p>
                    <button
                      type="submit"
                      onclick="addProduct()"
                      class="btn btn-success my-2"
                    >
                    Add Product
                    </button>
                  </p>
                </div>
              </div>
            </div>
          </section>
    
          <div style="background: linear-gradient(to bottom left ,#dbdd,#ff5,#ffd2)" class="album py-5 bg-light">
            <div class="container">
              <div
                id="productDiv"
                class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3"
              ></div>
            </div>
          </div>
        </main>
    
        <footer style="background: linear-gradient(to bottom left ,#dbdd,#ff5,#ffd2)" class="text-muted py-5">
          <div class="container">
            <p class="float-end mb-1">
              <a href="#"
              ></a>
            </p>
            <p class="mb-1">
              Yonatan Furman Assa &copy; made using
              <a href="https://getbootstrap.com/">Bootstrap</a>
            </p>
            <p class="mb-0"></p>
          </div>
        </footer>
    
        <script src="../assets/dist/js/bootstrap.bundle.min.js"></script>
        <script>
          const productDiv = document.getElementById("productDiv");
          const productName = document.getElementById("productName");
          const price = document.getElementById("price");
          const img = document.getElementById("img");
          const category = document.getElementById("category");
          let products = [];
    
          let addProduct=()=> {
            if(img.value.length==0||img.value==" "){img.value="https://picsum.photos/id/490/286/180"}
           if( productName.value.length == 0 || price.value.length == 0){ alert("Some Of The Fields Are Not Valid"); return false};
                products.push({
                Category:category.value,
                Name: productName.value,
                Price: price.value,
                Img: img.value,
              });
              console.log(products);
           
              productDiv.innerHTML = " ";
              for (let i = 0; i < products.length; i++) {
                productDiv.innerHTML += `<div class="col">
              <div class="card shadow-sm">
                <img src="${products[i].Img}" height="186" width="286" class="card-img-top" alt="${products[i].Name}">
                <div class="card-body">
                  <h2 class="card-text">${products[i].Category}</h2>
                  <h4 class="card-text">${products[i].Name}</h4>
                  <div class="d-flex justify-content-between align-items-center">
                    <div class="btn-group">
                      <p><strong>Price:</strong> ${products[i].Price}</p><br/>
                    </div>
                    <small class="text-muted">9 mins ago</small>
                  </div>
                  <button class="btn btn-danger" onclick="removeItem(${i})">Remove</button>
                </div>
              </div>
            </div>`;
              
            productName.value=" ";
              price.value=" ";
              img.value=" ";
        }
            
              
            }
       
            
            let removeItem=(i)=>{
                console.log(i)
            products.splice(i,1)
            console.log(products)
            productDiv.innerHTML = " ";
              for (let i = 0; i < products.length; i++) {
                productDiv.innerHTML += `<div class="col">
              <div class="card shadow-sm">
                <img src="${products[i].Img}" height="186" width="286" class="card-img-top" alt="${products[i].Name}">
                <div class="card-body">
                  <h2 class="card-text">${products[i].Category}</h2>
                  <h4 class="card-text">${products[i].Name}</h4>
                  <div class="d-flex justify-content-between align-items-center">
                    <div class="btn-group">
                      <p><strong>Price:</strong> ${products[i].Price}</p><br/>
                    </div>
                    <small class="text-muted">9 mins ago</small>
                  </div>
                  <button class="btn btn-danger" onclick="removeItem(${i})">Remove</button>
                </div>
              </div>
            </div>`;
              }
             } 
        
        </script>
      </body>
    </html>
