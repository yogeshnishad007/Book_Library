
# Triluxo Backend

This is the backend application for Triluxo. It's an Express.js application that interacts with a MongoDB database to manage books.


## Getting Started

### Prerequisites
- Node.js installed
- MongoDB installed and running

### Installation
1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/Triluxo-Backend.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Triluxo-Backend
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

## Usage

### Home Page
To access the home page, navigate to [https://lovely-moccasins-eel.cyclic.app/](https://lovely-moccasins-eel.cyclic.app/) in your browser.

### Get Books Data
Retrieve a list of books:

```http
GET /books
POST /post
PUT /update/:Id
DELETE /delete/:id

