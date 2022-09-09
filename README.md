# How to run
## 1. Create database name order_api
## 2. To create test data, use the following command:
```
php artisan migrate --seed
```
### 3. To start the application, use the following command:
```
php artisan migrate --seed
```
### 4. To test the /api/orders endpoint, use the following command:
```
curl --silent http://localhost:8000/api/orders | jq
```
