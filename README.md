# MApp-TIME: Monitoring App Issues for Maintenance and Evolution

## Overview

Analyzing user feedback from app stores through opinion mining supports software engineering activities, focusing on maintenance and evolution. This approach detects emerging issues promptly and aids in ongoing software development. Given the impracticality of manual analysis due to vast textual data, automation via machine learning methods is essential. However, current methods lack real-time mechanisms for trend detection and risk classification of emerging issues.

This repository presents the **MApp-TIME** approach, designed to address these challenges. It employs a two-fold strategy: (i) identifying app issues and (ii) monitoring their evolution in real-time using temporal dynamic modeling with time series, release dates, alerts, and notifications.

## Key Features

- **Issue Detection and Monitoring**: MApp-TIME leverages temporal dynamic modeling to detect and monitor emerging app issues in real-time. This helps in reducing the time between issue detection and resolution, thereby improving software maintenance and evolution.
  
- **Microservices Architecture**: The approach is implemented using a microservices architecture, which includes **M-iDetect** (Microservice - issue Detector) and **M-iDynamic** (Microservice - issue Dynamic). This architecture offers improved scalability, modularity, and ease of maintenance, allowing for more efficient processing and integration of issue detection functionalities within diverse and complex systems.
  
- **Insights from User Reviews**: Analysis of 13 million reviews across 20 domains provided insights crucial for early detection and prioritization of issues. This proactive approach significantly mitigates their impact on app quality and user satisfaction.

## Contributions

Our contributions include:

- **Temporal Dynamic Modeling**: Introducing a method for modeling the temporal dynamics of app issues and releases using time series analysis. This method detects abrupt changes in issue frequencies, aiding in timely interventions.
  
- **Microservices Architecture**: Designing a scalable architecture that supports real-time issue monitoring and management, enhancing overall software maintenance practices.
  
- **Dataset Availability**: Providing access to the dataset of 13 million reviews across diverse app domains, facilitating further research and development in app issue management.

## Experimental Package

- [Issue Embeddings Model](http://200.129.210.70/experimental-package/issue_embeddings.model)
- [Issue Network Model](http://200.129.210.70/experimental-package/issue_network.model)
- [Issues](http://200.129.210.70/experimental-package/issues.model)
- [M-iDetect](http://200.129.210.70/experimental-package/m-idetect.model)
- [M-iDynamic](http://200.129.210.70/experimental-package/m-idynamic.model)
- [Dataset](http://200.129.210.70/experimental-package/dataset.zip)



## Conclusion

MApp-TIME represents a significant advancement in app issue detection and management, leveraging real-time analysis of user feedback to enhance software maintenance and evolution practices. This approach not only improves developer responsiveness but also contributes to higher app quality and user satisfaction in competitive app store environments.

For detailed implementation and findings, refer to our [paper](available after the reviewing process), where we delve deeper into the methodology and results of our approach.
