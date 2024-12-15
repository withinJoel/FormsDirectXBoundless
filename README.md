# FormsDirectXBoundless

## About
This document consolidates suggestions derived from research conducted between November 11, 2024, and December 12, 2024.

---

## Product Improvements

### 1. Adopt Material UI
Material UI has gained significant traction, particularly following the release of Android 12. Its modern design principles align with user expectations, enhancing user engagement and experience.
![image](https://github.com/user-attachments/assets/f6534e51-10f6-4432-9feb-cf053a051a5c)

### 2. Simplify Data Eligibility Forms
Introduce a user-friendly interface to streamline the process of gathering eligible data, ensuring clarity and ease of use.
![image](https://github.com/user-attachments/assets/d5f063cf-ac58-40b8-b6cd-42b538ba4717)

### 3. Recommendation System
Develop a feature to recommend applications based on users' current eligibility criteria, similar to the functionality of Boundless Explore ([Boundless Explore](https://explore.boundless.com/)).
![image](https://github.com/user-attachments/assets/349974df-eb53-4b53-88f9-bf20de4a4db7)

### 4. Risk Indicator
Incorporate a risk indicator to enhance transparency and build trust with users by providing clear insights into potential challenges.
![image](https://github.com/user-attachments/assets/8faa24b8-245c-4412-9b6e-e4b694cae709)

### 5. Comprehensive Risk Analysis
Expand risk assessment features to provide users with a holistic analysis of their circumstances.

### 6. Persistent Header Visibility
Ensure the site header remains visible even when users scroll down, as its absence could reduce indirect brand marketing opportunities.
![image](https://github.com/user-attachments/assets/301cd668-e225-43d0-a3cf-99c27855c422)

### 7. News Page for Immigration Updates
Create a dedicated page for news and updates related to immigration, keeping users informed of relevant current events.
![image](https://github.com/user-attachments/assets/9b300ca7-439a-4a0d-b2fc-0863ff657789)

### 8. Consistent UI Design
Harmonize the user interface across all pages. For example, the design disparity between these two pages detracts from the user experience:
- [Green Card Guide](https://www.immigrationdirect.com/green-card-guide/)
- [Home Page](https://www.immigrationdirect.com/)

---

## Brand Value

### 9. Negative Reviews from Multiple Sources
A comparative analysis of review scores highlights areas for improvement:
- [FileRight Reviews](https://www.reviews.io/company-reviews/store/fileright-com): 2.0
- [Glassdoor - FileRight](https://www.glassdoor.co.in/Reviews/FileRight-Reviews-E1091389.htm): 2.1  
  vs.  
  [Glassdoor - Boundless](https://www.glassdoor.co.in/Overview/Working-at-Boundless-Immigration-EI_IE2018938.11,32.htm): 2.5
- [Trustpilot - FileRight](https://www.trustpilot.com/review/www.fileright.com): 2.8  
  vs.  
  [Trustpilot - Boundless](https://www.trustpilot.com/review/boundless.com): 4.8

---

## Uncategorized

### 10. Head Tag Observations
While examining the head tags on this page:  
[Petition for Alien Relative (I-130)](https://www.immigrationdirect.com/petition-for-alien-relative-i130-preparation-service/),  
I noticed the following:
```html
<meta name="twitter:site" content="@ashwanth">
<meta name="twitter:creator" content="@ashwanth">
```

### 11. Footer link not accessible
In the footer section the facebook link does not work.
- [File Right](https://www.fileright.com/)
![Uploading image.png…]()

### 12. The Visa Suggestion Box is buggy interms of UI
The drop box is shows on top of the header.
Solution: Reduce the `z-index`.
- [ImmigrationDirect](https://www.immigrationdirect.com/)

![image](https://github.com/user-attachments/assets/ce0a8a41-a3fa-4c84-acd9-3cf9482d30ea)
