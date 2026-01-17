📝 MyBlog – Django Blog Application

Deployment: https://siddhis.pythonanywhere.com/

MyBlog is a modern, dynamic blogging platform built using Django. It allows users to create, manage, and read blog posts with features such as featured articles, recent posts, author information, and an about section.
This project demonstrates practical Django concepts and is suitable for portfolio, resume, and interview showcase.

🚀 Features

✍️ Blog Post Management

✅Create, update, and delete blog posts via Django Admin
✅Each post includes title, slug, author, image, and short description

⭐ Featured Posts

✅Highlighted blog posts displayed prominently on the homepage
✅Eye-catching banner with featured image and overlay text

🆕 Recent Articles

✅Displays the latest posts dynamically
✅Shows author name and time since publication

👤 Author Support

✅Posts linked to specific authors
✅Author name visible on each post

ℹ️ About Section

✅Dynamic About content rendered from the database

🔗 Social Media Links

✅Sidebar includes social platform links managed from backend

🎨 Responsive UI

✅Clean layout using Bootstrap
✅Sidebar + content layout for better readability

🛠️ Tech Stack

✅Backend: Django (Python)
✅Frontend: HTML, CSS, Bootstrap
✅Database: SQLite
✅Template Engine: Django Templates
✅Authentication: Django Built-in Auth

🖥️ Homepage Layout

The homepage includes:

A featured post banner
A featured posts list
A recent articles section
A sidebar with About info and social links

All content is rendered dynamically using Django template tags such as:

for loops
truncatewords
timesince

⚙️ Installation & Setup

1️⃣ Clone the repository
git clone https://github.com/Sutarsiddhi/MyBlog.git
cd django_blog_app

2️⃣ Create a virtual environment
python -m venv env
source env/bin/activate   # Windows: env\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run migrations
python manage.py migrate

5️⃣ Create superuser
python manage.py createsuperuser
6️⃣ Start the server
python manage.py runserver

Visit:
http://127.0.0.1:8000/

Screenshots:
<img width="1913" height="1014" alt="home" src="https://github.com/user-attachments/assets/c6d22ae9-aa74-4898-ad9c-998adc3ce3b1" />

<img width="1907" height="1018" alt="singleblog" src="https://github.com/user-attachments/assets/7bb3f951-2aea-4817-94fc-9fe691e72333" />

<img width="1912" height="1018" alt="dashboard" src="https://github.com/user-attachments/assets/cf21084b-4831-4858-966e-e96778847a22" />

