# nodejs_collaboration
Maxwill Isaacs(Nodejs) &
Brandon Swinton(Mysql)

MYSQL
module.exports = {
    HOST: "bmxegzjhcdkzwzucx5xc-mysql.services.clever-cloud.com",
    USER: "ubdldcz2m7ujwx7m", 
    PASSWORD: "wkwBEmWDsaJqpX4t4xJw",
    DB: "bmxegzjhcdkzwzucx5xc"
  };
  
  Routes
   // Create a new Tutorial
    router.post("/", tutorials.create);
  
    // Retrieve all Tutorials
    router.get("/", tutorials.findAll);
  
    // Retrieve all published Tutorials
    router.get("/published", tutorials.findAllPublished);
  
    // Retrieve a single Tutorial with id
    router.get("/:id", tutorials.findOne);
  
    // Update a Tutorial with id
    router.put("/:id", tutorials.update);
  
    // Delete a Tutorial with id
    router.delete("/:id", tutorials.delete);
  
    // Delete all Tutorials
    router.delete("/", tutorials.deleteAll);
  
  
