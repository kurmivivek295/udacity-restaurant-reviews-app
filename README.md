# udacity-restaurant-reviews-app
Udacity Restaurant Review App Code

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

## Solution

We've added media queries to make the web app responsive also we have added Service worker script to cache various assets to improve the performance.

## Usage
In order to view the responsive restaurant reviews app, please follow the below steps:

1. Clone project:
    ```
    $ git clone git@github.com:kurmivivek295/udacity-restaurant-reviews-app.git
    ```
2. Install `http-server` so that we can host our web app locally
    ```
    $ npm install -g http-server
    ```
3. replace `<YOUR-GOOGLE-MAP-API-KEY>` with your google map api key in the `script` tag of `index.html` and `register.html` files.
	
4. Make sure you are in the root directory of the application and run the below command which will start serving current directory as web app:
    ```
    $ http-server -p 9090 --cors
    ```
5. Open the url `http://127.0.0.1:9090/` in the browser, and here you have the responsive restaurant reviews app.
