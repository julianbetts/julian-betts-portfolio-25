# Julian Betts - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript to showcase projects, skills, and professional information.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic navigation
- **Contact Form**: Functional contact form with validation
- **Project Showcase**: Dedicated section to display your projects
- **Skills Section**: Visual representation of your technical skills
- **Mobile Navigation**: Hamburger menu for mobile devices

## 📁 File Structure

```
julian-betts-portfolio-25/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # Project documentation
```

## 🎨 Customization Guide

### Personal Information
1. **Update Contact Information**: Edit the contact section in `index.html` with your actual details:
   ```html
   <span>your.email@example.com</span>
   <span>github.com/yourusername</span>
   <span>linkedin.com/in/yourusername</span>
   ```

2. **Modify Bio**: Update the about section with your personal story and background.

3. **Add Projects**: Replace the placeholder project cards with your actual projects:
   ```html
   <div class="project-card">
       <div class="project-image">
           <!-- Add project screenshot or icon -->
       </div>
       <div class="project-content">
           <h3>Your Project Name</h3>
           <p>Project description...</p>
           <div class="project-tech">
               <span class="tech-tag">Technology Used</span>
           </div>
           <div class="project-links">
               <a href="live-demo-url" class="project-link">
                   <i class="fas fa-external-link-alt"></i> Live Demo
               </a>
               <a href="github-url" class="project-link">
                   <i class="fab fa-github"></i> Code
               </a>
           </div>
       </div>
   </div>
   ```

4. **Update Skills**: Modify the skills section to reflect your actual technical skills.

### Styling
- **Colors**: Update the color scheme by modifying CSS variables in `styles.css`
- **Fonts**: Change fonts by updating the Google Fonts link in `index.html`
- **Animations**: Adjust animation timing and effects in `styles.css`

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and animations
- **Font Awesome**: Icons for visual elements
- **Google Fonts**: Inter font family for typography

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🚀 Getting Started

1. **Clone or Download**: Get the project files
2. **Customize**: Update personal information, projects, and styling
3. **Deploy**: Upload to your preferred hosting service (GitHub Pages, Netlify, Vercel, etc.)

## 📧 Contact Form

The contact form includes:
- Name, email, and message fields
- Client-side validation
- Success/error notifications
- Form reset after successful submission

**Note**: The form currently shows a success message but doesn't actually send emails. To make it functional, you'll need to:
- Set up a backend service (Node.js, PHP, etc.)
- Use a form service like Formspree or Netlify Forms
- Configure email sending functionality

## 🎯 SEO Optimization

The website includes:
- Semantic HTML structure
- Meta tags for social sharing
- Responsive design for mobile-first indexing
- Fast loading times with optimized assets

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider sharing them with the community!

---

**Built with ❤️ for showcasing programming skills and projects**