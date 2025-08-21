# Intelligent e-commerce repos

This project is a curated hub of an intelligent e-commerce application designed to explore the challenges of managing products with limited stock. It showcases solutions to real-world product problems such as product variations, stock management, multiple user roles, profile editing, order processing, and demand forecasting.
The project highlights decision-making around trade-offs in performance, scalability, and user experience, and demonstrates the application of AI for predicting demand trends. Overall, it’s a product-focused exploration of designing and delivering a complex e-commerce system end-to-end.

## Repositories  
- [Frontend Repo](https://github.com/Serban681/PlayPeak_Frontend)
- [Backend Repo](https://github.com/Serban681/PlayPeak_Backend)  
- [Forecasting Model Service](https://github.com/Serban681/PlayPeak_DemandPredictionService)  
- [Data Generation Scripts](https://github.com/Serban681/orders_data_generation)  

## Demo  
- [Demo Video](https://www.youtube.com/watch?v=UuMRdpRne3s)  

## Project Overview 
<details>
  <summary>Architecture:</summary>
  <br>
  <img width="664" height="299" alt="image" src="https://github.com/user-attachments/assets/76f8d333-b6c9-477a-8e4e-4f5a7eceb676" />  
  <br>
  - <b>Interface:</b> React + Tailwind  <br>
  - <b>Intermediate Server:</b> Spring  <br>
  - <b>Demand Forecasting Service:</b>  Flask, PyTorch  <br>
  - <b>Database:</b> PostgreSQL  <br>
</details>

<details>
  <summary>Decision-Making & Trade-offs:</summary>
  <br>
  - <b>Database Optimisation:</b> Reused DB objects for repeated data and used microservices to automatically delete unused data, balancing performance with memory use.  <br>
  - <b>Add-to-cart quantity assurance:</b> Reduced available stock immediately when items were added to cart to prevent overselling and ensure accurate inventory.  <br>
  - <b>Separation of backend services:</b> Split demand prediction service from database services, improving scalability and fault isolation.  <br>
  - <b>Saving generated forecasts:</b> Stored newly generated forecasts in the database before display, enabling future re-visualisation and consistency across sessions.  <br>
</details>

<details>
  <summary>Features:</summary>
  <br>
  - <b>Product Variations</b> – support for multiple versions of the same item (e.g., size, color, model).<br>
  - <b>Product Stock Management</b> – track and update inventory levels to prevent overselling.<br>
  - <b>Multi-role Users</b> – different roles (admin, customer) with role-specific permissions.<br>
  - <b>Profile Editing</b> – allow users to manage and update their account information.<br>
  - <b>Order Creation</b> – browse products, add to cart, and place orders.<br>
  - <b>Demand Forecasting</b> – generate product demand predictions using time series analysis with neural networks.<br>
</details>

<details>
  <summary>Future improvements:</summary>
  <br>
  - <b>Enhance prediction service:</b> Improve the demand forecasting by incorporating additional features and signals. <br>
  - <b>Test on real data:</b> Validate the system with real-world data, either through live deployment or realistic datasets. <br>
  - <b>Add more intelligent services:</b> Introduce new AI-driven functionalities to enhance user experience and decision-making. <br>
  - <b>Develop additional features:</b> Expand the application with more product-focused functionalities based on user needs and feedback. <br>
</details>

