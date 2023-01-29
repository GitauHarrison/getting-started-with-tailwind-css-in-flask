# Getting Started With Tailwind CSS in Flask

![Tailwind Flask](/app/static/images/tailwind_flask.gif)

[Tailwind CSS](https://tailwindcss.com/) is a utility-first CSS framework. To better understand it, we can contrast it with other popular frameworks such as [Bootstrap](https://getbootstrap.com/) or [Materialize CSS](https://materializecss.com/). These other frameworks come with predefined components, but Tailwind CSS does not. Instead, it operates on a lower level and provides us with a set of CSS helper classes. Using these classes, we can rapidly create a custom (unopinionated) design with ease.

## Learn More

If you want to use Tailwind CSS in Flask, you can learn more [here](https://github.com/GitauHarrison/notes/blob/master/tailwindcss/getting_started_tailwindcss.md). 


## Test Locally

Alternatively, clone this repo to test it locally:

1. Clone this repo:

    ```python
    git clone git@github.com:GitauHarrison/getting-started-with-tailwind-css-in-flask.git`
    ```

2. Change directory to the new repo:

    ```python
    cd getting-started-with-tailwind-css-in-flask
    ```

3. Create and activate a virtual environment:

    ```python
    $ virtualenv venv
    ```

4. Install dependencies:

    ```python
    (venv)$ pip install -r requirements.txt
    ```

5. Run the server:

    ```python
    (venv)$ flask run
    ```

6. Open the browser and navigate to http://localhost:5000/