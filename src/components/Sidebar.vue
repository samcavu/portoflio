<template>
  <aside class="sidebar">
    <div class="sidebar-header">
      <img src="../assets/logo-placeholder.svg" alt="Logo" class="logo" />
      <h1 class="name">SAM BRUTON</h1>
      <h2 class="title">Frontend Engineer</h2>
      <div class="contact">
        <div>+44 7581 779 207</div>
        <div>samwbru@gmail.com</div>
        <a href="https://linkedin.com/in/sam-bruton" target="_blank">linkedin.com/in/sam-bruton</a>
        <a href="https://thefrontendist.com/" target="_blank">thefrontendist.com</a>
        <a href="https://github.com/sambuxc" target="_blank">github.com/sambuxc</a>
      </div>
    </div>
    <nav class="sidebar-nav">
      <ul>
        <li><a href="#work-experience" @click.prevent="scrollTo('work-experience')">Work Experience</a></li>
        <li><a href="#skills" @click.prevent="scrollTo('skills')">Additional Skills</a></li>
        <li><a href="#education" @click.prevent="scrollTo('education')">Education & Training</a></li>
        <li><a href="#additional" @click.prevent="scrollTo('additional')">Additional Experience</a></li>
      </ul>
    </nav>
    <section class="sidebar-section" id="skills">
      <h3>&lt;code&gt;</h3>
      <p>
        Vue, Javascript, Typescript, Css/Tailwindcss, HTML5, Accessibility, TDD, Terraform, REST APIs, Node, Postman, Terraform
      </p>
      <h3>&lt;env&gt;</h3>
      <p>
        NX Monorepo, Auth0, AWS, Cloud-infrastructure, Git, Jira, Slack, Vscode, CI/CD, MacOS
      </p>
      <h3>&lt;self&gt;</h3>
      <p>
        Self-organised, Adaptable, Responsible, Proactive, Pair-programming, Reliable, Eye for detail, Mentoring, Agile
      </p>
    </section>
  </aside>
</template>

<script setup>
function scrollTo(anchor) {
  const el = document.getElementById(anchor);
  if (el) {
    el.scrollIntoView({ behavior: 'smooth' });
  }
}
</script>

<style scoped>
.sidebar {
  background: #232323;
  color: #fff8e1;
  width: 340px;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  padding: 36px 28px;
  box-sizing: border-box;
}
.logo {
  width: 72px;
  margin-bottom: 24px;
  opacity: 0.65;
}
.name {
  font-size: 2rem;
  font-weight: 600;
  margin-bottom: 8px;
  letter-spacing: 1px;
}
.title {
  font-size: 1.1rem;
  font-weight: 500;
  margin-bottom: 24px;
  color: #ffd700;
}
.contact {
  font-size: 0.95rem;
  margin-bottom: 28px;
  line-height: 1.6;
}
.contact a {
  color: #ffd700;
  text-decoration: none;
  display: block;
}
.sidebar-nav ul {
  list-style: none;
  padding: 0;
  margin-bottom: 24px;
}
.sidebar-nav li {
  margin-bottom: 8px;
}
.sidebar-nav a {
  color: #fff8e1;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s;
}
.sidebar-nav a:hover {
  color: #ffd700;
}
.sidebar-section {
  margin-top: 22px;
  font-size: 0.97rem;
}
.sidebar-section h3 {
  margin: 16px 0 6px 0;
  color: #ffd700;
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.5px;
}
.sidebar-section p {
  margin: 0 0 8px 0;
  color: #fffde7;
}
</style>
