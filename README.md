Act 1

![Screenshot 2025-05-05 004935](https://github.com/user-attachments/assets/8f71eeb5-6ec0-40e9-9b91-2346561fc81d)


To build the solution, I began by installing Streamlit and creating a basic app structure using st.title, st.header, and st.write to show text. I incorporated user input fields such as st.text_input and st.number_input to gather data, and then displayed real-time output based on the input to make the app interactive and responsive.

Act 2

![Screenshot 2025-05-04 221522](https://github.com/user-attachments/assets/680b6949-1079-49c1-bab2-7eb6698de997)

To achieve this, I utilized st.file_uploader to let users upload a CSV file, which I then loaded using Pandas for easy manipulation. I displayed the data using st.dataframe, included a st.checkbox to optionally view the raw data, and added a st.selectbox for filtering based on a specific column. This setup created an interactive and user-friendly way to explore datasets with a minimum of five columns.

Act 3

![Screenshot 2025-05-04 221341](https://github.com/user-attachments/assets/77356c6f-c00f-4fdb-a2fd-edce7d4e8650)
![Screenshot 2025-05-04 221400](https://github.com/user-attachments/assets/61f6e8d8-88fb-4ba3-a0ae-e9735b19dd14)
![Screenshot 2025-05-04 221413](https://github.com/user-attachments/assets/6c8c4edb-2232-4c70-9b22-6bdbbe9e41ef)
![Screenshot 2025-05-04 221429](https://github.com/user-attachments/assets/576f4d50-8208-42df-8527-7519d0ed9005)

To address this issue, I organized the Streamlit app using st.sidebar for filters and user options, creating a cleaner and more interactive layout. I employed st.columns and st.expander to structure and toggle detailed content about Data Warehousing and Enterprise Data Management, ensuring the information was well-organized and easy to access. This approach made complex topics more user-friendly and visually appealing.

Act 4

![Screenshot 2025-05-04 221111](https://github.com/user-attachments/assets/befa6ede-a7ea-411a-a949-2d663af22c77)
![Screenshot 2025-05-04 221215](https://github.com/user-attachments/assets/5fb6534d-924a-414b-bf6e-ce4e3d7be4ce)
![Screenshot 2025-05-04 221200](https://github.com/user-attachments/assets/e676366c-a1f1-44db-947c-254c57ffb692)

To address the problem, I chose the Meteo Weather API for its accessible and detailed weather data in JSON format. Using the requests library, I fetched the data and parsed it to extract key metrics like temperature, humidity, and wind speed. With Streamlit, I displayed the results through widgets and created five different chart types to visually present the weather trends and comparisons.

Act 5

![Screenshot 2025-05-04 220900](https://github.com/user-attachments/assets/ab30b4fc-186e-49b2-ae33-cf9d1c10c537)
![Screenshot 2025-05-04 220919](https://github.com/user-attachments/assets/ef102454-03bb-4de9-9a40-68887be26781)

To complete the task, I used SQLAlchemy to connect Streamlit with the MySQL database, enabling secure and efficient data interaction. I wrote SQL queries to retrieve and filter records, displayed the results with st.dataframe, and used Streamlit forms to insert new rows. Additionally, I implemented a basic user authentication system to manage access to database operations.

Act 6

![Screenshot 2025-05-05 003417](https://github.com/user-attachments/assets/31ad930b-1f3c-45db-8e0e-29c674153b6f)

To achieve the objective, I used OpenCV's cv2.VideoCapture to access the webcam and read video frames in real-time. I incorporated Streamlit sliders to dynamically adjust filter thresholds (like GrayScale) and displayed the processed frames using st.image. Additionally, I implemented a snapshot feature to capture and save the current frame on demand.













