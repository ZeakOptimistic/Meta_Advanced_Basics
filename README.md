# 💼 Personal Portfolio Website

This project is a **single-page personal portfolio website** built as the final lab for the Coursera Meta Advanced React course. It showcases my featured projects, a bio section, contact form, and social media links, using **React**, **Chakra UI**, **Formik**, and **Yup**.

---

## 🚀 Features

### ✅ Header
- Displays social media icons with external links (e.g., GitHub, LinkedIn)
- Internal navigation links to `#projects-section` and `#contactme-section`
- Smooth scrolling on link click
- Bonus: Header hides on scroll down and reappears on scroll up

### ✅ Landing Section
- Avatar image and greeting
- Short bio using Chakra UI `Heading` and `Text`

### ✅ Projects Section
- Featured projects displayed in a responsive grid
- Each project is shown as a Card with:
  - Image
  - Title and description
  - Right arrow icon (FontAwesome)

### ✅ Contact Me Section
- Functional contact form built with:
  - Chakra UI components
  - Formik for form control
  - Yup for validation
  - Custom hook `useSubmit` to simulate API calls
- Validates `firstName`, `email`, `type`, and `comment`
- Displays form errors and submission feedback
- Shows alert on success or failure using `useAlertContext`

---

## 🧰 Libraries Used

| Library        | Purpose                             |
|----------------|-------------------------------------|
| **React**      | Core framework                      |
| **Chakra UI**  | UI components and responsive layout |
| **Formik**     | Form state management               |
| **Yup**        | Form validation                     |
| **FontAwesome**| Icons for social links and arrows   |

---

## 📁 Folder Structure

