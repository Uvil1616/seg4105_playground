## Pitch
At Erwind's and Friends' Bike Shop, our website is naturally intuitive and simple to manage. All the information is laid out in a neat and concise manner making it easy for the user to navigate and find the resources they are looking for. One area of improvement, however, would be the appointment request.

(See "Appointment Form.jpg")

This form is easily filled out and ensures we provide the exact type of service the customer is looking for however it can be quite tiresome. Especially, when it comes to a recurring appointment like a tune-up. Surely, there is an even easier method that eases up the repetitive nature of these forms. We're not servicing millionaires and their yachts, how complicated should it be to fix a bike?

## Accounts
The solution is simple and obvious. Just like every other website known to man, we just need to make an account system. By having the user register an account with our website we can securely store their personal information and auto-fill the fields in the request form.

(See "nav bar.jpg")

To allow the user to create an account we will have to add an option to sign in to the current Navbar. Such an option can be added easily with very little change, only altering the font and positioning of the current links. Once the user chooses to "Sign In," they will be approached with a screen, potentially a pop-up that allows them to enter their email and password to sign in.

(See "login window.jpg")

If they do not have an account already they can click on the link to create one and will be directed to a landing page asking for all relevant information.

(See "Register form.jpg")

Once they are finished signing in, or they have finished making an account, they will be redirected to the home page, except this time the fields within the "Book an Appointment" section will already be filled out.

(See "Autofill.jpg")

Of course, being signed in, the sign-in option in the Navbar will then be replaced by the logout option. There isn't any reason to have both of them available at the same time since the user may only be in one state and any given time: signed in or not.

Such a task will most likely take the full 6-weeks as an immense overhaul of the back-end will be required. This will involve creating a database from scratch to store and retrieve saved information and auto-fill the fields within the "Book an Appointment Section." As mentioned earlier, the few UI changes will also require minor tweaks to the current design as well as a landing page for users to create their accounts.

Some rabbit holes to be mindful of is the organization of personal information and passwords. As we are a local business there will not be as many users as some much larger-scale bike shops. With this in mind, we may store the information as simply as possible and will not bother checking for common emails. For this stage, we can assume that each user will have a unique email and will not worry about duplicates. It should also be noted that passwords will not have the usual restrictions in place but will require at least a single character. If a password is input incorrectly the website will simply repeat the popup. Again this will be left up to the user's discretion.

One no-go is that we will be foregoing security for now, and thus will not ask for the user's credit card information. To ensure we will retain the safety of our users, we will require they manually input such information. While such a feature may be of interest in the future, it will not be a concern in this cycle.