# trial-task-manager
git clone https://github.com/your-repo/trial-task-manager.git 
create .env and setup MYSql Database
composer install 
php artisan key:generate 
import task.sql in mysql from path \trial-task-manager\public\sql_dump
php -S 127.0.0.1:8000 -t public
Login details
username: admin@admin.com
password: password

After login explore projects and tasks.
I added draggable functionality to the tasks entity. Once you go to the tasks tab, you will see a list of tasks including main actions button at top, "Add New", "Bulk Delete", "Order"
using Order tab you can setup the priority of the tasks.  