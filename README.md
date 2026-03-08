## NETFLIX MIRCROSERVICES
##### MAGOOLA ANGELA MUTESI 
##### B28735
##### M24B23/047
#### Mircroservice architecture
Mircroservice architecture is where applications are broken down into smaller independent services that work hand in hand and communicate over APIs.
Each handles a specific domain like user profiles, payments, security and so on.
Microservices allow independent deployment and improvements without hindering the overrall performance.
#### How netflix uses Mircoservices
Netflix is one of the companies that has successfully implemented microservices architecture. Instead of building its platform as one large monolithic application, Netflix divides its system into many small, independent services, each responsible for a specific function. These services communicate with each other using APIs, allowing them to work together to deliver the full platform experience. <br>


Netflix uses a cloud-based microservices architecture on AWS, which lets it scale horizontally and handle millions of users. Its Open Connect CDN delivers videos closer to users for faster streaming. Requests go through Zuul, the API gateway, while Hystrix ensures failures in one service don’t crash the platform. Internal APIs manage authentication, recommendations, catalog, streaming, and billing, keeping the system reliable and flexible.
#### Characteistics of microservices at netflix
Domain driven<br>
Decoupled services<br>
Lightweight communication<br>
Independent deployment<br>
#### Other Companies That Use Microservices
**Amazon** uses microservices to manage its massive e-commerce system. Different services handle tasks such as product search, inventory management, order processing, payment handling, and shipping logistics. Each service operates independently, which allows Amazon to scale individual services and update features without affecting the entire platform.


**Uber** also relies heavily on microservices to operate its ride platform. Separate services handle ride requests, driver matching, location tracking, pricing calculations, and payment processing. Because ride demand changes rapidly throughout the day, Uber can horizontally scale specific services to handle peak traffic.


