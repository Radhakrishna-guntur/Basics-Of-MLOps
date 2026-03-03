# Model Serving

This guide covers model deployment and serving in machine learning applications, focusing on integration, microservices architecture, and collaboration between engineers.

Here we explore how a machine learning (ML) model is integrated into an application once it’s ready for production. Previously, we discussed how data scientists build models and collaborate with product managers and MLOps engineers to iterate during the development and experimentation phases. Now, we move on to integrating the ready model, a request often initiated by the product manager, and executed with precision by the MLOps engineer.

Consider the following real-world scenario: A pharmacy uses an inventory application managed by a pharmacist. When inventory is needed, the pharmacist submits a request through the app. The request travels to a warehouse where an inventory prediction dashboard analyzes historical data and predicts future inventory needs. Based on these predictions, the warehouse dispatches the required items to the pharmacy. This process not only ensures timely inventory management but also opens avenues for additional operational improvements.

Accurate product demand forecasting helps optimize inventory levels and improve warehouse efficiency. Automated scheduling can further streamline these operations.

**How the Inventory Prediction Dashboard Works**

Within our inventory prediction dashboard, users select a branch and a month before clicking the green “Go” button. This action triggers a call from the frontend to a dedicated API endpoint—/predict—which hosts our ML model configured for inventory prediction. For instance, the dashboard might predict that a pharmacy at Dubai Mall in December 2025 will require four units of a specific medicine.

This prediction adds value in two distinct ways:

**1. It supports proactive inventory planning by allowing purchase orders to be placed well in advance.**
**2. It enhances cost efficiency through reliable forecasts, paving the way for better vendor negotiations.**


## Transitioning to a Microservices Architecture

Once the ML model is ready, integrating it into an API shifts the deployment strategy towards a microservices architecture. The /predict endpoint is deployed as a microservice with the following core properties:

          Independent deployability /
          Scalability /
          Fault tolerance /
          Dedicated CI/CD process /
          Loose coupling (single responsibility—inventory prediction) /
          Comprehensive monitoring and logging

These aspects align with core DevOps principles, demonstrating the synergy between MLOps and DevOps practices.


## High-Level Deployment Process

Follow these high-level steps for successful model deployment and serving:

         1.Ensure the ML model is production-ready.
          
         2.Identify the source API calling the serving API, typically the frontend endpoint.
          
         3.Deploy the ML model as a microservice accessible via the /predict endpoint.




## Operational Workflow and Team Collaboration
In an operational context, the MLOps engineer queries, “Which backend service will call the ML model API?” The frontend engineer responds that their API is responsible for calling the /predict endpoint, passing two parameters: branch name and date. The endpoint then uses these inputs to generate an inventory prediction



## The complete deployment process unfolds as follows:

       1. Deploy the API in a staging environment.
       2. Frontend engineers update their code to call the /predict endpoint.
       3. Conduct staging tests.
       4. Transition to production by initially routing 10% of frontend traffic to the /predict endpoint.
       5. Monitor the service and infrastructure.
       6. Upon validation, route 100% of traffic through the /predict endpoint.
       
Jointly agreeing on API parameters and communication protocols is essential for a smooth deployment process.


## Visualizing the Deployment Lifecycle

          1.The entire process can be visualized as a lifecycle encompassing:
          2.Engineering alignment
          3.API parameter agreements
          4.Staging deployments with thorough testing
          5.Production deployments with incremental traffic routing
          6.Continuous monitoring and fine-tuning for scalability

          
## Summary

This guide has outlined how a simple ML model (e.g., stored in a pickle file) is transformed into a production-ready deployment within a microservices architecture. We demonstrated the roles of DevOps and MLOps engineers and underscored the importance of collaboration and adherence to microservices principles.
