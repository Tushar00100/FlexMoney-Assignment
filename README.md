# FlexMoney Assignment

## Yoga Registration Form

### The project is divided into three section

1. Registration form
2. Making Payment
3. Confirmation and Database storage

Frontend is made with handlebars. It is a Javascript library used to create reusable webpage templates.

### Registration Page

1. User need to fill their basic details.
2. Any user age between 18 - 65 can register on the portal.
3. After successful registration of new user, you get redirected to payment page.

### Payment Page

1. After successful registration, user need to pay a fixed amount of INR 500/-.
2. User need to fill the card detail.
3. After filling correct information, payment will be successful and confirmation message is shown.

### Confirmation Page

After successful payment, a comfirmation will be shown.

### Database

After successful payment, user data is stored in the mongodb database.
Data includes name, email, password, phone, age, Batch timing.

## Important Assumptions made

1. There is no need of login and verification, just register and pay and you get your slot.
2. Every user have a unique ID which will be used to access the service within slot.
3. Payment detail is not stored just shown there.
4. By clicking on Payment button, payment will be successful.
5. Validity of one time payment is till last day of the month.
6. User need to register and make payment again for booking a new slot.
7. User cannot book more than one time in a month to avoid clash with other slot.
8. Users are Indian citizen.
9. 10 digit mobile no validation.
10. The validation is done for the registration page only.
11. Plain password is stored in the database.
