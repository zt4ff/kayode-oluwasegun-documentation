# Books I've Read

Browse through books I've read.

---

<div class="book-grid">

<div class="book-card">
  <a href="/reading/books/read/21-lessons-for-the-21st-century-by-yuval-noah-harari/">
    <img src="https://books.google.com/books/content?id=lIyTEAAAQBAJ&printsec=frontcover&img=1&zoom=1&source=gbs_api" alt="21 Lessons for the 21st Century">
    <h3>21 Lessons for the 21st Century</h3>
    <p class="author">Yuval Noah Harari</p>
    <span class="tag">History</span>
  </a>
</div>

</div>

<style>
.book-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.book-card {
  background: var(--md-default-bg-color);
  border: 1px solid var(--md-default-fg-color--lightest);
  border-radius: 8px;
  overflow: hidden;
  transition: transform 0.2s, box-shadow 0.2s;
}

.book-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 16px rgba(0,0,0,0.1);
}

.book-card a {
  text-decoration: none;
  color: inherit;
  display: block;
}

.book-card img {
  width: 100%;
  height: 300px;
  object-fit: cover;
  display: block;
}

.book-card h3 {
  margin: 1rem 1rem 0.5rem;
  font-size: 1.1rem;
  line-height: 1.3;
  min-height: 2.6em;
}

.book-card .author {
  margin: 0 1rem;
  color: var(--md-default-fg-color--light);
  font-size: 0.9rem;
}

.book-card .tag {
  display: inline-block;
  margin: 0.5rem 1rem 1rem;
  padding: 0.25rem 0.75rem;
  background: var(--md-primary-fg-color);
  color: white;
  border-radius: 12px;
  font-size: 0.75rem;
  font-weight: 500;
}

@media (max-width: 768px) {
  .book-grid {
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: 1rem;
  }
  
  .book-card img {
    height: 220px;
  }
}
</style>
