# TickIt-Marketplace-Application

The TickIt Marketplace app notifies users when tickets for their preferred events are available and helps them purchase tickets at their preferred price point.

The aim of the Ticket Marketplace app is to provide a comprehensive overview of ticket prices from both primary and secondary sources across the internet. Users will receive notifications based on their preferences when ticket prices exceed or fall below a specified threshold. By selecting their preferred artists and bands, users will be alerted when concert or tour tickets become available. Additionally, the app empowers users to set a maximum price they are willing to pay for a ticket. If the ticket price drops to that level, the app will automatically purchase the ticket on their behalf, ensuring they never miss an opportunity to attend their favorite events.


# FUNCTIONS:

There are five functions throughout the contract which help users of the application to more easily navigate the market for concert and event tickets. 

The first function is an event creation function, which allows the owner to input details for an event such as the Event ID, the Artist or band name, ticket prices and how many tickets are available or have been sold thus far.

Second, is a ticket purchase function, which allows the user to buy tickets for an event, making sure there are enough funds in their account or that there are tickets available for them to buy.

The third function is for the owner of the contract, allowing only the owner of the contract to withdraw the balance of the contract where users have been sending funds to purchase tickets.

The fourth function allows users of the application to set a desired price for their desired event that they would like to attend. This will help users to be notified when the ticket price has dropped to or below a certain level that they are willing to purchase the ticket at.

Lastly, the fifth function will purchase the ticket for the user at their desired price and for their desired event if their account has enough ether and there are tickets are available

# FUTURE CHANGES AND PROBLEMS

The TickIt Marketplace application is expected to undergo future changes that I encountered some issues with. Specifically, an API integration is planned to automatically update events and concerts within the application, removing the need for the contract owner to perform manual updates. However, accessing the necessary data for the API has proven challenging due to limitations imposed by certain ticket marketplace websites, which may not provide the required data for the API to function properly.

