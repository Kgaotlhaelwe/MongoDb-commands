##To start the MongoDB shell, use the following command:

mongosh

To create or switch to the `Codetribe` database, use the following command:

use Codetribe

To create the collections, use the following commands:

db.createCollection("Facilitators")
db.createCollection("Trainees")
db.createCollection("Projects")


Insert a document into the `Facilitators` collection:

db.Facilitators.insertOne({
  Name: "John Doe",
  Location: "Kimberley",
  Course: "Web Development"
})


Insert a document into the `Trainees` collection:

db.Trainees.insertOne({
  Name: "Jane Smith",
  Location: "Kimberley",
  Facilitator: "John Doe"
})

Insert a document into the `Projects` collection:
db.Projects.insertOne({
  Name: "Project X",
  Course: "Web Development",
  Lesson: "React Basics"
})
