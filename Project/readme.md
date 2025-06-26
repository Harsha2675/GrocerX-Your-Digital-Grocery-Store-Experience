<h1 align='center'> GrocerX - Your Digital Grocery Store Experience </h1>


<h3 align='center'> Backend Setup </h3>

```bash
cd client
npm install
npm start
```


<h3 align='center'> Frontend Setup </h3>

```bash
cd server
npm install
# Create .env file with your configuration like below
npm start
```


<h3 align='center'> .env File </h3>

Create a `.env` file in the `server` directory with the following variables:

```env
# Database Configuration
MONGODB_URI=your_mongodb_url_connection_string

# JWT Secret Keys (Generate strong random strings)
ADMIN_SECRET_TOKEN=your_admin_secret_key_here_make_it_long_and_random
USER_SECRET_TOKEN=your_user_secret_key_here_make_it_long_and_random
SELLER_SECRET_TOKEN=your_seller_secret_key_here_make_it_long_and_random
JWT_SECRET=your_jwt_secret_key_here_make_it_long_and_random

# Server Configuration
PORT=5100
```


