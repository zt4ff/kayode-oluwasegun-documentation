# The Bookshop

Browse our curated collection of thought-provoking books.

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

<div class="book-card">
  <a href="/reading/books/read/1984-by-george-orwell/">
    <img src="https://covers.openlibrary.org/b/id/7222246-L.jpg" alt="1984">
    <h3>1984</h3>
    <p class="author">George Orwell</p>
    <span class="tag">Fiction</span>
  </a>
</div>

<div class="book-card">
  <a href="/reading/books/read/sapiens-by-yuval-noah-harari/">
    <img src="https://covers.openlibrary.org/b/id/8245447-L.jpg" alt="Sapiens">
    <h3>Sapiens</h3>
    <p class="author">Yuval Noah Harari</p>
    <span class="tag">History</span>
  </a>
</div>

<div class="book-card">
  <a href="/reading/books/read/the-hero-with-a-thousand-faces-by-joseph-campbell/">
    <img src="https://covers.openlibrary.org/b/id/8503543-L.jpg" alt="The Hero With a Thousand Faces">
    <h3>The Hero With a Thousand Faces</h3>
    <p class="author">Joseph Campbell</p>
    <span class="tag">Mythology</span>
  </a>
</div>

<div class="book-card">
  <a href="/reading/books/read/cosmos-by-carl-sagan/">
    <img src="https://covers.openlibrary.org/b/id/8231887-L.jpg" alt="Cosmos">
    <h3>Cosmos</h3>
    <p class="author">Carl Sagan</p>
    <span class="tag">Science</span>
  </a>
</div>

<div class="book-card">
  <a href="/reading/books/read/meditations-the-annotated-edition-by-marcus-aurelius/">
    <img src="https://covers.openlibrary.org/b/id/8307408-L.jpg" alt="Meditations">
    <h3>Meditations</h3>
    <p class="author">Marcus Aurelius</p>
    <span class="tag">Philosophy</span>
  </a>
</div>

<div class="book-card">
  <a href="/reading/books/read/man-s-search-for-meaning-by-viktor-e-frankl/">
    <img src="https://covers.openlibrary.org/b/id/8482050-L.jpg" alt="Man's Search for Meaning">
    <h3>Man's Search for Meaning</h3>
    <p class="author">Viktor E. Frankl</p>
    <span class="tag">Psychology</span>
  </a>
</div>

<div class="book-card">
  <a href="/reading/books/read/the-god-delusion-by-richard-dawkins/">
    <img src="https://covers.openlibrary.org/b/id/8235826-L.jpg" alt="The God Delusion">
    <h3>The God Delusion</h3>
    <p class="author">Richard Dawkins</p>
    <span class="tag">Philosophy</span>
  </a>
</div>

<div class="book-card">
  <a href="/reading/books/read/sapiens-by-yuval-noah-harari/">
    <img src="https://covers.openlibrary.org/b/id/8245447-L.jpg" alt="Sapiens">
    <h3>The Denial of Death</h3>
    <p class="author">Ernest Becker</p>
    <span class="tag">Philosophy</span>
  </a>
</div>

<div class="book-card">
  <a href="/reading/books/read/between-the-world-and-me-by-ta-nehisi-coates/">
    <img src="https://covers.openlibrary.org/b/id/8235960-L.jpg" alt="Between the World and Me">
    <h3>Between the World and Me</h3>
    <p class="author">Ta-Nehisi Coates</p>
    <span class="tag">Memoir</span>
  </a>
</div>

<div class="book-card">
  <a href="/reading/books/read/the-lord-of-the-rings-by-john-ronald-reuel-tolkien/">
    <img src="https://covers.openlibrary.org/b/id/8231708-L.jpg" alt="The Lord of the Rings">
    <h3>The Lord of the Rings</h3>
    <p class="author">J.R.R. Tolkien</p>
    <span class="tag">Fantasy</span>
  </a>
</div>

<div class="book-card">
  <a href="/reading/books/read/v-for-vendetta-by-alan-moore/">
    <img src="https://covers.openlibrary.org/b/id/8486391-L.jpg" alt="V for Vendetta">
    <h3>V for Vendetta</h3>
    <p class="author">Alan Moore</p>
    <span class="tag">Graphic Novel</span>
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

---

## Recently Added

Check back regularly for new additions to our collection.

**Total Books**: 12 displayed | [View All →](/reading/books/read/)
