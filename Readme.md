# LinkDOC

LinkDOC is a web application that allows users to upload documents or PDFs and generate shareable links. This service is built using React for the front end, Tailwind CSS for styling, Supabase for the backend, and ShadcnUI for the UI components.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- **Document Upload:** Users can upload documents or PDFs.
- **Shareable Links:** Generates a unique, shareable link for each uploaded document.
- **User Authentication:** Users can sign up, log in, and manage their documents.

## Tech Stack

- **Frontend:** ReactJS
- **Styling:** Tailwind CSS
- **Backend:** Supabase
- **UI Components:** ShadcnUI

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Node.js and npm installed on your local machine.

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/linkdoc.git
    cd linkdoc
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up Supabase:**

    - Create a project on Supabase.
    - Copy your Supabase URL and anon key.
    - Create a `.env` file in the root directory and add your Supabase credentials:

      ```env
      REACT_APP_SUPABASE_URL=your-supabase-url
      REACT_APP_SUPABASE_ANON_KEY=your-supabase-anon-key
      ```

4. **Run the application:**

    ```bash
    npm start
    ```

## Usage

1. **Sign Up / Log In:** Create an account or log in to your existing account.
2. **Upload Document:** Use the upload feature to add your document or PDF.
3. **Share Link:** Copy the generated shareable link and share it with others.

## Contributing

Contributions are what make the open-source community such an amazing place to be. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Supabase](https://supabase.io/)
- [ShadcnUI](https://shadcnui.com/)
