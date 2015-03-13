## General To-dos for the RSD ##

  1. Develop mock-ups and scenarios for the RSD.
  1. If the requirements cannot all be accomodated, the design should be open for extensibility
  1. In the first RSD, we will scale down the requirements (see below) to a **minimum viable product**.
  1. There is no common RDF data on nutrition we could find, S Uskudarli will check for a common data set both groups can work on.

## Functional Requirements ##

_At the minimum_:

  * The system shall exhibit basic social network features. i.e.:
  * There will be a user construct, supporting login, registration and logout
  * The users shall be able to follow one another in Twitter-like asymmetric follow links
  * When logged into the system, the user will be able to see a news feed of what other users he/she is following have been up to
  * The system will support basic messaging, i.e. users will be able to send/recommend recipes to one another
  * Users will be able to enter/share recipes of their own
  * Users will be able to search the overall recipe database by querying with ingredient

_In the future_:
  * Users will be able to rate the recipes they encounter within the system
  * Users will be able to define constraints for recipe searches like ailments, calorie goals, definitive personal preferences (e.g. I don't eat pork)
  * The system shall return a unique set of recipes to each user based on prior ratings, preferences of network, and their recipes.

## Non-functional Requirements ##

  * Use of RDF/semantic data is recommended but **not required**.
  * There are no constraints for the server backend (programming language, database type, database engine)
  * The system shall present a web frontend
  * The system shall comprise a mobile client, which **must** be in Android