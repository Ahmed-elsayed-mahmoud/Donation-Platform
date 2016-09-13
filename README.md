# Donation Platform

Online: https://donation-platform.herokuapp.com/

## Project Overview 

It is an online donation platform that creates a positive community of donors. The platform also will help
Non-Governmental Organizations(NGOs) and Charity Organizations build awareness, credibility, and flexibility.

The platform offers an easy and structured method to communicate with donors and facilitate donations, and builds the donors community. 
Finally, donors can also try donating through ways other than money, such as devoting time and skills.


## How To Run

1. Clone the project (git clone https://github.com/Ahmed-elsayed-mahmoud/Donation-Platform.git)
2. Open the terminal to the folder in the project.
3. Type `bundle install`
4. Type `rake db:migrate`
5. Type `rails server`
6. Open your browser and go to http://localhost:3000/

## Project specifications

Donation Platform includes the following features:
- Front page that lists all organizations.
- Each organization has its own page with info, contacts, logo, needs and achievements.
- Each donor has his own profile and his payments.
- Every one can Sign in/Sign up ,but in case of organization sign up, the admin must approve it first before sign in.

Registration must include the following features:
- A registration form that validates user input, and displays the error(s) when necessary.
- After a successful registration, a donor will recieve a welcome email ,but in case of organization registeration, 
the admin will check and approve the org. data then send the welcome email.
- If a user attempts to visit a restricted page without being signed in, then redirect to the Signup page.

Login must include the following features:
- Have a login form that validates user input, and displays the error(s) when necessary.
- Sign in with facebook.

Donors must include the following features:
- Donors should only be able to edit their profiles. They receive an error message if they disobey this rule.
- Donors can see any organization and display its info, contacts, needs and achievements and donate to any need.
- Donors can display all their payments to every organization that they have donated to.

Organizations must include the following features:
- Organizations should only be able to edit their profiles. They receive an error message if they disobey this rule.
- Organizations can add/delete/edit their needs and achievements.

## Setting up your computer

1. [Install Ruby](https://www.ruby-lang.org/en/documentation/installation/) .
2. [Install Rails 5](http://installrails.com/).

## Frameworks/technologies used
- [Bootstrap](http://getbootstrap.com/)
- [omniAuth](https://github.com/omniauth/omniauth)
- [Rails 5](http://weblog.rubyonrails.org/2016/6/30/Rails-5-0-final/)


  
# License

The project is licensed under the [Apache License](LICENSE).