<h3>Laravel Sanctum CRUD API</h3>
<p>This project configures laravel sanctum with a CRUD api. When a user is logged in an access token will be created so the user can use the access token to access STORE, UPDATE and DESTROY routes. if an Access token is no present the store, update and delete operations are not available</p>
<h4>How to configure the project</h4>
<p>First download the project to your dev server and run migrations using command "php artisan migrate" then you need to create a user, in order to create a user you have to make a post request to your http://projectpath/api/register with fields of name, email, password and password_confirmation and you have to pass headers of accept => application/json if you are using an API tester. </p>

<h4>Routes you can try</h4>
<p>
    1. http://youprojectpath/api/register
        pass ->
                name, email, password and password_confirmation </br>
    2. http://youprojectpath/api/login
        pass->
            email and password fields</br>
    3. http://youprojectpath/api/logout</br>
    4. http://youprojectpath/api/products    ... list all products</br>
    5. http://youprojectpath/api/products/2    ... show a specific product</br>
    6. http://youprojectpath/api/products/   ... post request to </br>
        pass->
                name, slug, description, price</br>
    7. http://youprojectpath/api/products/1   ... put request to 
        pass any of the following -> 
                name, slug, description, price</br>
    
    8. http://youprojectpath/api/products/1   ... delete request to 
</p>
