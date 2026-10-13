<script setup>
import BSITHero from '../BSIT_section/bsit_hero.vue'
</script>

<template>
  <main class="about-me-page">
    <BSITHero />

    <section>
      <h2>What You Will Learn</h2>
      <p>
        Students can develop skills in programming, analyzing user and business
        needs, managing data, understanding networks, and troubleshooting
        technology. The program also encourages communication, teamwork, and
        problem-solving skills.
      </p>
    </section>

    <section>
      <h2>Career Opportunities</h2>
      <p>Graduates may pursue roles such as:</p>
      <ul>
        <li>Web or application developer</li>
        <li>IT support specialist</li>
        <li>Systems analyst</li>
        <li>Database or network technician</li>
        <li>Technical support associate</li>
      </ul>
      <p>
        Specific job requirements vary. Some roles may require additional
        experience, training, or certifications.
      </p>
    </section>

    <section>
      <h2>Why Choose This Program</h2>
      <p>
        BSIT can be a good choice for students who want to understand how
        technology is used in real-world settings. Its broad subject areas can
        provide a foundation for exploring different IT careers and continuing
        to learn as technology changes.
      </p>
    </section>

    <section>
      <h2>Who Should Enroll</h2>
      <p>
        This program may suit students who are curious about technology, enjoy
        solving problems, and are willing to learn through practice. An interest
        in computers can help, but patience, creativity, and a willingness to
        keep learning are also valuable.
      </p>
    </section>

    <section>
      <h2>Other Relevant Information</h2>
      <p>
        Add verified details here, such as the official curriculum, internship
        requirements, available laboratories, student organizations, or
        certifications supported by your school. These details vary by
        institution, so confirm them using official school materials.
      </p>
    </section>
  </main>
</template>

<style scoped>

:global(body) {
  min-height: 100vh;
  background: #0A051A;
}

.about-me-page {
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 100vh;
  width: 100%;
  padding: 40px 24px;
  background: #0A051A;
}

h1,
section {
  width: 100%;
  max-width: 900px;
}

h1 {
  margin: 0 0 28px;
  font-size: 2.5rem;
  color: #D946EF; 
  text-align: center;
  text-shadow: 0 0 10px rgba(217, 70, 239, 0.4); 
}

section {
  margin-bottom: 20px;
  padding: 24px;
  background: #13092A; 
  border: 1px solid #9D4EDD; 
  border-left: 5px solid #D946EF; 
  border-radius: 8px;
  box-shadow: 0 4px 15px rgba(217, 70, 239, 0.15);
}

h2 {
  margin: 0 0 12px;
  color: #D946EF; 
}

p {
  margin: 0 0 12px;
  line-height: 1.6;
  color: #e2e8f0; 
}

p:last-child {
  margin-bottom: 0;
}

ul {
  padding-left: 24px;
  line-height: 1.8;
  color: #e2e8f0;
}

@media (max-width: 600px) {
  .about-me-page {
    padding: 24px 14px;
  }

  h1 {
    font-size: 2rem;
  }

  section {
    padding: 18px;
  }
}
</style>
