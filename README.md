# The Awareness Project

_A calming and accessible platform for mental well-being_

---

## 🖼️ Website Mockup

<div align="center">
  <img src="./Wireframes/website-mockup.png" alt="Website Mockup" width="600"/>
</div>

---

## 🌐 Deployed Site

[https://tbragg88.github.io/Mental-Awareness-Project/](https://tbragg88.github.io/Mental-Awareness-Project/)

---

## 📝 Project Overview

**The Awareness Project** offers beginner-friendly resources in a calming, organized, and accessible format. The site features a clean UI, smooth navigation, and interactive wellness tools to help users manage stress and learn about mental health.

### 🌟 Brief

-   Cohesive one-page layout with semantic HTML and accessible navigation
-   Information organized using UX principles and user-initiated actions with feedback
-   Valid HTML and CSS (W3C/Jigsaw)
-   Responsive design with media queries

---

## 🛠️ Features Considered But Not Included

During development, several features were explored but not included to maintain clarity, accessibility, and a calming user experience:

-   **Image Carousel:**  
    Initially planned for the hero or resource sections to showcase tips and affirmations. Removed as it disrupted the calm, focused flow of the site and could distract users seeking support.

-   **Breathing Animation:**  
    A guided breathing exercise animation was prototyped to help users manage stress. It was omitted to keep the interface simple and avoid overwhelming first-time visitors. This feature may be revisited in future updates.

-   **Live Chat Widget:**  
    Considered for instant support, but excluded to maintain privacy and reduce technical complexity for a static site.

---

## 🌓 Partial Integrations

-   **Dark/Light Mode Toggle Animation:**  
    More elaborate transitions were tested but replaced with a subtle, accessible toggle for a smoother experience.

These decisions were made to ensure the site remains approachable, fast, and easy to navigate for all users.

---

## 🖼️ Screenshots & UI Flow

Initial wireframing

<div align="center">
  <img src="./Wireframes/MHMWF1.png" alt="Mobile Wireframe" width="160"/>
  <img src="./Wireframes/MHTWF1.png" alt="Tablet Wireframe" width="160"/>
  <img src="./Wireframes/MHPCWF1.png" alt="Desktop Wireframe" width="160"/>
</div>

---

## 🎨 Colour Palette

![Colour Palette](./Wireframes/colour-pallet.png)

The color palette was selected for its calming and accessible qualities. Soft blues and neutral tones help create a relaxed atmosphere, while accent colors provide enough contrast for clear readability. The choices aim to support a welcoming and easy-to-use experience for everyone.

---

## 🚀 How AI Was Used

Artificial Intelligence played a crucial role in shaping this project, streamlining development, and improving overall efficiency. Here’s how AI was leveraged:

1. **Code Generation:**  
   AI-powered tools, such as **GitHub Copilot**, provided structured HTML and CSS code snippets, streamlining development. "A manual review ensured code quality. In the end, I mainly used an external Copilot for 'How can I do X?' rather than letting VS Code's internal Copilot indiscriminately shotgun lines."
2. **Debugging & Optimization:**  
   AI debugging tools detected errors and suggested solutions, minimizing bugs and improving stability.
   "The W3C Markup Validation Service was great for identifying issues and bad coding practices. Lighthouse was particularly helpful in assessing accessibility and ensuring sufficient text contrast for an inclusive experience."

3. **AI-Generated Imagery:**  
   **DALL-E** was used to generate all images for the website, ensuring consistency and creativity.
   "This was great from start to finish. As someone with little artistic talent, it provided me with enough guidance to create an aesthetic that flowed nicely."

4. **Content Assistance:**  
   **GitHub Copilot** aided in text refinement, delivering real-time suggestions for blurbs and content. "Again, this is completely true—I wrote nothing on the page. Every paragraph, inspirational message, and aspiration came entirely from the AI, and it was both cohesive and comprehensive."

5. **Accessibility Improvements:**  
   Tools like **Lighthouse** assessed accessibility features and provided recommendations for a user-friendly experience. "Not only was Lighthouse useful, but the built-in Copilot was also effective at formatting and validation. It highlighted best practices for aria-label placement and suggested accessibility improvements. It was very good at that."

    ***

## 🧪 Testing & Validation

### Initial Testing

-   **HTML & CSS Validation:**  
    All pages were validated using the [W3C Markup Validation Service](https://validator.w3.org/) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to ensure standards compliance and accessibility:

    <div align="center">
      <img src="./Wireframes/html-validation.png" alt="HTML Validation Result" width="320"/>
      <img src="./Wireframes/css-validation.png" alt="CSS Validation Result" width="320"/>
    </div>

    _Tip: Images between 300–400px wide are generally clear and readable in most README views. Adjust as needed for your preferred layout._

### Accessibility Checks

[Lighthouse](https://developers.google.com/web/tools/lighthouse) was used to assess accessibility, color contrast, and best practices.

  <div align="center">
    <br/>
    <sub>Mobile Lighthouse Accessibility Report</sub>
    <br/><br/>
    <img src="./Wireframes/mobile-lighthouse.png" alt="Lighthouse Accessibility Report (Mobile)" width="320"/>
    <br/>
    <sub>Desktop Lighthouse Color Contrast Report</sub>
    <br/><br/>
    <img src="./Wireframes/desktop-lighthouse.png" alt="Lighthouse Color Contrast Report (Desktop)" width="320"/>
  </div>

\*\*"Initial testing revealed that the mobile hero image was causing mild lag, which resulted in a lower score. Preloading and resizing the image for mobile screens is recommended.

Accessibility issues in both reports stemmed from contrast problems with the 'greyer' text color."\*\*

 <div align="center">
    <br/>
    <sub>Mobile Lighthouse Accessibility Report (Updated)</sub>
    <br/><br/>
    <img src="./Wireframes/updated-mobile-lighthouse.png" alt="Updated Lighthouse Accessibility Report (Mobile)" width="320"/>
    <br/>
    <sub>Desktop Lighthouse Color Contrast Report (Updated)</sub>
    <br/><br/>
    <img src="./Wireframes/updated-desktop-lighthouse.png" alt="Updated Lighthouse Color Contrast Report (Desktop)" width="320"/>
  </div>

**Performance**
After creating a mobile-sized version of the header and preloading both headers, it was still causing issues with other images and files. So, I've decided this is acceptable until it isn’t.

**Accessibility**
Changing the neutral grays to blacks and darkening a few blues improved my score.

**Best Practices**
This is due to the dark mode toggle and the new burger menu that the AI provided for me. I love it, so you won’t take it from me—it stays.

<div align="center">
  <img src="./Wireframes/burger-moon.png" alt="Burger Menu with Moon Icon" width="120"/>
</div>




-   **Manual Testing:**  
    The site was tested on multiple devices and browsers to verify responsive design and smooth navigation.

---

## 🛠️ Local Development Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/TBragg88/Mental-Awareness-Project
    ```
2. **Open in browser:**
    - **Mac:** `open index.html`
    - **Windows:** `start index.html`

---

## 🌍 Hosting & Deployment

-   **GitHub Pages:**  
    Deploy from the main branch via repository settings.
-   **Alternative:**  
    Netlify or similar static site hosts.

---

## 📜 Attribution & Credits
-   [Bootstrap](https://getbootstrap.com/) for layout  
-   [Font Awesome](https://fontawesome.com/) for icons  
-   [DALL-E](https://openai.com/dall-e) for AI-generated images  
-   [GitHub Copilot](https://github.com/features/copilot) for code and content assistance  
-   [W3C Markup Validation Service](https://validator.w3.org/) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) for code validation  
-   [Lighthouse](https://developers.google.com/web/tools/lighthouse) for accessibility and performance testing  
-   External mental health resources for content accuracy  
