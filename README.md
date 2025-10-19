# SciAI-Lab Website

Visit **[sciai-lab.org](https://sciai-lab.org)** 🚀

## Branch protection

The `main` branch is protected, so you can't push changes to the live website immediately. Instead, you need to add changes to a branch and create a pull request.

If you want to make changes using the GitHub interface, you will be notified that you can't commit to `main` and GitHub will tell you that you need to create a new branch after clicking "commit changes". GitHub will offer you to create a pull request from your new branch. Opening a pull request will build a preview. You can download it, unzip it and start a web server in the website's root directory (e.g., using `python -m http.server`) to view your changes. After an approving review, you can merge your changes into the main branch.


## How to create a member page

1) Put a picture of you (or something else if you prefer) into `images/team/<firstname>-<lastname>.jpg`. Color picture. You could use Fred's picture as a template, 1:1 ratio, roughly 1500px, https://sciai-lab.org/images/team/fred-hamprecht.jpg.

2) Add your basic info to `_data/members-list.yaml`:
```
<Firstname Lastname>:
  email: <your email>
  room: Room 4.<xyz>
  phone: +49 6221 54<vwxyz>
  address: Im Neuenheimer Feld 205, 69120 Heidelberg
```

3) Create a `firstname-lastname.md` in `_members` with the following content:
```
---
name: Firstname Lastname
image: images/team/<firstname>-<lastname>.jpg
role: <choose from postdoc, phd, master, bachelor, etc. see `_data/types.yaml`>
links:
  <any additional links you want to add (optional), e.g.>
  twitter: <my_twitter_handle>
---

# Firstname Lastname

Describe your current role in the group, your academic background and your research interests. 

Possibly add something about what you like to do in your free time. 

Possibly add something like a fun fact about you. Feel free to get creative. 
```

_Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_
