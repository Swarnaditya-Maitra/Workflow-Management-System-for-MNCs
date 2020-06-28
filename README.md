## Workflow Management System for MNCs
This project aims to increase the ease of managing workflow of firms, by having all the details of every project activity in the organization, consolidated at one place. The software empowers all the stakeholders of an organization, comprising project managers, employees, HR representatives, business owners, clients, coders and non-coders with a platform to easily build, deliver, monitor and maintain projects undertaken by the firm. The software features login and authentication-based access, with role-based access control. Features like various form elements, multiple project support, user notifications during various events, and DevOps integration have also been incorporated. A project manager can create the project workspace and add the project members, who then collaborate on that project. Every account has its own dashboard to monitor different aspects, and option to create projects. Company executives can simply login to the software, browse through the projects, see the various project status indicators, the people involved, and also add notes for people to see. This application not only helps the team to stay in sync but also allows the clients to see the progress, without having to wait for months before deployment. We also plan to incorporate drag and drop workflow management in the future.

## Important Documents
Important documents directory contains the project report, a YouTube video link for the project working demonstration, and a user manual - installation and product details. Please refer the manual for thorough details of the process.

Some basic points are mentioned below:

## Prerequisites
1. XAMPP (PHP development environment)
2. Composer (Dependency manager for PHP)
3. Laravel (PHP development framework)

## Setting up a new project
To create new *Laravel* project, run `composer create-project laravel/laravel ProjectName`.

## Setup of this repository
1. Clone the repository.
2. Start `MySQL` server from XAMPP.
3. In MySQL console, run `create database db_name` to create new database.
4. Run `php artisan migrate` to setup the database.
5. Run `php artisan migrate:status` to check status of each migration file.
