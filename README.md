FCC Mongo & Mongoose Challenges
===============================

Project has `.env` file which needs to be created, it contents should read
```bash
# Environment Config

# store your secrets and config variables in here
# only invited collaborators will be able to see your .env values

# reference these in your code with process.env.SECRET

SECRET=
MADE_WITH=
MONGO_URI=mongodb:// *your access to a mLab mongoDB database*
MONGO_CLUSTER_URI=mongodb+srv:// *your access to MongoDB Atlas cluster*
# note: .env is a shell file so there can't be spaces around =
```

*It should be noted that mLab does not accept any new accounts and you will be automatically redirected to Atlas to create free cluster DB.*

If you create an Atlas cluster DB you will also need to whitelist your IP address, or whitelist `0.0.0.0/0` this allows **all** IP's to access your databases. Whilst not suitable for production, this may be acceptable for testing purposes, like [glitch.com](glitch.com) and tests from the [freeCodeCamp Tutorials](https://learn.freecodecamp.org/)
