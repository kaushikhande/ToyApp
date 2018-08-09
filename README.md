# Sample toy application
## Contents
* User and Micropost scaffold
* Root to users#index
* Validation of user model
* Validation of micropost model
* No relation in between them

## Getting Started
To get started clone the repo and then install the gems

```bash
$ bundle install --without production
```

Next, migrate the database

```bash
$ rails db:migrate
```

Finally run the test suite to verify that everything is in place

```bash
$ rails test
```

If the test suite passes, the run the application 
```bash
$ rails server
```
Open the browser and type localhost:3000 in the url

