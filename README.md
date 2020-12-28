
# Awards

Author: Humphrey Mutuma

## Description

The application will allow a user to post a project they have created and get it reviewed by their peers.

## User Stories

* View posted projects and their details
* Post a project to be rated/reviewed
* Rate/ review other users' projects
* Search for projects 
* View projects overall score
* View my profile page


## BDD

| Behavior                          | Input                                   | Output                             |
| --------------------------------- | --------------------------------------- | ---------------------------------- |
| login/sign up                | enter user details                                    | view site             |
| Search for different categories   | project id                             | displays projects of that category   |
| Filter projects   | click a button                          | displays projects |

##  Prerequisites
* Python3.6
* django
* Postgresql

## Setup/Installation Requirements

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/humphrey-mutuma/Awards.git
$ cd Awards
```

Create a virtual environment to install dependencies and activate it:

```sh
$ python3 -m venv --without-pip virtual
$ source virtual/bin/activate
```
Then install  PIP:
```sh
(virtual)$ curl https://bootstrap.pypa.io/get-pip.py | python
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(virtual)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `venv`.

Once `pip` has finished downloading the dependencies:
```sh
(virtual)$ cd Awards
(virtual)$ python manage.py runserver
```

## How the app works
* A user needs to log in if they have an existing account
* A user can sign up if they do not have an account
* A user then can view a persons profile and the projects they have worked on.


## Support and contact details
Incase of any issues using the site please contact me: [mailto](mailto:humphreymutuma01@gmail.com)

## Known bugs

No known errors. However, if found, contact me here [mailto](mailto:humphreymutuma01@gmail.com)


No known errors. However, if found, contact me here [mailto](mailto:humphreymutuma01@gmail.com)


## Technologies used 

* Python 3.8
* django framework
* Bootstrap
* PostgreSQL

    
## Contributing

Any contributions to this projects will be greatly appreciated. If you want to contribute to it, here are the suggested instructions:
* Clone this GitHub repository to your local machine.


To fix a bug or enhance an existing module, follow these steps:

```buildoutcfg
git clone https://github.com/humphrey-mutuma/Awards.git
```

- Create a new branch (git checkout -b improve-feature)

- Make the appropriate changes in the files

- Add changes to reflect the changes made

- Commit your changes (git commit -am 'Improve feature')

- Push to the branch (git push origin improve-feature)

- Create a Pull Request


## Versioning

Used GIT and GitHub. There are commits attached to the entire project to show the management of versions.

## Copyright

All Rights Reserved by [@humphrey Mutuma](https://github.com/humphrey-mutuma)
Other GitHub can however fork or clone this repository provided the necessary credit is given to the original author.

## License 

This project is licensed under the [MIT License](License). Moringa School moreover retains certain rights to elements in the code of this program.

