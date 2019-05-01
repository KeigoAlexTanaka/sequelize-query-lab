## Sequelize Query Lab

- Clone down this repo
- run `npm install`
- run `createdb people_db``
- run `npm run resetDb` and `npm run seed`
- open `main.js` in your editor and add relevant code either as functions that are called in the `main` function or directly in `main`

Problems:

- write a function that fetches all `people` from the db and returns the array
- fetch all the `people` from the db, but only return their `name` and `company`
- fetch only people who have id's greater than 10
- Create two new people and make sure they are saved to the db.  How might you verify this both in psql and using sequelize?
- Fetch one of the people you just created and update/save their role
- Fetch another person you did not create adn update their name to your own
- Create yet another person, verify that they are in the db, then fetch and destroy that person

<details>
  <summary>Hint</summary>
  http://docs.sequelizejs.com/manual/querying.html
</details>
<br />
<br />
Bonus:

Fetch everyone from the db, update _all_ of their `company` columns to `General Assembly` and make sure they are saved to the db.

### Additional Resources
Formatting return data with JSON.stringify: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify
