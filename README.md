# Labeasy

Labeasy is a platform that connects blood collection centers and diagnostic labs with users looking for affordable and accessible tests.  
Designed especially for tier‑2 and tier‑3 labs, Labeasy provides them with an online presence, enables easy price comparisons, and offers unique features like a **Health Dashboard with an H‑Index** to help users and insurance companies understand overall health trends.


## Website
https://labeasy.aadish.tech/

## Features

1. **Lab and Test Listings**: Labs and collection centers can list themselves and add diagnostic tests with prices.
2. **User‑Friendly Interface**: Users can easily browse and compare labs, prices, and available tests to make informed decisions.
3. **Health Dashboard & H‑Index**: Each user gets a health dashboard with a calculated health index (H‑Index) from past reports, useful for users and insurers alike.
4. **Insurance Integration**: Insurance companies can access a user’s health index (with permission) to expedite premium calculations.
5. **Revenue Model**:
   - Sponsored ads for labs.
   - Tiered commissions on lab sales above specific thresholds.
   - Commissions from insurance sales via the platform.

## Tech Stack

- **Frontend**: React with Recoil for state management  
- **Backend**: Express.js  
- **Database**: PostgreSQL with Prisma ORM  
- **UI Library**: Acternity UI for consistent and modern UI components

## Project Structure

- **frontend/**: Contains the frontend code, built with React and Recoil.
- **backend/**: Contains the backend code, built with Express.js and Prisma.
- **LabDetailsPopup Component**: Displays lab listings while maintaining cart functionality.
- **database/**: PostgreSQL database managed with Prisma for seamless integration.

## Pages

### 1. Home

![Home](https://drive.google.com/uc?id=1WDKnWV0erGIwXTbJdiwRmVUHHtfTnb6_)


### 2. Tests

![Tests](https://drive.google.com/uc?id=18LcJXQcHWqEfigVrj7_KZjHcc2FlWPaW)


### 3. Cart

![Cart](https://drive.google.com/uc?id=1576QFBgUUw8uzBbgWL_qzoQ2vI1ld6OA)


### 4. Results

![Results](https://drive.google.com/uc?id=1LZ-Rwc2zBHDAdHtkGjou2vZ-LtOKltl1)


### 5. Labs Dashboard

![Labs Dashboard](https://drive.google.com/uc?id=1xcnURi8frBq85BjJvKGk5FE59aP7gqji)


### 6. SignIn

![SignIn](https://drive.google.com/uc?id=1J5g_VrXPR4wCJZYBxkcfuz6PWKgvMmK6)


### 7. SignUp User

![SignUp User](https://drive.google.com/uc?id=1Zi_DWkE-EbvygPfLL8fX2d7DttJgrYEm)


### 8. SignUp Lab

![SignUp Lab](https://drive.google.com/uc?id=12GE6c5K0lx4axzoWbWXlScjyqY9T-v29)


## Getting Started

### Prerequisites

1. **Node.js** (v14 or higher)
2. **PostgreSQL**
3. **Prisma**
4. **React.js**
5. **Recoil**

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/srishtchauhan/Labeasy
    cd labeasy
    ```

2. **Install dependencies**:

    - Install backend dependencies:
      ```bash
      cd backend
      npm install
      ```

    - Install frontend dependencies:
      ```bash
      cd ../frontend
      npm install
      ```

3. **Setup Database**:
    - Create a PostgreSQL database.
    - Update the `.env` file in the backend with your database credentials.

    ```env
    DATABASE_URL="postgresql://username:password@localhost:5432/labeasy"
    ```

    - Run Prisma migrations:
      ```bash
      cd backend
      npx prisma migrate dev
      ```

4. **Run the Application**:
    - Start the backend server:
      ```bash
      cd backend
      npm start
      ```
    - Start the frontend server:
      ```bash
      cd frontend
      npm run dev
      ```

5. **Access the Application**:
    - Open a browser and go to `http://localhost:3000` for the frontend.

## Usage

1. **User Registration and Login**: Users can sign up, browse labs, and view available tests and prices.
2. **Lab Listing and Test Management**: Labs can list tests and manage their information from the lab dashboard.
3. **Order Tests and Checkout**: Users can add tests to the cart and proceed to checkout with their selected options.
4. **View Health Dashboard**: Users can view their H‑Index based on past reports.
5. **Insurance Integration**: Insurance companies can access user data (with permission) to determine premiums based on health status.
