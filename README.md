# mwkart
Django eCommerce Application with Product Variants, Orders, Rating System and much more


<p align="left">
  <a href="[[https://www.linkedin.com/in/dydevops](https://www.linkedin.com/in/dydevops/)](https://www.linkedin.com/in/dydevops/)" target="_blank"><img alt="LinkedIn" title="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://www.youtube.com/channel/UCYesptHRU1QZ2pHZkAqdQTw/videos" target="_blank"><img alt="YouTube" title="YouTube" src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a>
</p>

# About The Project
MWKart is an eCommerce application built with Python Django Framework. Some of the features of this project includes custom user model, categories and products, Carts, Incrementing, Decrementing and removing car items, Unlimited Product image gallery, Orders, Payments, after-order functionalities such as reduce the quantify of sold products, send the order received email, clearing the cart, Order completion page as well as generating an invoice for the order. Also we have a Review and Rating system with the interactive rating stars that even allows you to rate a half-star rating. My account functionalities for the customer who can easily edit his profile, profile pictures, change his account password, and also manage his orders and much more.

<img src="https://github.com/dydevops/mwkart/media/mwkar-screenshot.jpg">

# Setup Instructions

1. Clone the repository `git clone https://github.com/dydevops/mwkart.git`
2. Navigrate to the working directory `cd mwkart`
3. Open the project from the code editor `code .` or `atom .`
4. Create virtual environment `python -m venv env`
5. Activate the virtual environment `source env/Scripts/activate`
6. Install required packages to run the project `pip install -r requirements.txt`
7. Rename _.env-sample_ to _.env_
8. Fill up the environment variables:
    EMAIL_HOST=smtp.gmail.com
    EMAIL_PORT=587
    EMAIL_HOST_USER=youremailaddress@gmail.com
    EMAIL_HOST_PASSWORD=yourStrongPassword
    EMAIL_USE_TLS=True
    ```
    _Note: If you are using gmail account, make sure you [turn ON the less secure apps](https://myaccount.google.com/lesssecureapps)_
9. Create database tables
    ```sh
    python manage.py migrate
    ```
10. Create a super user
    ```sh
    python manage.py createsuperuser
    ```
    _GitBash users may have to run this to create a super user - `winpty python manage.py createsuperuser`_
11. Run server
    ```sh
    python manage.py runserver
    ```
12. Login to admin panel - (`http://127.0.0.1:8000/admin/`)
13. Add categories, products, add variations, register user, login, place orders and EXPLORE SO MANY FEATURES


[Demo Video](#)

## Support
💙 If you like this project, give it a ⭐ and share it with friends!

Made with ❤️ and Python
