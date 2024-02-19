```markdown
# Hello World Django App

## Getting Started

### Prerequisites

You should have Python and Django installed on your machine. If not, you can install them using the following commands:
```
```bash
pip install django
```

### Installation

1. Clone the repository:

```bash
git clone https://github.com/jayasainathyerragudi/software-architecture-django-helloworld/HelloWorldProject.git
cd HelloWorldProject
```
### Run the Development Server

```bash
python manage.py runserver
```
or if you are uisng python3

```bash
python3 manage.py runserver
```

Visit [http://localhost:8000/hello/](http://localhost:8000/hello/) in your web browser, and you should see the JSON response:

```json
{"Message": "Hello World!"}
```
