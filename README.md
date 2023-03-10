<p align="center">
    <a href="https://github.com/yiisoft" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/993323" height="100px">
    </a>
    <h1 align="center">My Yii2 Application</h1>
    <br>
</p>


DIRECTORY STRUCTURE
-------------------

      assets/             contains assets definition
      commands/           contains console commands (controllers)
      config/             contains application configurations
      controllers/        contains Web controller classes
      mail/               contains view files for e-mails
      models/             contains model classes
      runtime/            contains files generated during runtime
      tests/              contains various tests for the basic application
      vendor/             contains dependent 3rd-party packages
      views/              contains view files for the Web application
      web/                contains the entry script and Web resources



REQUIREMENTS
------------

The minimum requirement by this project template that your Web server supports PHP 7.4.


INSTALLATION
------------

This is a sample Yii2 application that demonstrates basic CRUD operations for

Installation

Clone the repository:
git clone https://github.com/webstar0103/YII2_CRUD.git

Install the dependencies using Composer:
composer install

Create a new MySQL database and update the db configuration in the config/db.php file:
return [
    'class' => 'yii\db\Connection',
    'dsn' => 'mysql:host=localhost;dbname=fruit_db;port=3306',
    'username' => 'root',
    'password' => '',
    'charset' => 'utf8',
];

Run the migrations to create the necessary tables:
./yii migrate/up --interactive=0

Run the migrations to remove the necessary tables:
./yii migrate/down --interactive=0

seed database db
.yii db/seed

start serve
php yii serve --port=8800

