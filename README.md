## This is a tutorial Project I completed for learning how to use bootstrap with react, using reactstrap to add Bootstrap to React.

I installed Axios as a dependency. Axios is a promise-based HTTP client for the browser and Node.js. It enables me to fetch posts from the Bacon Ipsum JSON API.

The Header component contains the navigation menu.

The Post component renders a post on the page. I initialized the component’s state by setting the post property to null.

After the component was mounted, I utilized the useEffect hook and Axios to retrieve a random post of four paragraphs from the Bacon Ipsum JSON API and change our post field to the data returned from this API.
