# DocQuify: AI-Powered Document Querying Platform

![GitHub release](https://img.shields.io/github/release/maharishiayurveda/DocQuify.svg)
[![Download Releases](https://img.shields.io/badge/Download%20Releases-blue.svg)](https://github.com/maharishiayurveda/DocQuify/releases)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

DocQuify is an AI-powered document querying platform designed to enhance the way users interact with PDFs. Users can upload documents such as research papers and technical manuals, then ask context-based questions. Leveraging OpenAI's capabilities and advanced vector search technology, DocQuify provides intelligent answers tailored to the content of the uploaded documents.

## Features

- **AI-Powered Queries**: Use OpenAI to ask questions about your documents and receive accurate, context-based answers.
- **PDF Upload**: Seamlessly upload PDFs for analysis.
- **Smart Semantic Search**: Integrate with Pinecone for efficient vector-based searches, ensuring quick retrieval of relevant information.
- **AWS S3 Storage**: Store your documents securely in AWS S3, ensuring reliability and scalability.
- **Google Authentication**: Easy and secure sign-in using Google accounts.

## Technologies Used

- **Next.js 14**: A powerful React framework for building server-side rendered applications.
- **OpenAI API**: For generating intelligent responses to user queries.
- **Pinecone**: A vector database that supports semantic search capabilities.
- **AWS S3**: For secure document storage.
- **Clerk Auth**: For user authentication and management.

## Installation

To get started with DocQuify, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/maharishiayurveda/DocQuify.git
   cd DocQuify
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env.local` file in the root directory and add the following variables:
   ```
   OPENAI_API_KEY=your_openai_api_key
   AWS_S3_BUCKET=your_aws_s3_bucket_name
   PINECONE_API_KEY=your_pinecone_api_key
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   ```

4. **Run the Application**:
   ```bash
   npm run dev
   ```

5. **Access the Application**:
   Open your browser and go to `http://localhost:3000`.

## Usage

1. **Upload a PDF**: Click on the upload button to select a PDF file from your device.
2. **Ask Questions**: After uploading, type your questions in the query box.
3. **Receive Answers**: The AI will analyze the document and provide context-based answers.
4. **Explore Results**: Use the semantic search feature to explore related content within the document.

## Contributing

We welcome contributions to DocQuify. If you would like to contribute, please follow these steps:

1. **Fork the Repository**: Click on the fork button in the top right corner.
2. **Create a Branch**: 
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make Changes**: Implement your feature or fix.
4. **Commit Your Changes**: 
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push to Your Branch**: 
   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Open a Pull Request**: Go to the original repository and click on "New Pull Request".

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries, please reach out to the maintainer:

- **Name**: [Your Name]
- **Email**: your.email@example.com
- **GitHub**: [maharishiayurveda](https://github.com/maharishiayurveda)

For more information about releases, please visit the [Releases section](https://github.com/maharishiayurveda/DocQuify/releases).

![DocQuify Logo](https://via.placeholder.com/600x200.png?text=DocQuify+Logo)

Feel free to explore and enjoy using DocQuify for all your document querying needs!