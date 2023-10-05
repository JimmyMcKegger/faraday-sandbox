
# Faraday Sandbox

A Ruby script using Faraday to make GraphQL requests.

## Setup

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/JimmyMckegger/faraday-sandbox.git
   ```

2. Navigate to the project directory:

   ```bash
   cd faraday-sandbox
   ```

3. Create a `.env` file in the project directory and add your GraphQL URL and API token as follows:

   ```env
   URL=my-example-url.com
   API_TOKEN=qwerty_1234sdf234234asdfasdf234234
   API_VERSION=2023-10
   ```

4. (Optional) If you haven't already, you can make the `req` file executable:

   ```bash
   chmod +x req
   ```

## Usage

To run the script and make GraphQL requests, use the following command:

```bash
ruby req
```

This script uses Faraday to send a GraphQL query and prints the response using Awesome Print for better readability.

## Customization

You can customize the GraphQL query by modifying the `gql_body` variable in the `req` script.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
