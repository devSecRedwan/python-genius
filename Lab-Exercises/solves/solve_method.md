## For exercise 1
### Steps behind the solve
I solve this problem by following these steps below:
 1. At first, I ask user a question that what is his/her name and store
    it in a variable as an user input. For ensuring user is not
    providing blank value I use a `while` loop and warning users until
    he/she does not provide any input against this question.
 2. Then I ask for the age and verify is it in between 10 to 120 years
    because we don't want that our system is used by a child less than
    ten, and usually no human being alive after 120 years (except some
    rare cases).
 3. Then I ask for provided his developer status within boolean values that true or false. Here I also ensure that no null value is providing by users using `while` loop.
 4. Then I made a dictionary for the roles of users.
 5. Then I check those conditions using `if-elif-else` and `print` current role for the user with a greeting message.

### Limitations
**N.B:**
Though I check null value. But user can provide any string for his name. Because there are no limitation in the name field except null or empty string. It could be a single character to thousand of characters, with this advantage any malicious user can inject payload or malicious code or script to our program and there is a high risk that it could be compromise by that.

