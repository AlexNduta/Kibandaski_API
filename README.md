# Kibandaski_API

- What if you could shop in any supermarket and still get the best offers in town at the comfort of your house?
- Kibandaski does just that. 
- The API basically scraps different popular supermarkets and gets you the best deals in the market.
- Client(Android) comming soon

# Features
1. Product Search
- Allow users to search products by name or category.
2. Price Comparison
- Display prices from different supermarkets for the searched product.
3. Highlight the cheapest option
- Make sure that the client knows the cheapest option
4. Order creation
- Users can create orders with chosen products and specify delivery info
5. Order status
- Users can track status of their orders(placed, processing, delivered)

NB: payment should be COD until the payment gateway is delivered

# structure

```sh

├── API
│   ├── Data-Layer
│   ├── Delivery
│   ├── Engine
│   └── Order
├── DB
├── LICENSE
└── README.md
```

## `API` 
- handles all Api related logic
### `Data-Layer`
- Data source related queries
- web scrapping Logic
- Data input(feeds) logic
### `Engine`
- This is the comparison Engine
- Analyses the prices and suggest the cheapest option from different stored

### `Order`
- Checkout and order processing
- Order creation, tracking status(places/ processing), flag out of stock items

### `Delivery`
- This handles order tracking logic

## `DB`
- contains any database related code
