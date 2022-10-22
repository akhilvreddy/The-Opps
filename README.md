# The Opps - A way to make friends :)

We aim to allow people to make friends based on their common enemies. As more and more people find out that their enemies are linked with other enemies, you will start to see friendships through that again.

We also live by the quote that “an eye for an eye makes the whole world blind”. We aim to help people understand that somewhere down the road, you are going to have to use one’s help again. 

MERN

Front End in **React & Redux**

Back End in **Node & Express**

Database in **MongoDB** 

### MongoDB Schema

```
Users = 
[
  {
    userID: Number
    username: String 
    email: String,
    password: String,
    friends:   [String]    //  [“friend1”, “friend2”, “friend3”, …]
    opps:      [String]    //    [“opp1”, “opp2”, “opp3”, …]
  }
]
```
