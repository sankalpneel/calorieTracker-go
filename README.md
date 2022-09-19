# calorieTracker-go

MongoDB
-Create
-Read
-Update
-Delete

Routes


	router.GET("/hello", routes.Hello)
	router.POST("/entry/create", routes.AddEntry) // Crete
	router.GET("/entries", routes.GetEntries) // Read
	router.GET("/entries/:id/", routes.GetEntryById) //  Read by id

	router.PUT("/entry/update/:id", routes.UpdateEntry) // Update
	router.PUT("/ingredient/update/:id", routes.UpdateIngredient) // Update by id
	router.DELETE("/entry/delete/:id", routes.DeleteEntry) // Delete
