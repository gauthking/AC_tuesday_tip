# React-Router-Dom

For routing and navigating into different pages and routes of our web application, we can make use of the "react-router-dom" package.

#### For using this functionality in our REACT App

- first install the "react-router-dom" package using - ``npm install react-router-dom``
- then in our App.js file, we import the following 

<img src="https://user-images.githubusercontent.com/90638995/182850255-7648bff9-c6a1-4002-91bc-d83860a333ee.png" width=50% />

- Now we'll be creating a simple app that can navigate between pages and this can be implemented using react-router
- for that, first we create the routes for the two pages - Home Page and Next Page, in our App.js file:

<img src= "https://user-images.githubusercontent.com/90638995/182858021-9641d333-fa4d-4155-969c-d697240d7806.png" width=60% />

Home.js (default page having path of just '/')

<img src="https://user-images.githubusercontent.com/90638995/182858843-62dd3392-1173-4bb3-96f2-4787342e6bf2.png" width=60% />

 - in here we wrap the `button` tag with a `Link` tag from react-router-dom, which provides accessible navigation around your application and we set the `to` attribute to "/nextpage" so that whenever user clicks on it, then it will redirect into the route having a path of "/nextpage" in our App
 
 - in our App.js we defined the route for "/nextpage" i.e. to render the `<Nextpage />` component in our App.
 ![image](https://user-images.githubusercontent.com/90638995/182861632-04e9b6f0-f933-4cd6-a50e-b9d301f7a2e0.png)

- similary in Nextpage.js, we route the button back to the home page

Nextpage.js (having a path of '/nextpage')

![image](https://user-images.githubusercontent.com/90638995/182864228-cd4698da-79a9-407b-abad-77481e9143a4.png)

- now we test the react-router-dom functionality by running the app in dev mode - `npm run start`

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/90638995/182866460-ee3fd9cf-4165-4dd3-bdf4-7f5cd9bc1c56.gif)




