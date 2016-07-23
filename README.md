# L5-eloquent-encryptable

Adds possibility to encrypt fields in Laravel Eloquent models.


# Setup
Add the package to the require section of your composer.json and run `composer update`

    "travis_enclave/encryptdata": "^dev"

# Prepare models
In your model add following lines:
    
    use \Travis_enclave\Eloquent\Encryptable;
    protected $encrypted=['field',['filed']];

# Usage
