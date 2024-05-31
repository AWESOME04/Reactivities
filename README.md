# Reactivities

This repository is dedicated to building a social media app with clean architecture using the following technologies:

- .NET 8.0
- React 18 (with TypeScript)
- Semantic UI
- MobX

## Table of Contents

- [Introduction](#introduction)
- [Technologies](#technologies)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

Reactivities is a modern social media application designed to showcase clean architecture principles. It leverages the power of .NET 8.0 on the backend, React 18 with TypeScript on the frontend, styled with Semantic UI, and state management using MobX.

## Technologies

- **Backend**: .NET 8.0
- **Frontend**: React 18 with TypeScript
- **Styling**: Semantic UI
- **State Management**: MobX

## Features

- User Authentication and Authorization
- Real-time Notifications
- Post Creation and Management
- Commenting System
- User Profiles and Timelines
- Responsive Design

## Installation

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Node.js and npm](https://nodejs.org/)
- [Git](https://git-scm.com/)

### Steps

1. Clone the repository:

   ```sh
   git clone https://github.com/AWESOME04/Reactivities.git
   cd Reactivities
   ```

2. Set up the backend:

   ```sh
   cd API
   dotnet restore
   dotnet build
   dotnet ef database update
   dotnet run
   ```

3. Set up the frontend:

   ```sh
   cd ../client-app
   npm install
   npm start
   ```

## Usage

1. Navigate to `http://localhost:3000` in your web browser to access the React frontend.
2. The backend API will be running on `http://localhost:5000`.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests with your changes. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -m 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

