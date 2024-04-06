# Hanashi-Blog-Site
![Preview Image](Preview.jpg)

Welcome to my blog website! This is a personal project that allows users to register, create, read, update, and delete (CRUD) blog posts with images. It also features a search functionality to easily find blog posts.

## Features

- User registration and authentication
- CRUD operations for blog posts
- Image uploads for blog posts
- Search functionality for finding specific blog posts
- Responsive design for mobile and desktop devices

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.6 or newer
- pip (Python package installer)

### Installation

1. Clone the repository to your local machine:

bash```
git clone https://github.com/SapporoAlex/Hanashi-Blog-Site.git
```

2. Navigate to the project directory:

bash```
cd hanashi-blog-site
```


3. Install the required dependencies:

bash```
pip install -r requirements.txt
```

4. Apply the migrations:
bash```
python manage.py migrate
```

5. Create a superuser:
bash```
python manage.py createsuperuser
```

6. Run the development server:
bash```
python manage.py runserver
```

7. Open your web browser and go to `http://127.0.0.1:8000/` to view the site.

## Usage

After setting up the project, you can:

- Register a new user account
- Log in with your user credentials
- Create, read, update, and delete blog posts
- Upload images with your blog posts
- Use the search bar to find specific blog posts

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Author
Alex McKinley
