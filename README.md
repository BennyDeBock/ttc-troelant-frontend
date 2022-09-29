# TTC Troelant front-end

This project contains the front-end code for the [TTC Troelant website](https://www.ttctroelant.be).
Added functionality is needed to the website, so that other administrative persons in the club are able to make changes, which is not the case currently.

## Functions Needed
### Contributer functions

- [ ] Add blog posts
  * Posts should include a title, a date and the body. Functionality is needed to be able to add pictures to the body.
  * Posts should be editable at a later date
  * Posts should be able to be deleted
- [ ] Add photo's to an album
- [ ] Add video links to the video section
- [ ] Be able to log in
- [ ] Be able to change the user password

### Administrative functions

- [ ] All of the above
- [ ] Create Custom pages with html or markdown

## Tech stack

CSS Framework: Tailwind
JS Framework: Vue
Image storage: AWS S3 Bucket

## Possible future additions
- Login for other members
- Include a sign-up form to join the club
- Create a planner for the team captains that notifies members if they're planned to play.


## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
