<template>
  <main class="main-content">
    <section id="work-experience" class="content-section">
      <h2>WORK EXPERIENCE</h2>
      <div v-html="workExperience"/>
    </section>
    <section id="skills" class="content-section">
      <h2>ADDITIONAL SKILLS</h2>
      <div class="additional-skills">
        <p>Frontend engineer with a proactive progression from WordPress development to modern JavaScript frameworks, specialising in Vue.js ecosystems and large-scale SaaS applications. Passionate about modern component-driven architecture and test-driven development.</p>
      </div>
    </section>
    <section id="education" class="content-section">
      <h2>EDUCATION & TRAINING</h2>
      <div v-html="education"/>
    </section>
    <section id="additional" class="content-section">
      <h2>ADDITIONAL EXPERIENCE</h2>
      <div v-html="additionalExperience"/>
    </section>
  </main>
</template>

<script setup>
const workExperience = `
  <strong>FRONT-END ENGINEER</strong> <br/>CAVU | 2024 - Present <br/><a href="https://ca.vu" target="_blank">ca.vu</a>
  <ul>
    <li>Responsible for public-facing post-purchase customer journey within large nx monorepo whitelabel saas.</li>
    <li>Maintains and upgrades our codebase for security and cutting-edge functionality within our UI components.</li>
    <li>Leads on technical refinement session for future features.</li>
    <li>Takes initiative on EAA (Accessibility adherence) and improving our codebase through UI CoP.</li>
    <li>Test-driven development and deployment via cloud infrastructure.</li>
    <li>Eye for detail in front end development implementations.</li>
    <li><strong>Skills:</strong> Vue.js, Pinia State, Composition API, Typescript/JS, Tailwindcss, Eslint, Unit testing, DevOps, Terraform, Auth0, CI/CD, AWS, Cloud Infrastructure, Datadog, Postman, REST APIs, Bitbucket, Jira, Agile.</li>
  </ul>
  <strong>FRONT-END SHOPIFY SPECIALIST</strong> <br/>Squashed Pixel | 2023 <br/><a href="https://squashedpixel.co.uk" target="_blank">squashedpixel.co.uk</a>
  <ul>
    <li>Enhanced and documented our Shopify base UI theme library for improved performance and scalability for future projects.</li>
    <li>Transformed client needs into customised solutions using LIQUID and latest frontend dependencies.</li>
    <li>Adeptness in cross-browser responsive development (HTML5, ES6+, CSS3+, SCSS).</li>
    <li>Utilised Lighthouse, Google Search Console (GSC), and Web Vitals to offer insightful feedback on areas for improvement.</li>
    <li>Experienced in agile methodologies (Scrum, Trello, Jira) for project management.</li>
    <li>Applied creative problem-solving to address clients' queries effectively.</li>
    <li>Utilised Shopify CLI 2.0+, JSON Templates & ThemeKit for streamlined development.</li>
    <li><strong>Skills:</strong> Liquid, HTML, SCSS, Tailwindcss, ES6+, Vite.js, Node.js, NPM, Git, Trello, and Jira.</li>
  </ul>
  <strong>FRONT-END SHOPIFY DEVELOPER</strong> <br/>Underexposed | 2022 - 2023 <br/><a href="https://uxcreature.co" target="_blank">uxcreature.co</a>
  <ul>
    <li>Ownership of code, PR reviews and scoping our new dependencies for clients requirements.</li>
    <li>Built highly tailored and customisable Shopify website themes.</li>
    <li>Lead a ground-breaking animal metrics full-stack app for farmers.</li>
    <li>Mobile-first approach to development.</li>
    <li><strong>Skills:</strong> Liquid, HTML, Tailwindcss, JS, Alpine.js, Webpack/Vitejs, Node.js, NPM, GitHub, Asana.</li>
  </ul>
  <strong>WEB DEVELOPMENT MENTOR</strong> <br/>Openclassrooms | 2022 - 2023 <br/><a href="https://openclassrooms.com" target="_blank">openclassrooms.com</a>
  <ul>
    <li>Guided aspiring full-stack developers through hands-on, project-based learning in weekly one-on-one sessions.</li>
    <li>Provided technical support, mentorship, and feedback to help students master front-end and back-end concepts, strengthen problem-solving skills, and deliver professional-grade projects.</li>
  </ul>
  <strong>FRONT-END WORDPRESS SPECIALIST</strong> <br/>Blaze Media | 2021 - 2022 <br/><a href="https://blazemedia.co.uk" target="_blank">blazemedia.co.uk</a>
  <ul>
    <li>Frontend Web Developer for a digital marketing agency based in Liverpool, UK.</li>
    <li>Custom theme development within WordPress CMS for fitness, high-street and dentist companies.</li>
    <li>Mobile-first approach to development.</li>
    <li>Lead on live-streaming fitness Progressive web app</li>
    <li><strong>Skills:</strong> HTML, CSS, Bootstrap, Javascript, jQuery, PHP, Gulp/Webpack, NPM, GitHub, Asana.</li>
  </ul>
  <strong>FRONT-END WORDPRESS SPECIALIST</strong> <br/>Pure Organic Golf | 2021 <br/><a href="https://pureorganicgolf.com" target="_blank">pureorganicgolf.com</a>
  <ul>
    <li>In-house Web Developer to maintain, update & implement UI functionality, product marketing content and lead the e-commerce shop.</li>
    <li>WordPress CMS, customise theme development, Woocommerce integration and custom page styling & functionality with CSS & JS.</li>
    <li>Illustrator, Photoshop & Canva for page mock-ups & product merchandise designs to improve the presentation of marketing content.</li>
    <li>SEO analysis to increase web traffic & new content strategies.</li>
    <li>On-page SEO improvements with Yoast plugin and lead the off-page SEO strategies to build organic traffic.</li>
    <li><strong>Skills:</strong> HTML, CSS, Javascript, jQuery, WordPress, PHP, SEO, Lighthouse.</li>
  </ul>
  <strong>FRONT-END WORDPRESS SPECIALIST</strong> <br/>Pure Organic CBD | 2021 <br/><a href="https://pureorganiccbd.com" target="_blank">pureorganiccbd.com</a>
  <ul>
    <li>Involved in maintaining content aesthetics, building custom e-commerce pages, and improving organic search traffic with latest SEO strategies.</li>
    <li>Employed Google SEO standards (Yoast Premium plugin) and devised content SEO strategies to increase online sales.</li>
    <li>In-charge of the overall upkeep of the e-commerce store, on-hand for error handling, bug detection, plugin management & AWS maintenance.</li>
    <li>Web graphics, product mock-up designs and merchandise branding.</li>
    <li>I was most impressed by the results from targeted pop-ups. Offering product discounts and capturing emails was very successful.</li>
    <li>I am most proud of the terpene pro cards I designed and built for the product pages.</li>
    <li><strong>Skills:</strong> HTML, CSS, Javascript, jQuery, WordPress, PHP, SEO, Lighthouse.</li>
  </ul>
`;

const education = `
  <strong>VUE DEVELOPER COURSE</strong> <br/>Udemy - 2023
  <p>Complete Vue js developer course on Udemy, Self study with practical applications of building frontend and fullstack web apps. Using Pinia, Routing, Directives, Functions and Vitest for testing.</p>
  <strong>LEEDS BECKETT UNIVERSITY</strong> <br/>Bachelor of Science - Computing - 2011 - 2015
  <p>
    Covered all areas of computing, from hardware & network security; computer forensics; website & software development and MySQL Oracle database development.<br/>
    My Final project involved me designing and building an <b>Android-Java mobile app</b> that would track the mobile location whilst skateboarding, show your route on a map as well as displaying speed stats and distance travelled.<br/>
    <b>1-year work placement</b> at a Java software company, Rental Result Group Ltd, as an Android App Developer Intern. Collaborated with the team using GitHub to help bring prototype apps into a working condition.
  </p>
  <strong>DANYADARA CENTRE, SURYALILA</strong> <br/>Permaculture Design Course Diploma - 2018
  <p>The course consisted of theory classes coupled with practical applications of the 12-principle of permaculture. I also helped to build an eco-earth house.</p>
`;

const additionalExperience = `
  <strong>STUDY CHINA PROGRAMME</strong>
  <p>Visited Solar energy manufacturers, dinner with local families, climbed Mount Tai (1545 meters high), introduced to Mandarin Chinese.</p>
  <strong>CAMP COUNSELLOR, CAMP AMERICA</strong>
  <p>Over the summer I worked for Camp America in Pennsylvania assisting with the organisation of campers and guiding them in their daily activities. My main role was to work with the magician teaching illusions and close-up card tricks.</p>
  <strong>CHARITY FUNDRAISING</strong>
  <p>Over the years, I’ve been actively involved in fundraising initiatives, both as a participant and organiser. From charity walks to coordinating skydives, I enjoy creating experiences that bring colleagues together, support meaningful causes, and make a lasting positive impact beyond the workplace.</p>
`;
</script>

<style scoped>
.main-content {
  flex: 1;
  background: #f7f7f5;
  padding: 48px 54px;
  min-height: 100vh;
  overflow-x: auto;
}
.content-section {
  margin-bottom: 48px;
}
.content-section h2 {
  font-size: 1.4rem;
  font-weight: 700;
  color: #232323;
  border-bottom: 2px solid #ffd700;
  margin-bottom: 22px;
  padding-bottom: 4px;
  letter-spacing: 0.5px;
}
strong {
  color: #232323;
  font-weight: 600;
  display: block;
  margin-bottom: 2px;
  font-size: 1.09rem;
}
a {
  color: #2369a5;
  text-decoration: underline;
}
ul {
  margin: 10px 0 26px 18px;
  padding: 0;
}
li {
  margin-bottom: 8px;
  color: #232323;
  font-size: 1rem;
}
.additional-skills p {
  color: #444;
  font-size: 1.05rem;
  margin-bottom: 12px;
}
</style>
