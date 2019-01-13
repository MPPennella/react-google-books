#react-google-books

An app powered by React and MongoDB that allows users to search for books using Google's Books API and mangage a list of books of interest through a Mongo database.

Try it at: [https://react-google-books-mpp.herokuapp.com/](https://react-google-books-mpp.herokuapp.com/)


## Search Page

Allows users to search for books by entering a search term in the search field. Upon submission, the search query is submitted to Google's Books API, and results are shown in a list below, including title, author, a summary,and cover image. Users can click the 'View' button on each book entry to view more detailed info on the Google Play store, or the 'Save' button to save the list of books of interest in the database.


## Saved Page

Allows users to view a list of books that have been previously saved to the database, with similar presentation to the results on the Search page. The 'Delete' button allows users to remove the book from the list of books of interest.