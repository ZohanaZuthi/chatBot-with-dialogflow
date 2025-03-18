
# Food Website FAQ Chatbot

## Description
This project is a chatbot built using **Dialogflow** for handling frequently asked questions (FAQ) and providing customer support on a food-related website. The chatbot assists users in various ways, including placing orders, tracking existing orders, viewing ongoing and upcoming offers, and providing store hours. It is designed to offer a smooth and efficient experience for customers, answering their queries and guiding them through the website's offerings.

The chatbot uses **Dialogflow**'s natural language processing (NLP) capabilities to understand customer inputs and provide relevant responses, ensuring customers get quick and accurate answers to their questions.

## Features
- **New Order**: Helps customers place a new order by guiding them through the menu and order process.
- **Track Order**:
  - **Track Order by Order ID**: Allows users to check the status of their order using the unique order ID.
  - **Track Order by Phone Number**: Lets customers track their order status using their phone number.
  - **Track Order by Customer Name**: Customers can track their order status by providing their name.
- **Store Hours**: Provides the working hours of the restaurant, including opening and closing times.
- **Offers**:
  - **Ongoing Offers**: Displays current promotions, discounts, and special offers available for customers.
  - **Upcoming Offers**: Notifies users about upcoming offers or seasonal discounts.
- **Support Payment**: Provides assistance with payment methods, including troubleshooting payment issues or explaining accepted payment methods.

## Technologies Used
- **Dialogflow**: For building the conversational agent and processing natural language inputs.
- **Node.js**: For backend support and integrations.
- **Firebase** (Optional): For storing real-time data like order status, menu updates, etc.
- **API Integration**: To fetch real-time data such as order statuses, menu details, and offer updates.

## Setup & Installation

1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up a Dialogflow account and create a new agent:
   - Go to [Dialogflow Console](https://dialogflow.cloud.google.com/)
   - Create a new agent and configure intents based on the FAQ.

5. Configure the Dialogflow API:
   - Obtain your credentials from the Dialogflow Console.
   - Set up the Dialogflow API in your project to connect the backend with Dialogflow.

6. Run the application:
   ```bash
   npm start
   ```

## Usage
- Users can interact with the chatbot through the website’s chat interface.
- The chatbot will respond to user queries based on predefined intents such as placing new orders, tracking orders, and providing information about ongoing offers and store hours.

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. We welcome suggestions for new features, enhancements, or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
