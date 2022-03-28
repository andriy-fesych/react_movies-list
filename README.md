# Movies list
- Replace `<your_account>` with your Github username in the
 [DEMO LINK](https://<your_account>.github.io/react_movies-list/)
- Follow the [React task guideline](https://github.com/mate-academy/react_task-guideline#react-tasks-guideline)

## Task
You are given movies loaded from API and the initial markup.
1. Split the markup into `MoviesList` and `MovieCard` components
2. `App` should pass the `moviesFromServer` to the `MoviesList` as a prop
3. `MoviesList` should render a `MovieCard` per each movie
4. All the fields in the `movie` are required

## REQUIREMENTS

- `MovieCard` component should have `data-cy="card"` attribute
- `title` in the `MovieCard` component should have `data-cy="title"` attribute
- `description` `title` in the `MovieCard` component should have `data-cy="description"` attribute
- imbd link `title` in the `MovieCard` should have `data-cy="imbd"` attribute