Project Checklist [Production]
---
> Fully Complete Project 
- [ ] **README**
  - [ ] Initiate README.md [mvp]
  - [ ] One-liner explaining the purpose of the repo
  - [ ] Necessary background context & links
  - [ ] Potentially infamiliar terms link to informative sources
  - [ ] Clear, *runnable* example of usage
  - [ ] Installation instructions
  - [ ] Example API documentation
  - [ ] Performs [cognitive funneling](https://github.com/noffle/art-of-readme#cognitive-funneling)
  - [ ] Caveats and limitations mentioned up-front
  - [ ] Doesn't rely on images to relay critical information
  - [ ] License
  - [ ] Badges
- [ ] **API Documentation**
  - [ ] Choose Tool(s)
  - [ ] *Additional Step* 
  - [ ] *Additional Step*
  - [ ] *Additional Step*
- [ ] **[Github Pages](https://pages.github.com/)**
  - [ ] *Additional Step* 
  - [ ] *Additional Step*
  - [ ] *Additional Step*
- [ ] **UX/UI**
  - [ ] Decide Web Application Features
  - [ ] Make Sketch of Web Application
  - [ ] Plan Work Process(How Customer Send and Receives Data)
  - [ ] Wireframe Project
- [ ] **Backend**
  - [ ] Design Backend Architecture
    - [ ] Choose Database [ SQLite | Postgres | Etc. ]
    - [ ] Architech Database
    - [ ] Map out Server Request
  - [ ] Initiate with [pipenv](https://pypi.org/project/pipenv/) or [venv](https://docs.python.org/3/library/venv.html) or [poetry](https://python-poetry.org/)
      - Make sure to use *pip3* instead of pip to install virtual enviroment or any modules
  - [ ] Initiate Backend w/ [Django](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)
  - [ ] Migrate Database
  - [ ] Establish and configure asynchronous communication from day one
  - [ ] Create an abstract base model to be inherited by every other model in your database
  - [ ] Implement authentication and authorisation microservices
  - [ ] Set up error logging
  - [ ] Set up a notification microservice
  - [ ] 
- [ ] **Frontend** 
  - [ ] Initiate Frontend w/ [React](https://reactjs.org/docs/create-a-new-react-app.html)
  - [ ] Homepage/Landingpage
    - [ ] Design
    - [ ] Code
    - [ ] Connect to Backend
    - [ ] Connect to Other Pages
  - [ ] Page 2
    - [ ] Design
    - [ ] Code
    - [ ] Connect to Backend
    - [ ] Connect to Other Pages
  - [ ] Page 3
    - [ ] Design
    - [ ] Code
    - [ ] Connect to Backend
    - [ ] Connect to Other Pages
- [ ] **Testing**
  - [ ] Choose Tool(s)
  - [ ] Test Endpoints 
  - [ ] Introduce throttling in your APIs and rate limiting on your application servers 
  - [ ] *Additional Step*
  - [ ] *Additional Step*
- [ ] **Security**
  - [ ] [Backend Best Practices](https://github.com/futurice/backend-best-practices)
  - [ ] *Additional Step*
  - [ ] *Additional Step*
- [ ] **Deployment**
  - [ ] Edit Docker File
  - [ ] Choose Hosting Platform