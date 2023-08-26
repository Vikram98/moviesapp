# moviesapp


# Search Route

. When an authenticated user opens the Search Route

    .When a value is provided in the search input and the button with the search icon is clicked

    Make an HTTP GET request to the Search Movies API URL with jwt_token in the Cookies and query parameter search with value as the text provided in the search input
    Loader should be displayed while fetching the data
    
    After the data is fetched successfully, display the list of movies received from the response

    If the HTTP GET request made is unsuccessful, then the failure view given in the Figma screens should be displayed
    
    When the Try Again button is clicked, an HTTP GET request should be made to Search Movies API URL

    When the HTTP GET request made to the Search Movies API URL returns an empty list for movies then Search no results view should be displayed

    When a Movie item is clicked, then the page should be navigated to the Movie Item Details Route
    
    All the header functionalities mentioned in the Home Route should work in this route accordingly
