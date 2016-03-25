Follow these step to contribute:  

---

###### Step #1: Pull Github repository ######

---

##### Step #2: Committing your changes #####

Example:
- added a **navbar** component to library

```Shell
$ git add .
$ git commit -m "navbar: some styling in top toolbar"
```

---

###### Step #3: Update bower package version ######
```Shell
$ npm version [<newversion> | major | minor | patch] -m "Upgrade for whatever reasons"
```

---

##### Step #4: Pushing your changes #####

```Shell
$ git push origin master; git push origin --tags
```

---

##### Step #6: Pull the changes to your project #####

- To pull latest changes into your project, run:
```Shell
$ npm update
```

