# DummyJSON Products API Testing

## API Information

**Base URL**
https://dummyjson.com

**Endpoint**
GET /products

---

## Test Objective

Verify that the Products API returns a successful response and valid product data.

---

## Test Steps

1. Open Postman.
2. Create a GET request.
3. Enter the endpoint:
   https://dummyjson.com/products
4. Click **Send**.

---

## Expected Result

- Status code should be **200 OK**.
- Response body should be in JSON format.
- Response should contain a list of products.
- Each product should contain:
  - id
  - title
  - price
  - category
  - stock

---

## Actual Result

The API returned a **200 OK** status and displayed product information in JSON format.

---

## Result

**PASS**
