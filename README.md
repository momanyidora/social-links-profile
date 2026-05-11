nd Mentor - Social Links Profile Solution

This is a solution to the Frontend Mentor Social Links Profile Challenge
. These challenges help improve front-end development skills by building realistic projects.

#Table of Contents#
Overview
The Challenge
Links
My Process
Built With
What I Learned
Continued Development
Useful Resources
AI Collaboration
Author
Acknowledgments
Overview
The Challenge

Users should be able to:

View hover and focus states for all interactive elements on the page
Access social media profile links easily
Experience a responsive layout across different screen sizes
Screenshot

Links
Solution URL: GitHub Repository
Live Site URL: Live Demo
My Process
Built With
Semantic HTML5 markup
CSS custom properties
Flexbox
Mobile-first workflow
Responsive design principles
What I Learned

While building this project, I practiced creating responsive card layouts using Flexbox and improved my understanding of hover and focus states for accessibility.

One section I’m proud of is styling interactive buttons consistently:

.social-link {
display: block;
padding: 12px;
border-radius: 8px;
background-color: hsl(0, 0%, 20%);
text-align: center;
transition: background-color 0.3s ease;
}

.social-link:hover,
.social-link:focus {
background-color: hsl(75, 94%, 57%);
color: black;
}

I also learned how to structure a clean and accessible HTML layout.

<main class="profile-card">
  <img src="./assets/images/avatar-jessica.jpeg" alt="Jessica Randall">
  <h1>Jessica Randall</h1>
  <p>London, United Kingdom</p>
</main>
Continued Development

In future projects, I would like to continue improving:

Responsive layouts
Accessibility best practices
CSS positioning and spacing
Writing cleaner and more reusable CSS
Useful Resources
MDN Web Docs
— Helped me understand Flexbox and accessibility concepts.
CSS Tricks Flexbox Guide
— Very useful for learning Flexbox layouts.
Frontend Mentor
— Great platform for practicing real-world front-end projects.

Author
Name - Dorah Whali
Frontend Mentor - @dorah
GitHub - momanyidora
Acknowledgments

Thanks to the Frontend Mentor community for providing beginner-friendly challenges and feedback opportunities. I also appreciate the learning support from AI tools like ChatGPT and Google Gemini
