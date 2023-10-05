
# Faraday Sandbox

A Ruby script using Faraday to make GraphQL requests to a Shopify store.

## Prerequisites

Before running this script, make sure you have the following:

1. Ruby installed on your system.
2. A Shopify store with a valid API token.

## Setup

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/JimmyMckegger/faraday-sandbox.git
   ```

2. Navigate to the project directory:

   ```bash
   cd faraday-sandbox
   ```

3. Create a `.env` file in the project directory and add your Shopify store URL and API token as follows:

   ```env
   SHOP=my-shop.myshopify.com
   API_TOKEN=shppa_1234sdf234234asdfasdf234234
   API_VERSION=2023-10
   ```

4. (Optional) If you haven't already, you can make the `req` file executable:

   ```bash
   chmod +x req
   ```

## Usage

To run the script and make GraphQL requests to your Shopify store, use the following command:

```bash
ruby req
```

This script uses Faraday to send a GraphQL query to your Shopify store's GraphQL endpoint and prints the response using Awesome Print for better readability.

## Customization

You can customize the GraphQL query by modifying the `gql_body` variable in the `req` script. Refer to the [Shopify GraphQL documentation](https://shopify.dev/docs/admin-api/graphql) for more information on available queries and mutations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
