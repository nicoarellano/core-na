# 🌎 CDT

CDT is a web-based, non-proprietary platform designed for the visualization and interaction of multi-scale geospatial information systems (GIS), open data, open building information modelling (BIM), and a wide range of other digital media, including text, images, animated and static 3D models, IFCs, and point clouds.

The platform is built with full-stack web development frameworks, using React.js for the user interface, state management, and memory optimization, and Next.js for file organization, routing, and server-side rendering (SSR). It integrates multiple open-source packages to support maps and 3D models: Maplibre as the web map renderer and Martin as the PostGIS vector tile server for GIS data, Three.js for 3D graphics, and Web-IFC from That Open Company for native browser-based IFC parsing, with IDS and BCF integration. Point cloud streaming and visualization are supported through Cloud Optimized Point Clouds (COPC), handled by the Potree and Giro3D libraries.

The backend is powered by PostgreSQL, with MinIO providing object storage for binary files such as IFC models and point clouds. All services are hosted on Canadian-based Fullhost infrastructure to ensure data sovereignty.

CDT efficiently incorporates multi-scale open data (federal, provincial, municipal), which is fetched directly from organizational APIs without requiring local data storage. Rather than functioning as a system of record, it serves as a framework and infrastructure for referencing and linking distributed data sources.

Finally, CDT includes a robust authentication system that allows users to form groups, assume different roles and credentials for controlled data and feature access, collaborate effectively, and contribute diverse types of digital media, both publicly and privately.

# 🧭 Mission

This platform bridges BIM and GIS using open standards and free and open-source technologies, enabling stakeholders to visualize and analyze data directly in the browser, thereby eliminating proprietary barriers.
The platform is being stewarded by a not-for-profit, <a href="www.collabdt.org">Collab Digital Twins</a>, established to promote openness, innovation, and long-term public benefit. Our mission is to democratize digital twin technologies. 

# 🚀 Beta access

 to participate in the beta, please complete this short <a href="https://docs.google.com/forms/d/e/1FAIpQLScB12Qc7khiOk4a_E753jDccx6026AjO-_FINBKoZZZtkmqnA/viewform" target="_blank" rel="noopener">beta access form</a>. We will review submissions and contact you with onboarding details.
