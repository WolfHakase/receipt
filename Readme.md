This is a coding kata based on:
http://codekata.com/kata/kata01-supermarket-pricing/

With the following criteria:
- The project should output a receipt.
- A receipt should contain a list of products.
- Per line on the receipt it should contain `product name`, `amount of items` and `total price`.
- Every line on the receipt can have a subline containing discount.
- A discount line contains `the word discount`, `total currency amount of discount`.
- Below the product lines the following lines should be shown:
  - Total currency amount excluding discount excluding vat
  - Total currency amount of discount
  - Total currency amount excluding vat (including discount)
  - Total currency amount VAT
  - Total currency amount including vat
