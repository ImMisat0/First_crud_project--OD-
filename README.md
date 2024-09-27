# OperationDeadbolt
This project is a Basic CRUD function Task list, built using Laravel framework along with TailwindCSS & AlpineJS.

# DOWNLOADING GUIDE
## Installation 
1. Cloning the repo:
```bash
git clone https://github.com/ImMisat0/First_crud_project-OD.git
cd First_crud_project-OD
```
2. Installing dependacies 
```
composer install
```

3. Copy .env.example to .env and configure environment variables
```
cp .env.example .env
```

4. Set up the database
```
php artisan migrate
```

## Usage
Right after you've done clone the repo, navigate to the root directory and type this into the terminal:
```
php artisan serve
``` 
This will start the server, after that just ctrl+click on the link.

## Features
1. View Task List:
Users can easily view a list of tasks, providing a clear overview of both completed and pending tasks.

2. Add New Tasks:
Users can create and add new tasks to the list. Each task can include important details such as a description or due date (if applicable).

3. Delete Tasks:
Users can remove tasks from the list when they are no longer needed.

4. Mark Task as Completed/Not Completed:
Users can toggle tasks between completed and not completed states, allowing for better tracking of task progress.

## Troubleshooting
- Problem: Cannot connect to the database.
+ Solution | Check if the database credentials in the `.env` file are correct.


## Contribution
Any contributions to the project are welcome and very much appriciate. 
To contribute: 
1. Copy the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Creating a pull request.

## Credits
- Tailwind.Css(https://tailwindcss.com) - for styling.
- Alpine.JS (https://alpinejs.dev) 

