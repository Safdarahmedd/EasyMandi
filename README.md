# EasyMandi

Easy Mandi is an innovative solution for agricultural trading in India in response to the “farmers' protests” of 2020. Farmers can auction their produce on the decentralised application. Agreed-upon deals are stored in a smart contract that executes the transfer of funds upon delivery.

![easymandi](https://user-images.githubusercontent.com/59877986/220214731-5bb1ad1d-e014-4aa9-a1cc-9fcabeceb5b0.jpg)

# Getting Started

First clone the repository from Github and switch to the new directory:

    $ git clone git@github.com/Safdarahmedd/EasyMandi.git
    $ cd EasyMandi
    
Activate the virtualenv for your project.
    
    
## Starting the React Frontend 

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.



## Running the Django Backend

Install project dependencies:

    $ pip install -r requirements/local.txt
    
    
Then simply apply the migrations:

    $ python manage.py migrate
    

You can now run the development server:

    $ python manage.py runserver
