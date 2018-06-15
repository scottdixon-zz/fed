## Getting Started

1. Clone the repo and create a ThemeKit config file.
 ```
 $ git clone git@github.com:scottdixon/fed-assignment.git
 $ cd fed-assignment
 $ touch config.yml
 ```

2. Update the config file to include development and production environment details:
```
development:
  password: <api-password>
  theme_id: "37053268026"
  store: fed-assignment.myshopify.com
production:
  password: <api-password>
  theme_id: "37050417210"
  store: fed-assignment.myshopify.com
```


## Developing

`$ yarn serve` will launch the development theme in the browser and start ThemeKit. ThemeKit will listen for changes to the files and upload them automatically.


## Deploying

`$ yarn deploy` will deploy the latest changes to production.
