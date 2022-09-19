# calorieTracker-go

MongoDB
-Create
-Read
-Update
-Delete

Routes


	router.GET("/hello", routes.Hello)
	router.POST("/entry/create", routes.AddEntry)
	router.GET("/entries", routes.GetEntries)
	router.GET("/entries/:id/", routes.GetEntryById)
	router.GET("ingredient/:ingredient", routes.GetEntriesByIngredient)

	router.PUT("/entry/update/:id", routes.UpdateEntry)
	router.PUT("/ingredient/update/:id", routes.UpdateIngredient)
	router.DELETE("/entry/delete/:id", routes.DeleteEntry)
