# component-land-data

Data for [component.land](https://component.land)

## Adding a component

Open an issue and add:

The project's Github URL

Which category the component is:

- "solution" -- an exposed component that a person would use

- "development" -- a non-exposed component that would be used by other components

📌 Project should have a README that has a brief description of the project, how to use the project and at least 1 screenshot depicting the component

### If you'd like to do a pull request -- even better!

Take a github url, noting the user and repo name and category mentioned above. For the example, we'll use: [https://github.com/effordDev/Contact-Update-Create](https://github.com/effordDev/Contact-Update-Create)

- effordDev

- Contact-Update-Create

- solution

- [https://github.com/effordDev/Contact-Update-Create](https://github.com/effordDev/Contact-Update-Create)

Copy the image address of the screenshot as seen on github

- [https://camo.githubusercontent.com/13c28d504e68ef6cd9fe7d2cb4a2dcc1d520be9a6e496bc7776d3757c421e836/68747470733a2f2f696d6775722e636f6d2f7a3832584655462e706e67](https://camo.githubusercontent.com/13c28d504e68ef6cd9fe7d2cb4a2dcc1d520be9a6e496bc7776d3757c421e836/68747470733a2f2f696d6775722e636f6d2f7a3832584655462e706e67)

And add the new object / project:

```json
 {
    "_id": {
      "$oid": "5e8a9d89b1b0w42ab78gh84h"
    },
    "author": "effordDev",
    "name": "Contact-Update-Create",
    "title": "Contact Update Create",
    "keywords": "contact",
    "description": "Update/create a contact on any Contact child record",
    "image": "https://camo.githubusercontent.com/b94b432b915ef51bdf48a8f3f4bdbd78acd4b0a33a35beb3fb281aca6d946384/68747470733a2f2f692e696d6775722e636f6d2f357756495351432e706e67",
    "deployable": true,
    "platform": "salesforce",
    "type": "solution"
  },
```

---

written while 🤹 by [Jamie Smith](https://jsmith.dev)
