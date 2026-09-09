<style>
:root {
  --research-purple: #552D98;
  --research-orange: #E69735;
  --research-orange-light: rgba(230, 151, 53, 0.35);
}

.research-section {
  margin-top: 2.2rem;
  margin-bottom: 3rem;
}

.research-heading {
  display: flex;
  align-items: center;
  font-size: 1.25rem;
  font-weight: 700;
  margin-bottom: 1.2rem;
  border-bottom: 1px solid #e5e5e5;
  padding-bottom: 0.6rem;
}

.research-heading::before {
  content: "";
  width: 7px;
  height: 24px;
  background: var(--research-purple);
  border-radius: 4px;
  margin-right: 12px;
}

.research-card {
  position: relative;
  border: 1px solid #e1e1e1;
  border-top: 3px solid var(--research-orange);
  border-radius: 9px;
  padding: 1.25rem 1.3rem 1rem 5.2rem;
  margin-bottom: 1.2rem;
  box-shadow: 0 1px 4px rgba(0,0,0,0.04);
}

.paper-tag {
  position: absolute;
  left: 1.2rem;
  top: 1.25rem;
  min-width: 50px;
  text-align: center;
  padding: 2px 9px;
  border-radius: 14px;

  background: var(--research-purple);
  color: white;

  font-size: 0.8rem;
  font-weight: 700;
  border: 1px solid var(--research-orange);
}

.paper-title {
  font-size: 1.08rem;
  font-weight: 600;
  line-height: 1.35;
  margin-bottom: 0.25rem;
}

.paper-authors {
  font-size: 0.95rem;
  margin-bottom: 0.35rem;
}

.paper-authors a {
  color: var(--research-purple);
  text-decoration: underline;
}

.paper-status {
  color: #777;
  font-size: 0.95rem;
  margin-bottom: 0.7rem;
}

.paper-status em {
  color: #444;
}

.paper-buttons {
  margin: 0.5rem 0 0.8rem 0;
}

.paper-button {
  display: inline-block;
  padding: 3px 9px;
  margin-right: 5px;
  border: 1px solid #333;
  border-radius: 4px;
  color: inherit;
  font-size: 0.78rem;
  text-decoration: none;
}

.paper-button:hover {
  background: #f3f3f3;
  text-decoration: none;
}

.research-details {
  border-top: 1px solid var(--research-orange-light);
  padding-top: 0.7rem;
  margin-top: 0.6rem;
}

.research-details summary {
  cursor: pointer;
  color: var(--research-purple);
  font-weight: 600;
  font-size: 0.88rem;
  list-style: none;
}

.research-details summary::-webkit-details-marker {
  display: none;
}

.research-details p {
  margin-top: 0.8rem;
  margin-bottom: 0.2rem;
  line-height: 1.55;
  font-size: 0.93rem;
}

@media (max-width: 700px) {
  .research-card {
    padding: 3.4rem 1rem 1rem 1rem;
  }

  .paper-tag {
    left: 1rem;
    top: 1rem;
  }
}
</style>
