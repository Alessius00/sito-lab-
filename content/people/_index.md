---
title: "People"
summary: "Members of the Personnel Psychology Lab."
---

<div class="people-grid">

<a class="person-card" href="/sito-lab-/authors/michelangelo-vianello/">
  <div class="person-placeholder">MV</div>
  <h3>Michelangelo Vianello</h3>
  <p>Professor</p>
</a>

<a class="person-card" href="/sito-lab-/authors/anna-dalla-rosa/">
  <div class="person-placeholder">ADR</div>
  <h3>Anna Dalla Rosa</h3>
  <p>Assistant Professor</p>
</a>

<a class="person-card" href="/sito-lab-/authors/alessio-pasto/">
  <div class="person-placeholder">AP</div>
  <h3>Alessio Pasto</h3>
  <p>PhD Student</p>
</a>

</div>

<style>
.people-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 3rem;
  margin: 2rem auto;
  max-width: 1000px;
}

.person-card {
  text-align: center;
  padding: 1rem;
  text-decoration: none;
  color: inherit;
  border: none;
}

.person-card:hover {
  transform: translateY(-2px);
}

.person-placeholder {
  width: 160px;
  height: 160px;
  border-radius: 0;
  background: #e5e7eb;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 1rem auto;
  font-size: 2.2rem;
  font-weight: bold;
  box-shadow: 8px 8px 18px rgba(0,0,0,0.18);
}

.person-card h3 {
  font-size: 1.1rem;
  margin: 0.75rem 0 0.25rem 0;
  font-weight: 500;
}

.person-card p {
  font-size: 1rem;
  margin: 0;
  font-style: italic;
  color: #6b7280;
}

@media (max-width: 800px) {
  .people-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 500px) {
  .people-grid {
    grid-template-columns: 1fr;
  }
}
</style>
