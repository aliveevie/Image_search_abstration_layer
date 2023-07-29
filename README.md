# Image Search Abstraction Layer

The Image Search Abstraction Layer is a Node.js application that allows users to search for images using a search query and get the most relevant images from various search engines or image repositories.

## Features

- Search for images using a search query.
- Retrieve the most relevant images based on the search query.
- Pagination support to view more search results.
- Option to specify the number of results per page.
- Recent search history.

## Getting Started

### Prerequisites

- Node.js and npm (Node Package Manager) installed on your system.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/aliveevie/Image_search_abstration_layer.git

2. cd image-search-abstraction-layer
3. npm install
4. npm start

### API Endpoints
GET /query/
Use this endpoint to search for images based on the provided q parameter (search query). The server will respond with a JSON array containing the search results.

### GET /recent
Use this endpoint to retrieve the recent search history. The server will respond with a JSON array containing the most recent search queries.

### Dependencies
Express.js: Fast, unopinionated, minimalist web framework for Node.js.
Axios: Promise-based HTTP client for Node.js.
Dotenv: Zero-dependency module that loads environment variables from a .env file.

### Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.