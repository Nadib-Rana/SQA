---

### **Usability Test Case: Library Management System – Book Search Functionality**  
**Test Case ID:** UT_LMS_001  

**Test Case Title:** Usability Testing for Book Search in Library Management System  

#### **Objective:**  
To test the usability of the book search functionality in the Library Management System, ensuring users can quickly and efficiently find books using different search criteria.  

#### **Preconditions:**  
- The user is on the homepage of the Library Management System.  
- The user may or may not be logged in (test for both cases).  
- The system has a collection of books across different categories (fiction, non-fiction, academic, etc.).  
- The search bar is visible and functional.  

---

### **Test Steps and Expected Results**  

| **Step No.** | **Test Step Description** | **Expected Result** |
|-------------|--------------------------|---------------------|
| 1 | Navigate to the Library Management System homepage. | The page should load quickly, and the search bar should be visible. |
| 2 | Click on the search bar and start typing a book title (e.g., *Harry Potter*). | The cursor should appear, and the user should be able to type freely. |
| 3 | Type a book title (e.g., *To Kill a Mockingbird*) in the search bar. | The system should display real-time suggestions based on available books. |
| 4 | Press "Enter" or click the search icon after entering the book title. | A results page should display books matching the search term. |
| 5 | Search for a book using the author’s name (e.g., *J.K. Rowling*). | The system should list all books by the specified author. |
| 6 | Search using keywords or categories (e.g., *Computer Science*). | The system should list relevant books under the searched category. |
| 7 | Enter a misspelled book title (e.g., *Harrry Pottter*). | The system should suggest the correct spelling and show relevant results. |
| 8 | Search for a book that does not exist (e.g., *Unknown Book XYZ*). | The system should display a message: "No results found" and suggest related books. |
| 9 | Apply filters (e.g., filter by year, author, genre). | The results should update based on the selected filters. |
| 10 | Sort results (e.g., by "Newest First" or "Alphabetical Order"). | Books should be displayed in the correct order. |
| 11 | Test the search function on mobile and desktop. | The search results should be responsive and well-formatted on all devices. |
| 12 | Click the "Clear Search" button to reset the search. | The search bar should be cleared, and the default book list should reappear. |

---

### **Expected Results:**  
✅ **Easy Accessibility** – The search bar should be visible and easy to use.  
✅ **Real-Time Suggestions** – As the user types, the system should suggest books dynamically.  
✅ **Relevant Search Results** – The results should match the search query accurately.  
✅ **Error Handling** – The system should correct minor typos and provide suggestions.  
✅ **Filtering & Sorting** – Users should be able to refine search results with filters and sorting options.  
✅ **Mobile-Friendly Design** – The search should work well on both desktop and mobile devices.  
✅ **Clear Search Functionality** – Users should be able to reset their search easily.  

---

### **Postconditions:**  
- The user can search for books efficiently.  
- The system provides relevant results with filtering and sorting options.  
- The system handles typos and invalid searches gracefully.  

### **Metrics to Measure Usability:**  
📌 **Search Success Rate:** Percentage of users who find their desired book.  
📌 **Search Time:** Average time taken to find a book.  
📌 **Error Rate:** Number of incorrect or empty results due to poor usability.  
📌 **User Satisfaction:** Feedback from users about the ease of searching.  

---

### **Test Data:**  

✅ **Valid Search Terms:**  
- "The Great Gatsby"  
- "Stephen King"  
- "Data Structures"  

❌ **Invalid Search Terms:**  
- "XYZABC123" (should return "No results found")  
- "Hrry Ptter" (should suggest "Harry Potter")  

📌 **Filters & Sorting:**  
- Filter by Year: "Books published after 2020"  
- Sort by Author Name (A-Z)  

---

### **Resources Required:**  
📌 Test users (students, librarians)  
📌 Devices for testing (desktop, mobile, tablet)  
📌 Stable internet connection  
📌 A test version of the Library Management System with a sample book database  

---

### **Conclusion:**  
This usability test ensures that users can search for books efficiently using different criteria. By testing usability aspects like accessibility, filters, error handling, and mobile responsiveness, this test case helps improve the overall experience of the Library Management System.  

---
