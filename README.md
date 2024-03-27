# Blogger

Welcome to the Django Blog App! This is a simple blog application built using Django, allowing you to create, edit, and publish blog posts easily.

## Features

- **User Authentication**: Users can register, log in, and log out.
- **Create, Read, Update, Delete (CRUD) Operations**: Users can create new blog posts, view existing posts, edit their own posts, and delete posts they own.
- **Rich Text Editing**: Use a rich text editor to format your blog posts with ease.
- **Responsive Design**: The blog app is built with a responsive design, making it accessible and user-friendly across different devices and screen sizes.

## Setup

1. **Clone the Repository**: 
    ```
    git clone https://github.com/hamdani2020/Blogger.git
    ```

2. **Navigate to the Project Directory**: 
    ```
    cd Blogger
    ```

3. **Create a Virtual Environment** (optional but recommended): 
    ```
    python -m venv env
    ```

4. **Activate the Virtual Environment**: 
    - On Windows:
        ```
        env\Scripts\activate
        ```
    - On macOS and Linux:
        ```
        source env/bin/activate
        ```

5. **Install Dependencies**: 
    ```
    pip install -r requirements.txt
    ```

6. **Run Migrations**: 
    ```
    python manage.py migrate
    ```

7. **Create a Superuser**: 
    ```
    python manage.py createsuperuser
    ```

8. **Run the Development Server**: 
    ```
    python manage.py runserver
    ```

9. **Access the Admin Interface**: 
    - Go to `http://127.0.0.1:8000/admin/` in your web browser.
    - Log in using the superuser credentials created earlier.

## Usage

- **Create a Blog Post**: Log in to the admin interface, navigate to the "Posts" section, and click "Add Post".
- **Edit a Blog Post**: Click on an existing post in the admin interface to edit it.
- **View Blog Posts**: Visit the homepage (`http://127.0.0.1:8000/`) to view all published blog posts.
- **Manage Users**: Use the Django admin interface to manage users, groups, and permissions.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
