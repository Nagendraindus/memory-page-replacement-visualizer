# memory-page-replacement-visualizer
Interactive web app that helps users understand virtual memory management in OS. Simulate and visualize algorithms like FIFO, LRU, and MRU. Ideal for students and educators, it offers customizable parameters, step-by-step explanations, and a user-friendly interface to explore memory management concepts.
## FIFO
![image](https://github.com/user-attachments/assets/d89b890d-027d-48e6-a552-5244f2a4bf54)
##LRU
![image](https://github.com/user-attachments/assets/92386158-e1ca-4fab-8eb1-66c16ecc16e4)
## MRU
![image](https://github.com/user-attachments/assets/a3c7321d-6bad-40ba-9e7a-6523b62d8c4a)




## Virtual Memory Visualizer

Welcome to the **Virtual Memory Visualizer**! This web application helps you understand how virtual memory management works by simulating different page replacement algorithms. 

Whether you're a student learning about operating systems or just curious about how memory management functions, this tool is here to make things clearer.

## Features

- **Page Replacement Algorithms**: Simulate popular algorithms like FIFO (First-In, First-Out), LRU (Least Recently Used), and MRU (Most Recently Used).
- **Interactive Simulation**: Input a sequence of page requests and see how the algorithm handles each request in real time.
- **Customizable Parameters**: Set the number of memory frames and the page sequence to see how different scenarios affect memory management.
- **Detailed Output**: Get step-by-step descriptions of how pages are managed, including page faults, page hits, and the current memory state.

## Getting Started

To get started with the Virtual Memory Visualizer, follow these simple steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Nagendraindus/memory-page-replacement-visualizer.git

   ```

2. **Open the Project**

   Open the `index3.html` file in your preferred web browser.

3. **Enter Your Parameters**

   - **Page Sequence**: Enter a sequence of page requests (e.g., `1,2,3,4,1,2,5`).
   - **Number of Frames**: Specify the number of memory frames.
   - **Choose an Algorithm**: Select from FIFO, LRU, or MRU.

4. **Run the Simulation**

   Click the **Run Simulation** button to see how the selected algorithm processes your page sequence.

5. **View Results**

   The results will be displayed, showing step-by-step details of how pages are managed, including page faults, page hits, and the current memory state.





## Troubleshooting

- **If the scrollbar is not visible**: Ensure that your content exceeds the visible area of the `#result` div, and check the CSS settings for `overflow-y`.
- **If the input fields or buttons aren't working**: Make sure you have included the correct `script3.js` file and that it's properly linked in your `index.html`.



## License

This project is licensed under the Apache License. See the [LICENSE](LICENSE) file for details.

---

