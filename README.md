# GraphQL Playground

```
npm install
npm run dev
```

Visit http://localhost:3500 and try the following query in the left pane:

```
query UsersAndFriends {
  users {
    id
    name
    email
    friends {
      id
      name
    }
  }
}
```
