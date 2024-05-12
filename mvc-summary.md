ASP.NET MVC Cheat Sheet:

1. Model-View-Controller (MVC) Architecture:
   - Model: Represents the data and business logic of the application.
   - View: Displays the user interface to the user.
   - Controller: Handles user input, manipulates the model, and updates the view.

2. Routing:
   - Define routes in the RouteConfig.cs file to map URLs to controller actions.
   - Use attributes like [Route] and [HttpGet] to define routes at the controller and action level.

3. Controllers:
   - Inherit from the Controller base class.
   - Actions are public methods that handle user requests.
   - Use ActionResult or specific result types (e.g., ViewResult, JsonResult) to return responses.
   - Use attributes like [HttpGet], [HttpPost], [ValidateAntiForgeryToken] to specify HTTP methods and security measures.

4. Views:
   - Represent the user interface.
   - Use Razor syntax (@) to combine HTML and server-side code.
   - Use ViewBag or strongly-typed models to pass data from the controller to the view.
   - Use HTML helpers (@Html) to generate HTML elements and form controls.

5. Models:
   - Represent the data and business logic.
   - Use data annotations for validation and display purposes.
   - Use Entity Framework or other ORMs for database access.

6. Action Results:
   - ViewResult: Returns a view.
   - PartialViewResult: Returns a partial view.
   - JsonResult: Returns JSON data.
   - RedirectResult: Redirects to a specified URL.
   - RedirectToRouteResult: Redirects to a specified route.
   - FileResult: Returns a file to download.

7. Model Binding:
   - Automatically maps HTTP request data to action method parameters or model properties.
   - Use [Bind] attribute to include or exclude specific properties.
   - Use [HttpPost] attribute to prevent model binding from GET requests.

8. Filters:
   - Allow you to implement cross-cutting concerns.
   - Examples: [Authorize], [OutputCache], [HandleError], [ValidateAntiForgeryToken].

9. Validation:
   - Use data annotations for simple validation rules.
   - Use validation attributes like [Required], [StringLength], [Range], etc.
   - Implement custom validation by creating custom validation attributes.

10. Areas:
    - Organize large applications into smaller functional sections.
    - Each area has its own controllers, views, and models.
    - Register areas in the AreaRegistration.cs file.

11. Bundling and Minification:
    - Combine and compress CSS and JavaScript files for improved performance.
    - Define bundles in the BundleConfig.cs file.
    - Use @Scripts.Render and @Styles.Render in the layout view to include bundles.

12. Authentication and Authorization:
    - Use ASP.NET Identity or other authentication providers for user authentication.
    - Use [Authorize] attribute to restrict access to specific actions or controllers.

Remember to refer to the official ASP.NET MVC documentation for detailed information and best practices.