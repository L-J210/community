---

# FILENAME : please use your OpenClassrooms's name, available in your url.
# Example: https://openclassrooms.com/membres/celinemartinet
# must be the name of your file. If file name is celinemartinet.md, title is celinemartinet.
# lowercase, no blank space, Capital case or special character.
title: tony

# First name or full name
name: Tony
date: 2020-09-28 14:00

# One line.
# If you need more space, go to the next line and add 4 spaces on the left, as in 'description'.
objective: Réussir ma reconversion professionnelle et changer de vie.
short_description: Développeur en devenir!

# Ne modifiez pas le paramètre 'template', seulement la description
template: students
description:
    J'ai 40 ans, et je cherche à me reconvertir dans l'informatique.

# image must be located in content/images/students
# name should be the same as this file. Eg: celinemartinet.png
image: tony.jpg

# Change this to True when you do you pull request.
public: True

# You need to keep the exact same structure for each new project.
projects:
  - title: Présentez-vous !
    description: Une présentation de moi-même et un lien vers mon LinkedIn.
    # Create a new repository for your images. Name it the same as your nickname and profile picture.
    # Image must be here: content/images/students/yourrepo/project1.png
    image: tony/projet1.png
    link: https://www.linkedin.com/in/tony-alexandre-g-844a341a3/
    # 'true' makes it fully available.
    # 'false' will add a black layer on the picture. IT WILL BE PUBLIC!
    finished: true
  - title: Intégrez la communauté !
    description: Modifier un projet Open Source pour comprendre le fonctionnement de Git, Github et des PullRequest.
    image: tony/projet2.png
    link: https://github.com/Tony380
    finished: true
  - title: Aidez MacGyver à sortir !
    description: Création d’un jeu développé en Python et utilisant PyGame.
    image: tony/projet3.png
    link: https://github.com/Tony380
    finished: false
---