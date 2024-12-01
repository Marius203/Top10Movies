# Top10Movies

This project is a Flask web application that allows users to manage a list of their top 10 movies. Users can add movies to the list by searching for them using the Movie Database API, and can also rate and review the movies.

## Requirements

To run this project, you need to have Python installed. You will also need to install the required Python packages. You can install them using the following command:

```sh
pip install Flask Flask-Bootstrap Flask-SQLAlchemy Flask-WTF requests
```

1.Clone the repository
git clone https://github.com/Marius203/Top10Movies.git
cd Top10Movies

2.Set up environment variables
export MOVIES_API_KEY="Your Key"

3.run the application
py main.py

The home page will display the list of top 10 movies.
Use the "Add Movie" button to search for and add a new movie.
Use the "Edit" button to rate and review a movie.
Use the "Delete" button to remove a movie from the list.
