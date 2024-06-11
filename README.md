# Unit2.testSpecifications

Unit Tests:
    1.A function called "multiplication" that returns the product of the two
    input numbers.
        •Expect multiplication(3, 5) to be a number
        •Expect multiplication(3, 5) to be 15
        •Expect multiplication(“b”, 5) to give an error
        •Expect multiplication($, 5) to give an error message
    2.A function called "concatOdds" takes two arrays of integers as
    arguments. It should return a single array that only contains the odd
    numbers, in ascending order, from both of the arrays.
    ConcatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) should result in [-1, 1, 3, 9,
    15]
        •non-numbers, strings and characters and operators should return an error message
        •repeat numbers should be returned individually
        •numbers should follow numerical order in the new array
        •user should be prompted on how to fill out the form
        •an error message should appear if any other amount than 2 arrays are used
        Functional Tests:
            A shopping cart checkout feature that allows a user to check out as a
            guest (without an account), or as a logged-in user. They should be allowed to
            do either, but should be asked if they want to create an account or log in if
            they check out as a guest.
        •If cart is empty and the user tries to check out, the user should be
        given a message to tell them their cart is empty, but still ask if
        they would like to log in.
        •during each step of checkout there should be a link on the page to
        log in or sign up
        •if user is logged in there should be an account frame showing this
        and a log out link should be visible
        •if the browser takes them to another page to log in – ie. google,
        then they should be returned to the page or the page should
        update as soon as they log in
        •if the user inputs an erroneous user name or password they should
        get an error message, ie. forgot password or forgot username
        •if the user tries to create an account with an email already on
        record they should be notified accordingly.
        •If the user is logging in from a new device an email could be sent
        to their inbox to help minimize fraud.
