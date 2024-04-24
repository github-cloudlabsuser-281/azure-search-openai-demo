# Backend

## Description
This is the backend component of the Azure Search OpenAI Demo project. It provides the necessary APIs and services to support the frontend application.

## Installation
1. Clone the repository: `git clone https://github.com/your-username/azure-search-openai-demo.git`
2. Navigate to the backend directory: `cd azure-search-openai-demo/app/backend`
3. Install dependencies: `npm install`

## Configuration
1. Create a `.env` file in the backend directory.
2. Add the following environment variables:
    - `PORT`: The port number on which the server will run.
    - `DATABASE_URL`: The URL of your database.
    - `API_KEY`: Your API key for accessing external services.

## Usage
1. Start the server: `npm start`
2. The backend APIs will be available at `http://localhost:{PORT}`.

## Contributing
Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

## License
This project is licensed under the [MIT License](LICENSE).


# Backend Requirements

The backend of this application has several dependencies that are necessary for its operation. These dependencies are listed in the `requirements.txt` file in the `app/backend` directory. Here are the dependencies:

- `aiofiles==23.2.1`: Required for asynchronous file handling.
- `aiohttp==3.9.3`: Required for asynchronous HTTP requests.
- `aiosignal==1.3.1`: Required for handling signals in an asynchronous context.
- `annotated-types==0.6.0`: Required for type annotations.
- `anyio==4.3.0`: Required for compatibility with multiple asynchronous event loops.
- `asgiref==3.7.2`: Required for ASGI compatibility.
- `attrs==23.2.0`: Required for writing classes without boilerplate.
- `azure-ai-documentintelligence==1.0.0b2`: Required for AI document intelligence services from Azure.
- `azure-common==1.1.28`: Required for common Azure functionalities.
- `azure-core==1.30.1`: Required for core Azure functionalities.
- `azure-core-tracing-opentelemetry==1.0.0b11`: Required for OpenTelemetry tracing with Azure.

Please note that the versions listed are the ones that were used at the time of writing and may be updated in the future. Always refer to the `requirements.txt` file for the most up-to-date list of dependencies.