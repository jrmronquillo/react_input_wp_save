# react_input_wp_save
# this app was bootstrapped from create-react-app


run for development:
`cd my-app`
`npm run start`

create production build:
`cd my-app`
`npm run build`

mv /build/static to wordpress child theme

create a wordpress page template

`front-page.php`

add script tags that point to associated react files


edit funtions.php in child theme to enqueue react styles from /static directory


# notes:
wp db was set up manually in dev environment with a table called 'wp_destinations'

# what:

App allows user to input a string. Upon submission, that string is saved to the wp database.





# Features:
# v1
-boilerplate for user input
-handleSubmit function -> sends POST request with user input value.

