#Marketing Manager Backend
 - Link to website   <a>https://car-showcase-next-js-iota.vercel.app/</a>

![banner](https://imgur.com/2d0AFmP,png)
<div align="center">
  <br />

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets](#snippets)
6. 🔗 [Links](#links)
7. 🚀 [More](#more)

## <a name="introduction">🤖 Introduction</a>
This is a backend application for managing marketing campaigns using Django. The application provides APIs for creating, retrieving, updating, and deleting campaigns. Each campaign includes a title, a description, and an image. The API is documented using Swagger for easy access and understanding.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Django
- Django REST Framework

  **Installation**
Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on the corresponding websites from [Rapid API](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbmI1TlE1NHFGZ1JLdHU3dnAxSTU5a2R5UUM4QXxBQ3Jtc0tsUDY0aW8xMFhUZVdxMUNzSUlKUExRTG5UaDZoR3hWVFprN2tJV0k2dnk4MXo2NVFMVkk0NWhGS19Nd0g5cGRfN2JjcTdaSlJJRHJKYzlfT3lSS1M4TDVNVTV5Wl91c1lIR2VPZUYzbHJ2Tll2QkJ0aw&q=https%3A%2F%2Frapidapi.com%2Fapininjas%2Fapi%2Fcars-by-api-ninjas%3Futm_source%3Dyoutube.com%2FJavaScriptMastery%26utm_medium%3Dreferral%26utm_campaign%3DDevRel&v=pUNSHPyVryU) to [Imagin Cars](https://www.imagin.studio/solutions/api)

**Running the Project**

```Clone the repo
git clone https://github.com/yourusername/marketing-manager-backend.git
cd marketing-manager-backend

```


```Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

```


```Install the required packages:
pip install -r requirements.txt

```


```Apply migrations:
python manage.py migrate


```


```Run the development server:
python manage.py runserver


```

##API Endpoints

-POST	/api/campaigns/	Create a new campaign
-GET	/api/campaigns/	Retrieve all campaigns
-GET	/api/campaigns/{id}/	Retrieve a specific campaign
-PUT	/api/campaigns/{id}/	Update a specific campaign
-DELETE	/api/campaigns/{id}/	Delete a specific campaign

Open [http://localhost:8000](http://localhost:8000) in your browser to view the project.

  
