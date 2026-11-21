💄 Makeup Clone Project
A modern e-commerce web app for selling cosmetics and perfumes, inspired by the design and features of popular beauty platforms. The project is built with React and TypeScript to keep it reliable and scalable.

Live demo: https://make-up-clone.vercel.app


🚀 Main features
Product catalog: products are loaded by category through SectionDao.

Interactive cart: the full cart flow, including adding, removing, changing quantity and calculating the total in real time.

Authorization: user login and sign up.

Global UI components:

Modal system: one confirmation window for important actions (placing an order, clearing the cart).

Toast notifications: a queue of quick messages about events (for example, "Product added").

Preloader: branded loading animation when the app starts.

Responsive design: Bootstrap 5 together with custom styles so the site looks good on any device.


🛠 Tech stack
Frontend: React (Hooks, Context API), TypeScript.

Routing: React Router DOM.

UI/UX: Bootstrap 5, Lucide Icons / Bootstrap Icons.

Build tool: Vite.


📂 Project architecture
The project uses a modular architecture (FSD-lite), so each layer of the app has its own clear responsibility:

Entities: separate business entities (User, Product) with their own models and logic.

Features: functional blocks (Cart, Authorization, Modals) that handle specific user scenarios.

Pages: components that build full screens.

Data is handled with the DAO (Data Access Object) pattern. It keeps the logic of working with data sources (localStorage/API) separate from UI components. Global state is managed with React Context API.


📸 Screenshots
<img width="1440" height="812" alt="Screenshot" src="https://github.com/user-attachments/assets/513b1a85-61e9-48bf-8712-49ebcc6b48cf" />
<img width="1440" height="809" alt="Screenshot" src="https://github.com/user-attachments/assets/b8942cf2-ea0e-49ff-a587-e9ce3e6357db" />
<img width="1440" height="812" alt="Screenshot" src="https://github.com/user-attachments/assets/5172837b-eb81-4833-8ce7-6518948d6e68" />
<img width="1437" height="815" alt="Screenshot" src="https://github.com/user-attachments/assets/bfbb30a6-00c6-4809-a2b2-38d80f52dfd2" />
<img width="1440" height="811" alt="Screenshot" src="https://github.com/user-attachments/assets/63fc6f34-eccf-48b8-a371-904834f9e63c" />
<img width="1440" height="812" alt="Screenshot" src="https://github.com/user-attachments/assets/c3706a70-10eb-448c-9930-02529572d0fd" />
<img width="1434" height="808" alt="Screenshot" src="https://github.com/user-attachments/assets/03096015-6e0c-4a32-b13f-2bcf479b6c57" />
<img width="1437" height="809" alt="Screenshot" src="https://github.com/user-attachments/assets/ffd3451e-61b1-40a1-86eb-3b19257eba20" />
<img width="1436" height="814" alt="Screenshot" src="https://github.com/user-attachments/assets/5de19266-b380-4b88-aa36-e7bc90e3978d" />
<img width="1434" height="800" alt="Screenshot" src="https://github.com/user-attachments/assets/065f4648-d3c1-4fc7-acff-e192ffb27cc2" />
<img width="1434" height="800" alt="Screenshot" src="https://github.com/user-attachments/assets/2fa65481-eaf4-46ff-8e9e-4cbc9219b3eb" />
<img width="1440" height="811" alt="Screenshot" src="https://github.com/user-attachments/assets/21756a1b-9e16-4f81-b36c-01e3227b90c2" />


Thanks for checking out this project! If you have any questions or ideas, I will be happy to talk.
