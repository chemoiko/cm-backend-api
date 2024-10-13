#Marketing Manager Backend
 - Link to website   <a>https://car-showcase-next-js-iota.vercel.app/</a>

![banner](https://imgur.com/2d0AFmP,png)
<div align="center">
  <br />

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Installation](#quick-start)
5. 


## <a name="introduction">🤖 Introduction</a>
This is a backend application for managing marketing campaigns using Django. The application provides APIs for creating, retrieving, updating, and deleting campaigns. Each campaign includes a title, a description, and an image. The API is documented using Swagger for easy access and understanding.

## <a name="tech-stack">⚙️ Tech Stack</a>
- Django
- Django REST Framework

## Installation
**Running the Project**
-Clone the repo
```
git clone https://github.com/yourusername/marketing-manager-backend.git
cd marketing-manager-backend

```

- Create a virtual environment:
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

```

- Install the required packages:
```
pip install -r requirements.txt

```

- Apply migrations
```
python manage.py migrate


```

- Run the development server:
```
python manage.py runserver

```

##API Endpoints
-POST	/api/campaigns/	Create a new campaign
-GET	/api/campaigns/	Retrieve all campaigns
-GET	/api/campaigns/{id}/	Retrieve a specific campaign
-PUT	/api/campaigns/{id}/	Update a specific campaign
-DELETE	/api/campaigns/{id}/	Delete a specific campaign

Open [http://localhost:8000](http://localhost:8000) in your browser to view the project.

  
