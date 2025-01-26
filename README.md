# Practice Project with Laravel 9.x

This project is a basic application built with Laravel 9.x. It was created for practice and learning purposes and includes the following main features:

## Features

- **Post Management (CRUD)**: 
  - List posts.
  - Create new posts.
  - View post details.
  - Pagination to navigate between posts.
- **Protected Dashboard**:
  - Access only for authenticated users.
- **Test Data Generation**:
  - Seeder to create posts with data generated using the Faker library.

## Prerequisites

Before starting, ensure you have the following components installed:

- PHP >= 8.0
- Composer
- MySQL or any compatible database

## Installation

Follow these steps to set up and run the project locally:

1. Clone the repository:

   ```bash
   git clone git@github.com:guduchango/platzi-laravel-basic.git
   cd platzi-laravel-basic
   ```

2. Install PHP dependencies:

   ```bash
   composer install
   ```

3. Configure the `.env` file:

   - Copy the example file:
     ```bash
     cp .env.example .env
     ```
   - Set your database credentials in the `.env` file.

4. Generate the application key:

   ```bash
   php artisan key:generate
   ```

5. Run migrations and seeders:

   ```bash
   php artisan migrate --seed
   ```

6. Start the development server:

   ```bash
   php artisan serve
   ```

## Usage

- Visit `http://localhost:8000` to access the application.
- Use the dashboard by logging in with the credentials created or generated via the seeder.

## Project Structure

- `routes/web.php`: Defines the main routes of the application.
- `app/Http/Controllers`: Contains the controllers for the project functionalities.
- `resources/views`: Blade files for the application views.
- `database/seeders`: Seeders for generating test data.

## Images

_Here you can add screenshots or GIFs showcasing how the application works._

![image1](https://images.edgardoponce.com/platzi-laravel-basic/image6.png)
![image2](https://images.edgardoponce.com/platzi-laravel-basic/image5.png)
![image3](https://images.edgardoponce.com/platzi-laravel-basic/image4.png)
![image4](https://images.edgardoponce.com/platzi-laravel-basic/image3.png)
![image5](https://images.edgardoponce.com/platzi-laravel-basic/image2.png)
![image6](https://images.edgardoponce.com/platzi-laravel-basic/image1.png)

## Technologies Used

- Laravel 9.x
- PHP 8.x
- MySQL
- Faker (for test data)
- Blade (for views)

## Next Steps

- Add role-based authentication.
- Implement unit tests.
- Enhance the design with Tailwind CSS.

## Contributions

If you want to contribute to this project, feel free to fork it and submit a pull request.

## License

This project is licensed under the MIT License. You can find more details in the `LICENSE` file.

---

Thank you for exploring this project! If you have any questions or suggestions, feel free to contact me.
