Sales Dashboard Application
This project is a single-file web application demonstrating a sales dashboard with chart visualization. It is built to simulate a Next.js environment using React, leveraging Tailwind CSS for styling and Recharts for data visualization.

Key Features
Mock Data Visualization: Displays sales data for 2022, 2023, and 2024.

Multiple Chart Types: Users can switch between Bar, Line, and Pie charts to view the data differently.

Custom Filtering: An input field allows users to set a minimum sales threshold to filter the displayed data.

Project Structure (Simulated for this Example)
This code is provided as a single, self-contained file (Dashboard.jsx). In a real-world Next.js project, the structure would be more organized, following the atomic design principles you mentioned. It would typically look like this:

/app
├── page.jsx           // The main dashboard page
├── components
│   ├── SalesChart.jsx  // Reusable chart component
│   └── ChartControls.jsx // Buttons and filter input

Setup and Running the Project
To use this code in a Next.js project:

Create a new Next.js project:

npx create-next-app@latest my-dashboard --typescript --tailwind --eslint

Install Recharts:

npm install recharts

Copy the code:
Open the app/page.tsx file (or pages/index.tsx depending on your version) in your new project.
Replace the entire content of that file with the code from the Dashboard.jsx file provided.

Run the application:

npm run dev

Your application will be available at http://localhost:3000.

Further Enhancements
This project serves as a foundational example. For further development, you could consider the following:

API Integration: Instead of using mockSalesData, you can fetch real data from an external API endpoint.

More Chart Options: Add more chart types like area charts or scatter plots using the Recharts library.

Advanced Filtering: Implement more complex filters, such as filtering by date range or product category.

State Management: For a larger application, consider using a state management library like Zustand or Redux to handle global state more effectively.
