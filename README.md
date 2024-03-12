# Project Proposal: Crop Recommendation AI Device (CRAD)
## 1. Executive Summary
 
Agriculture in Rwanda, despite contributing about 31% to the national GDP and employing about 70% of the population, faces significant challenges in optimizing crop yield. One of the primary challenges is the lack of precise information on suitable crops for specific land and weather conditions. To counter this problem, we propose the introduction of the Crop Recommendation AI Device (CRAD). This AI-powered device is designed to provide crop recommendations based on real-time land parameters and forecasted rainfall. The anticipated impact of this project is a 15-20% improvement in crop yield and optimized agricultural practices in Rwanda over the next five years.
(Rwanda Agriculture Board (2019). Annual Report)
  
## 2. Project Background
 
While Rwanda's agriculture sector is a significant contributor to the economy and livelihoods, it is yet to fully leverage the opportunities presented by technology for precision farming. Over the past decade, research has addressed generic crop recommendation systems, but none has been tailor-made for Rwanda's unique soil and climatic conditions. This gap provides an opportunity for a localized solution like the CRAD, which will be customized to Rwanda's agricultural landscape.
(Rwanda Agriculture Board. (2019). Annual Report,  Rurangwa, E., & Van Ranst, E. (2006). Soil Science of Tropical and Temperate Soils. Land Evaluation. Part II. K.U.Leuven, Belgium.)
  
## 3. Solution
 
Our vision is to revolutionize Rwanda's agriculture through the application of AI. We aim to develop a user-friendly CRAD built on the Raspberry Pi 4 Model B platform within a 24-month project timeline. The key milestones of the project include a six-month system design phase, four months of data collection, six months of software development, four months for testing, and four months for deployment and user training.
  
 
The project team will consist of five data scientists, three hardware engineers, and two UI/UX designers. To mitigate risks, we will conduct regular system backups, rigorous testing, and comprehensive user training. Our main deliverable is the fully functional CRAD device, and we'll use reporting tools such as Jira for effective project management. 
  

## 4. Project Deliverables and Goals
 
Our end product is a user-friendly CRAD capable of recommending suitable crops for Rwandan farmers based on real-time land parameters and forecasted rainfall. Our SMART goals align with delivering a fully functional device that increases crop yield by 20% within the first year of deployment.  
| Deliverable | Timeline |
| --- | --- |
| System Design | 6 months |
| Data Collection | 4 months |
| Software Development | 6 months |
| Testing | 4 months |
| Deployment & User Training | 4 months |

## 5. Resources Needed
 
The estimated project budget stands at $100,000. This sum includes $40,000 for hardware components, $30,000 for software development, $20,000 for testing, and $10,000 for user training. A detailed cost breakdown and resource allocation plan will be provided upon project approval. </br>
<img width="566" alt="image" src="https://github.com/theoneste2060/Crop-Recommendation-AI-Device-CRAD-/assets/101105164/c6d67b93-cc55-42e6-be5b-ee748cc2ffc6">



  
| Resource | Estimated Cost |
| --- | --- |
| Hardware Components | $40,000 |
| Software Development | $30,000 |
| Testing | $20,000 |
| User Training | $10,000 |
| Total | $100,000 |

## 6. Conclusion
 
Our project promises a new dawn for Rwanda's agriculture sector. By addressing the precise information gap on suitable crops for specific land and weather conditions, our solution will optimize agricultural practices in Rwanda, leading to improved crop yield and subsequent economic growth. In the long run, we expect to see a 15-20% increase in crop yield over the next five years, contributing significantly to Rwanda's food security and the livelihoods of its people.
  
--------------------------------------
# Crop-Recommendation-AI-Device-CRAD-Technology details 
--------------------------------------



 
The **Crop Recommendation AI Device (CRAD)**, built on a Raspberry Pi 4 Model B, is a technological marvel designed to **revolutionize precision agriculture**. This device's primary function is to recommend suitable crops based on land criteria and predicted rainfall, making it a vital tool for optimizing agricultural practices.
  
 
The hardware components of the device include the **Raspberry Pi 4 Model B, a 5-in-1 soil sensor, **and** a 5-inch touchscreen**. The sensor communicates with the system via a **MAX485 TTL** to **RS485 module**, and the wiring details are seamlessly orchestrated to connect all the components effectively. An integrated touchscreen provides real-time display of the parameters, enhancing the user interaction with the device.
![image](https://github.com/theoneste2060/Crop-Recommendation-AI-Device-CRAD-/assets/101105164/3e5d4fa5-8100-4d11-a926-27f14ea01eeb)
![image](https://github.com/theoneste2060/Crop-Recommendation-AI-Device-CRAD-/assets/101105164/a51883be-f37c-4518-a514-f48a2abdefbf)
![image](https://github.com/theoneste2060/Crop-Recommendation-AI-Device-CRAD-/assets/101105164/b3e7eec3-2864-42c1-bde1-1e7f6ea800e2)
![image](https://github.com/theoneste2060/Crop-Recommendation-AI-Device-CRAD-/assets/101105164/e36c1ef2-4953-4250-b916-aac63ace34fc)



 
Data management and machine learning are at the heart of this device. The dataset utilized consists of columns for **N, P, K, temperature, humidity, pH, rainfall, and label**. The device employs a **Random Forest Classifie**r for crop recommendations, trained on 2201 records. This use of Artificial Intelligence allows the device to provide highly accurate crop recommendations, tailored to the specific conditions of the land.
![image](https://github.com/theoneste2060/Crop-Recommendation-AI-Device-CRAD-/assets/101105164/41614c8d-f61b-4309-a9ce-0b7dd61d0886)
  
 
The user interface is designed with simplicity and efficiency in mind. The touchscreen interface displays real-time parameters when the sensor is inserted into the soil, and two buttons, '**Predict**' and '**Reset**', provide user control over the system. The 'Predict' button triggers the machine learning model to recommend suitable crops, while the 'Reset' button reloads data and resets the system, ensuring it is ready for the next use.
<img width="646" alt="image" src="https://github.com/theoneste2060/Crop-Recommendation-AI-Device-CRAD-/assets/101105164/f6886f05-84a9-4575-bc43-4ad52279aa93">
  
 
The 5-in-1 soil sensor measures pH, NPK, temperature, humidity, and conductivity, providing comprehensive data for crop recommendation. The milliseconds delay for loading parameters into the system ensures real-time data accuracy, while the user-friendly interface allows users to easily interact with the system.
  
 
In terms of meteorological forecasting, the device integrates a 3-month average of predicted rainfall. This feature enhances the accuracy of the crop recommendations, taking into account expected rainfall in addition to the real-time soil parameters.
  
 
From a user experience perspective, this device offers numerous benefits. It allows users to easily understand and interact with the system and provides crop recommendations based on real-time land parameters and forecasted rainfall. It enables early identification of suitable crops, optimizing agricultural practices, and offers technical insights for users seeking advanced functionality.

  
 
In conclusion, the **Crop Recommendation AI Device (CRAD)** is a sophisticated piece of technology that combines **hardware components, data management, Artificial Intelligence, user interface design, meteorological forecasting, and user experience considerations to provide a comprehensive solution for precision agriculture.**
  
**APPENDIX**
 
- **The N, P, K, temperature, humidity, pH, rainfall, and label** columns in the dataset correspond to different parameters of the soil and weather conditions. N, P, K refer to nitrogen, phosphorus, and potassium levels in the soil, respectively. Temperature and humidity are self-explanatory, pH measures the acidity or alkalinity of the soil, and rainfall refers to the amount of rainfall. The 'label' column contains the crop recommendations based on these parameters.
- **The MAX485 TTL to RS485 module** plays a crucial role in sensor communication. It converts the signal from the sensor into a format that the Raspberry Pi can understand and process. This is critical for the device to read and interpret the soil and weather data correctly.
- **The RandomForestClassifier** is a machine learning model used for providing crop recommendations. It works by creating a 'forest' of decision trees based on the dataset and then outputs the mode of the classes (crop recommendations) of the individual trees. This method allows for more accurate and reliable recommendations.
- The method for **predicting a 3-month average of rainfall** for meteorological forecasting uses historical weather data and statistical models to predict future rainfall. This information is vital for recommending crops that will thrive under the expected weather conditions.
- The **milliseconds delay** in loading parameters into the system is significant as it ensures data accuracy. This brief delay allows the system to process the real-time data from the sensor effectively, ensuring that the crop recommendations are based on the most accurate and up-to-date information.  
