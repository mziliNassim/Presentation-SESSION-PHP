# **SESSION**

## Check Methode POST ** GET

    $_SERVER['REQUEST_METHOD'] == 'POST'

## Start || Complet Sessions

    session_start();

## Session Variables

    * $_SESSION['nom_sess_var1'] = nom_sess1;
    * $_SESSION['nom_sess_var2'] = nom_sess2;

## Rediction

    * header('location:page.php');
    * exit();

## Check Exist Session

    * isset($_SESSION['nom_sess_var']);

## Fin D'une Session

    // vider les sessions variable
    * session_unset();
    
    // suprimer * destroy session
    * session_destroy();
