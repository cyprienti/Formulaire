# Formulaire

Code HTML
<!DOCTYPE html>

<html>

<head>

    <meta charset="UTF-8">

    <title>INSCRIPTION</title>

    <link rel="stylesheet" href="bootstrap.css">

</head>

<body class="bg-gradient-primary">

  <div class="container">

    <div class="card o-hidden border-0 shadow-lg my-5">

      <div class="card-body p-0">

        <div class="row">

          <div class="col-lg-5 d-none d-lg-block bg-register-image"></div>

            <div class="col-lg-7">

              <div class="p-5">

                <div class="text-center">

                <h1 class="h4 text-gray-900 mb-4">Créer un compte!</h1>

                </div>

                <form class="user" id="form">

                  <div class="form-group row">

                    <div class="col-sm-6 mb-3 mb-sm-0">

                    <input type="text" class="form-control form-control-user" placeholder="Nom" id="username" required>

                    </div>

                  <div class="col-sm-6">

                    <input type="text" class="form-control form-control-user" placeholder="Prénom" required>

                  </div>

                  </div>

                  <div class="form-group">

                    <input type="email" class="form-control form-control-user" placeholder="Adresse email" id="email" required>

                  </div>

                  <div class="form-group row">

                    <div class="col-sm-6 mb-3 mb-sm-0">

                      <input type="password" class="form-control form-control-user" placeholder="Mot de passe" id="password" required>

                    </div>

                  <div class="col-sm-6">

                    <input type="password" class="form-control form-control-user" placeholder="Répéter mot de passe" id="password2" required>

                  </div>

                  </div>

                    <a href="" class="btn btn-primary btn-user btn-block"><button class="btn btn-primary btn-user btn-block">S'inscrire</button></a>

                </form>

              <hr>

              <div class="text-center">

                <a href="">Mot de passe oublié?</a>

              </div>

              <div class="text-center">

                <a href="">Déjà un compte? Se connecter!</a>

              </div>

            </div>

          </div>

        </div>

      </div>

    </div>

 

  </div>

  </body>

  </html>

Code CSS
BOOTSTRAP V4
