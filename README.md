# Project Responsive Web Design using Bootstrap
## Date:25/12/2024

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<html>
    <head>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
        <style>
     .vijay
     {
        font-size: 15px;
     }
     .vijay2
     {
        font-size: 25px;
     }
        </style>
    </head>
    <body>
        <nav class="navbar navbar-default"  >
            <div class="container-fluid"  >
                        <ul class="nav navbar-nav"  >
                            <li  class= "bg-success" ><a href="#"> <button type="button" class="btn btn-danger btn-sm">DRIBBBLE</button> </a></li>
                            <li><a href="#">EXPLORE</a></li>
                            <li><a href="#">HIRE A DESIGNER</a></li>
                            <li><a href="#">BLOG</a></li>
                            <li><a href="#">CONTACT US</a></li>
                            <li><a href="#">...</a></li>
                        </ul>
                  
                        <ul class="nav navbar-nav navbar-right">                 
                            <li><a href="#"><button type="button" class="btn btn-primary btn-sm">Login</button></a></li>
                            <li><a href="#"><button type="button" class="btn btn-danger btn-sm">Sign Up</button></a></li>
                        </ul>
                 </div>   </nav>
                                    
                 <h1 class="text-center">DRIBBBLE</h1>
                 <div class="vijay">
                    <p class="text-center"><I> Inspirational designs, illustrations, and graphic elements from the world’s best designers.</I> </p>
                    <p class="text-center"> <I>Want more inspiration? Browse our <a href="#">search results...</I> </a></p>
                 </div>
                 <nav class="navbar navbar-default"  >
                    <div class="container-fluid"  >
                                <ul class="nav navbar-nav"  >
                                    <li  class= "bg-light" ><a href="#"> <button type="button" class="btn btn-info btn-sm"><b>popular...</b></button></a></li>
                                    <li  class= "bg-light" ><a href="#"><button type="button" class="btn btn-light btn-sm">Animation</button></a></li>
                                    <li  class= "bg-light" ><a href="#"><button type="button" class="btn btn-light btn-sm">Product Design</button></a></li>
                                    <li  class= "bg-light" ><a href="#"><button type="button" class="btn btn-light btn-sm">Web Design</button></a></li>
                                </ul>
                          
                                <ul class="nav navbar-nav navbar-right">
                                    <li><a href="#"><button type="button" class="btn btn-primary btn-sm">SEARCH</button></a></li>
                                    <li class="bg-light"><a href="#"> <button type="button" class="btn btn-light btn-sm"><input type="text" placeholder="search..."></button></a></li>
                                </ul>
                                
                         </div>   </nav>
                         <div class="row">
                            <div class="col-md-4">
                              <div class="thumbnail">
                               
                                  <img src="1.jpeg" alt="Lights" style="width:100%">
                                  <div class="caption">
                                    <p  class="vijay2" ><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Fahema Yesmin</b></p>
                                  </div>
                            
                              </div>
                            </div>
                            <div class="col-md-4">
                              <div class="thumbnail">
                               
                                  <img src="2.jpeg" alt="Nature" style="width:100%">
                                  <div class="caption">
                                    <p class="vijay2"><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Plainthing Studio</b></p>
                                  </div>
                               
                              </div>
                            </div>
                            <div class="col-md-4">
                              <div class="thumbnail">
                                
                                  <img src="3.jpeg" alt="Fjords" style="width:100%">
                                  <div class="caption">
                                    <p  class="vijay2"><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Nixtio</b></p>
                                  </div>
                             
                              </div>
                            </div>
                          </div>     
                          <div class="row">
                            <div class="col-md-4">
                              <div class="thumbnail">
                               
                                  <img src="4.jpeg" alt="Lights" style="width:100%">
                                  <div class="caption">
                                    <p class="vijay2"><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Flatonica </b></p>
                                  </div>
                          
                              </div>
                            </div>
                            <div class="col-md-4">
                              <div class="thumbnail">
                               
                                  <img src="5.jpeg" alt="Nature" style="width:100%">
                                  <div class="caption">
                                    <p class="vijay2"><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Purrweb UI/UX Agency </b></p>
                                  </div>
                          
                              </div>
                            </div>
                            <div class="col-md-4">
                              <div class="thumbnail">
                               
                                  <img src="6.jpeg" alt="Fjords" style="width:100%">
                                  <div class="caption">
                                    <p class="vijay2"><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Extej UI UX Design Agency </b></p>
                                  </div>
                                
                              </div>
                            </div>
                          </div>
                         <P class="text-center">DESIGNED AND DEVELOPED BY V.ENBANATHAN</P>
    </body> 
</html>
```

## OUTPUT:
![alt text](<Screenshot (154).png>)
![alt text](<Screenshot (155).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
