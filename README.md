# AI Clawbot

## Project Overview
AI Clawbot is an advanced artificial intelligence-driven solution designed to automate the claw machine experience. The project utilizes cutting-edge technology to enhance user interaction and optimize gameplay.

## Features
- **Intelligent Gameplay**: Uses machine learning algorithms to improve success rates.
- **User-Friendly Interface**: Easy-to-navigate interface for users and administrators.
- **Multi-Platform Support**: Accessible on both web and mobile devices.
- **Real-Time Analytics**: Provides insights into player behaviors and game performance.

## Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js with Express
- **Database**: MongoDB
- **Machine Learning**: TensorFlow
- **Cloud Provider**: Google Cloud

## Installation Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/lojistiksektoru/ai-clawbot.git
   cd ai-clawbot
   ```
2. **Install Dependencies**:
   ```bash
   npm install
   ```
3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and set your configuration values.

## Deployment Guide for Google Cloud Free Tier
1. **Create a Google Cloud Account**: Sign up at [Google Cloud](https://cloud.google.com/).
2. **Set Up Project**:
   - Go to the Google Cloud Console.
   - Create a new project.
3. **Enable Cloud Services**:
   - Enable the Google App Engine and Google Cloud Functions APIs.
4. **Deploy Application**:
   ```bash
   gcloud app deploy
   ```
5. **Domain Setup for lojistiksektoru.com**:
   - Purchase your domain from a registrar.
   - Go to the Cloud DNS section in the Google Cloud Console.
   - Create a managed zone and configure DNS records pointing to your App Engine service.

## Usage Examples
- **Starting the Application**:
   ```bash
   npm start
   ```
- **Accessing the Web Application**:
   Open your browser and navigate to `http://localhost:3000`.

- **Playing the Game**:
   Follow the on-screen instructions to start playing the claw machine game!  

For detailed information, refer to the documentation in the repository.