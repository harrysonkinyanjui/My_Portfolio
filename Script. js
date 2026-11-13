// 1. Dark / Light Mode Toggle
const themeToggle = document.getElementById('theme-toggle');
const body = document.body;

themeToggle.addEventListener('click', () => {
  body.classList.toggle('dark-mode');
  themeToggle.textContent = body.classList.contains('dark-mode') ? '☀️' : '🌙';
});

// 2. Dynamic Footer Year
document.getElementById('year').textContent = new Date().getFullYear();

// 3. Contact Form Submission Handler
const contactForm = document.getElementById('contact-form');
const formStatus = document.getElementById('form-status');

contactForm.addEventListener('submit', (e) => {
  e.preventDefault();
  const name = document.getElementById('name').value.trim();
  
  formStatus.textContent = `Thanks, ${name}! Your message has been received.`;
  contactForm.reset();

  setTimeout(() => {
    formStatus.textContent = '';
  }, 4000);
});
