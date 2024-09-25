# pemrograman-web
Nama : Zahra Azizah (231730027), INFORMATIKA 3A "Tugas 1"
## Here is the list that is needed
```
fontawesome.com
https://getbootstrap.com/docs/5.0/components/according/
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" 
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
```
## Head Syntax
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>company profile</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" 
    rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" 
    crossorigin="anonymous">
    <link rel="stylesheet"
    href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
    integrity="sha384-AYMEC3Yw5cVb3ZcuHt0A93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
    crossorigin="anonymous">
    <link rel="stylesheet" href="style.css"> 
    <script src="https://kit.fontawesome.com/860c0beb9f.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYMEC3Yw5cVb3ZcuHt0A93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
    crossorigin="anonymous">
  </head>
```
## Body -> Navbar Syntax
```
<body>
  <!--navigasi-->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow-lg fixed-top">
        <div class="container">
          <a class="navbar-brand" href="#">MY BLOG</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse text-right" id="navbarText">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" href="#layanan">Service</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#portofolio">Portofolio</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#tentang">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#staff">Staff</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#kontak">Contact</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
```
## Body -> Banner Syntax
```
<!--banner-->
      <div class="container-fluid banner">
        <div class="container text-center">
          <h4 class="display-6">Welcome to Our Website</h4>
          <h3 class="display-1" > Haii Everyone!!!</h3>
          <a href="#layanan">
            <button type="button" class="btn btn-danger btn-lg">Check Service</button>
          </a>
        </div>
      </div>
```
## Body -> Layanan Syntax
```
<!--layanan-->
      <div class="container-fluid layanan pt-5 pb-5">
        <div class="container text-center">
          <h2 class="display-3" id="layanan">Service</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, dolores.</p>
          <div class="row pt-4">
            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-code fa-5x"></i></span>
              
              <h3 class="mt-3">programming</h3>
              <p> Programming is the process of creating a set of instructions that a computer can follow to perform specific tasks. It involves writing code in various programming languages, which serve as a medium for human-computer communication. </p>
            </div>

            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-palette fa-5x"></i></span>
              
              <h3 class="mt-3">Design</h3>
              <p> is the process that involves designing the structure, algorithms, and interfaces of software systems. The main objective is to create solutions that can be effectively implemented and meet user needs.</p>
            </div>

            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-network-wired fa-5x"></i></span>
              
              <h3 class="mt-3">Networking</h3>
              <p>is defined as the connection of at least two computer systems, either by a cable or a wireless connection. The simplest network is a peer-to-peer network, where both participants have equal privileges and can share resources such as disk space, applications, or peripheral devices like printers.</p>
            </div>
          </div>
        </div>
      </div>
```
## Body -> Portofolio Syntax
```
<!--portofolio-->
      <div class="container-fluid pt-5 pb-5 bg-light">
        <div class="container text-center">
          <h2 class="display-3" id="portofolio">portofolio</h2>
          <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae, sunt aperiam fuga nisi sed tempora accusantium facilis reprehenderit pariatur officiis?
          </p>
          <div class="row pt-4 gx-4 gy-4">
            <div class="col-md-4">
              <div class="card">
                <img src="https://www.talenta.co/wp-content/uploads/2019/11/shutterstock_387456811.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://www.su.se/polopoly_fs/1.658849!/image/image.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://eventussecurity.com/wp-content/uploads/2024/01/Cyber-Law-img.webp" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://static.vecteezy.com/system/resources/previews/024/571/670/large_2x/side-view-of-young-female-programmer-working-on-computer-at-night-in-dark-office-a-female-programmer-coding-and-working-on-a-computer-in-her-office-ai-generated-free-photo.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://marketmillion.com/wp-content/uploads/2023/01/The-Future-Of-Technology-What-To-Expect-In-The-Next-Decade.png" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://cdn.wccftech.com/wp-content/uploads/2022/09/13th-Gen-Intel-Core-2.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
```
## Body -> Tentang 
```
<!--tentang-->
      <div class="container-fluid pt-5 pb-5">
        <div class="container">
          <h2 class="display-3 text-center" id="tentang">About</h2>
          <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, adipisci.</p>
          <div class="clearfix pt-5"><img src="https://static.vecteezy.com/system/resources/previews/015/324/234/non_2x/internet-law-concept-cyber-law-as-digital-legal-services-labor-law-lawyer-on-dark-blue-blurred-background-free-vector.jpg" class="col-md-6 float-md-end mb-3 crop-img" width="300" height="300"/>
          <p>Cyber law, also known as internet law or digital law, signifies the legal regulations and frameworks governing digital activities.It covers a large range of issues, including online communication, e-commerce, digital privacy, and the prevention and prosecution of cybercrimes. </p>
          <P>Cyber law plays a crucial role in shaping and overseeing the digital world.It provides a framework for protecting individuals and organizations from cyber threats, ensuring the privacy and security of digital transactions, and establishing guidelines for ethical and legal conduct in cyberspace. </P>
          <P>As the digital world evolves, the importance of cyber law becomes more pronounced, serving as a cornerstone for the responsible and lawful utilization of digital resources.</P>
        </div>
        </div>
      </div>
```
## Body -> Staff Syntax
```
<!--staff-->
      <div class="container-fluid pt-5 pb-5 bg-light">
        <div class="container text-center">
          <h2 class="display-3" id="staff">Staff</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, beatae earum odio veritatis tenetur porro voluptas ipsa ratione inventore alias.</p>
          <div class="row pt-4 gx-4">
            <div class="col-md-4 text-center staff">
              <img src="https://img.freepik.com/premium-photo/programmer-woman-coding-computer_662214-272768.jpg"
              class="rounded-circle mb-3"
              />
              <h4>Christine</h4>
              <p>Web Development</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>

            <div class="col-md-4 text-center staff">
              <img src="https://thumbs.dreamstime.com/b/beautiful-young-woman-paris-tuileries-garden-looking-eiffel-tower-55007435.jpg"
              class="rounded-circle mb-3"
              />
              <h4>Moane</h4>
              <p>Web Designer</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>

            <div class="col-md-4 text-center staff">
              <img src="https://img.freepik.com/premium-photo/female-programmer_777576-2930.jpg"
              class="rounded-circle mb-3"
              />
              <h4>Elizabeth</h4>
              <p>Network Engineer</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>
          </div>
        </div>
      </div>
```
## Body ->Client Syntax
```
<!-- client -->
       <div class="container-fluid client pt-5 pb-5">
        <div class="container text-center">
          <div class="row pt-4 gx-4 gy-4">
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/022/101/068/original/microsoft-logo-transparent-free-png.png"/>
            </div>
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/002/445/918/original/social-media-facebook-logo-icon-free-vector.jpg"/>
            </div>
            <div class="col">
              <img src="https://www.1min30.com/wp-content/uploads/2018/04/Couleur-logo-IBM.jpg"/>
            </div>
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/023/986/900/original/linkedin-logo-linkedin-logo-transparent-linkedin-icon-transparent-free-free-png.png"/>
            </div>
            <div class="col">
              <img src="https://freelogopng.com/images/all_img/1657955447google-logo-black-and-white.png"/>
            </div>
            </div>
          </div>
        </div>
       </div>
```
## Body -> Kontak Syntax
```
<!-- kontak -->
        <div class="container-fluid pt-5 pb-5 kontak">
          <div class="container">
            <h2 class="display-3 text-center" id="kontak">Contact Us</h2>
            <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam, at.</p>
            <div class="row pb-3">
              <div class="col-md-6">
                <input class="form-control form-control-lg mb-3" type="text" placeholder="Name"/>
                <input class="form-control form-control-lg mb-3" type="text" placeholder="Email"/>
                <input class="form-control form-control-lg mb-3" type="text" placeholder="No Phone"/>
              </div>
              <div class="col-md-6">
                <textarea class="form-control form-control-lg" rows="5"></textarea>
              </div>
            </div>
            <div class="col-md-3 mx-auto text-center">
              <button type="button" class="btn btn-danger btn-lg">Submit</button>
            </div>
          </div>
        </div>
        <div class="container text-center pt-5 pb-5">
          All Rights Reserved &copy; 2024
        </div>

</body>
</html>
```
## Full Version Syntax
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>company profile</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" 
    rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" 
    crossorigin="anonymous">
    <link rel="stylesheet"
    href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
    integrity="sha384-AYMEC3Yw5cVb3ZcuHt0A93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
    crossorigin="anonymous">
    <link rel="stylesheet" href="style.css"> 
    <script src="https://kit.fontawesome.com/860c0beb9f.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYMEC3Yw5cVb3ZcuHt0A93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
    crossorigin="anonymous">
  </head>
<body>
  <!--navigasi-->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow-lg fixed-top">
        <div class="container">
          <a class="navbar-brand" href="#">MY BLOG</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse text-right" id="navbarText">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" href="#layanan">Service</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#portofolio">Portofolio</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#tentang">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#staff">Staff</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#kontak">Contact</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <!--banner-->
      <div class="container-fluid banner">
        <div class="container text-center">
          <h4 class="display-6">Welcome to Our Website</h4>
          <h3 class="display-1" > Haii Everyone!!!</h3>
          <a href="#layanan">
            <button type="button" class="btn btn-danger btn-lg">Check Service</button>
          </a>
        </div>
      </div>
      <!--layanan-->
      <div class="container-fluid layanan pt-5 pb-5">
        <div class="container text-center">
          <h2 class="display-3" id="layanan">Service</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, dolores.</p>
          <div class="row pt-4">
            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-code fa-5x"></i></span>
              
              <h3 class="mt-3">programming</h3>
              <p> Programming is the process of creating a set of instructions that a computer can follow to perform specific tasks. It involves writing code in various programming languages, which serve as a medium for human-computer communication. </p>
            </div>

            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-palette fa-5x"></i></span>
              
              <h3 class="mt-3">Design</h3>
              <p> is the process that involves designing the structure, algorithms, and interfaces of software systems. The main objective is to create solutions that can be effectively implemented and meet user needs.</p>
            </div>

            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-network-wired fa-5x"></i></span>
              
              <h3 class="mt-3">Networking</h3>
              <p>is defined as the connection of at least two computer systems, either by a cable or a wireless connection. The simplest network is a peer-to-peer network, where both participants have equal privileges and can share resources such as disk space, applications, or peripheral devices like printers.</p>
            </div>
          </div>
        </div>
      </div>
      <!--portofolio-->
      <div class="container-fluid pt-5 pb-5 bg-light">
        <div class="container text-center">
          <h2 class="display-3" id="portofolio">portofolio</h2>
          <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae, sunt aperiam fuga nisi sed tempora accusantium facilis reprehenderit pariatur officiis?
          </p>
          <div class="row pt-4 gx-4 gy-4">
            <div class="col-md-4">
              <div class="card">
                <img src="https://www.talenta.co/wp-content/uploads/2019/11/shutterstock_387456811.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://www.su.se/polopoly_fs/1.658849!/image/image.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://eventussecurity.com/wp-content/uploads/2024/01/Cyber-Law-img.webp" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://static.vecteezy.com/system/resources/previews/024/571/670/large_2x/side-view-of-young-female-programmer-working-on-computer-at-night-in-dark-office-a-female-programmer-coding-and-working-on-a-computer-in-her-office-ai-generated-free-photo.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://marketmillion.com/wp-content/uploads/2023/01/The-Future-Of-Technology-What-To-Expect-In-The-Next-Decade.png" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://cdn.wccftech.com/wp-content/uploads/2022/09/13th-Gen-Intel-Core-2.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!--tentang-->
      <div class="container-fluid pt-5 pb-5">
        <div class="container">
          <h2 class="display-3 text-center" id="tentang">About</h2>
          <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, adipisci.</p>
          <div class="clearfix pt-5"><img src="https://static.vecteezy.com/system/resources/previews/015/324/234/non_2x/internet-law-concept-cyber-law-as-digital-legal-services-labor-law-lawyer-on-dark-blue-blurred-background-free-vector.jpg" class="col-md-6 float-md-end mb-3 crop-img" width="300" height="300"/>
          <p>Cyber law, also known as internet law or digital law, signifies the legal regulations and frameworks governing digital activities.It covers a large range of issues, including online communication, e-commerce, digital privacy, and the prevention and prosecution of cybercrimes. </p>
          <P>Cyber law plays a crucial role in shaping and overseeing the digital world.It provides a framework for protecting individuals and organizations from cyber threats, ensuring the privacy and security of digital transactions, and establishing guidelines for ethical and legal conduct in cyberspace. </P>
          <P>As the digital world evolves, the importance of cyber law becomes more pronounced, serving as a cornerstone for the responsible and lawful utilization of digital resources.</P>
        </div>
        </div>
      </div>
      <!--staff-->
      <div class="container-fluid pt-5 pb-5 bg-light">
        <div class="container text-center">
          <h2 class="display-3" id="staff">Staff</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, beatae earum odio veritatis tenetur porro voluptas ipsa ratione inventore alias.</p>
          <div class="row pt-4 gx-4">
            <div class="col-md-4 text-center staff">
              <img src="https://img.freepik.com/premium-photo/programmer-woman-coding-computer_662214-272768.jpg"
              class="rounded-circle mb-3"
              />
              <h4>Christine</h4>
              <p>Web Development</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>

            <div class="col-md-4 text-center staff">
              <img src="https://thumbs.dreamstime.com/b/beautiful-young-woman-paris-tuileries-garden-looking-eiffel-tower-55007435.jpg"
              class="rounded-circle mb-3"
              />
              <h4>Moane</h4>
              <p>Web Designer</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>

            <div class="col-md-4 text-center staff">
              <img src="https://img.freepik.com/premium-photo/female-programmer_777576-2930.jpg"
              class="rounded-circle mb-3"
              />
              <h4>Elizabeth</h4>
              <p>Network Engineer</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>
          </div>
        </div>
      </div>
      <!-- client -->
       <div class="container-fluid client pt-5 pb-5">
        <div class="container text-center">
          <div class="row pt-4 gx-4 gy-4">
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/022/101/068/original/microsoft-logo-transparent-free-png.png"/>
            </div>
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/002/445/918/original/social-media-facebook-logo-icon-free-vector.jpg"/>
            </div>
            <div class="col">
              <img src="https://www.1min30.com/wp-content/uploads/2018/04/Couleur-logo-IBM.jpg"/>
            </div>
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/023/986/900/original/linkedin-logo-linkedin-logo-transparent-linkedin-icon-transparent-free-free-png.png"/>
            </div>
            <div class="col">
              <img src="https://freelogopng.com/images/all_img/1657955447google-logo-black-and-white.png"/>
            </div>
            </div>
          </div>
        </div>
       </div>
       <!-- kontak -->
        <div class="container-fluid pt-5 pb-5 kontak">
          <div class="container">
            <h2 class="display-3 text-center" id="kontak">Contact Us</h2>
            <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam, at.</p>
            <div class="row pb-3">
              <div class="col-md-6">
                <input class="form-control form-control-lg mb-3" type="text" placeholder="Name"/>
                <input class="form-control form-control-lg mb-3" type="text" placeholder="Email"/>
                <input class="form-control form-control-lg mb-3" type="text" placeholder="No Phone"/>
              </div>
              <div class="col-md-6">
                <textarea class="form-control form-control-lg" rows="5"></textarea>
              </div>
            </div>
            <div class="col-md-3 mx-auto text-center">
              <button type="button" class="btn btn-danger btn-lg">Submit</button>
            </div>
          </div>
        </div>
        <div class="container text-center pt-5 pb-5">
          All Rights Reserved &copy; 2024
        </div>

</body>
</html>

