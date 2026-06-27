# Heaven of Solution Blog Writing & Publishing Rules

Whenever writing, editing, or publishing new blog articles for the Heaven of Solution website, you must adhere to the following guidelines:

1. **Title & Routing URLs**:
   - Generated slugs must be clean and follow the lowercase, dash-separated format (e.g., `10-steps-to-use-gemini-ai-for-school-questions-the-smart-way`).
   - Tautan (links) to articles in the templates must be root-level (e.g., `/${post.slug}`) and never include the `.md` or `/blog/` prefix.

2. **Formatting & Structure**:
   - Use standard Markdown headings: H2 (`##`) for main sections and H3 (`###`) for sub-sections and FAQ questions.
   - Do NOT use em-dashes (`—` or `–`) in sentences. Always replace them with a comma (`, `) or a standard hyphen where appropriate.
   - Do NOT use horizontal rule dividers (`---`) in the content body to separate sections.
   - Use standard ordered lists (`1.`, `2.`) for steps and unordered lists (`-`) for regular bullet points.

3. **SEO Optimization (Ensure SEO Score > 50%)**:
   - Every article must have a defined Focus Keyword.
   - Include the Focus Keyword in the title, slug, and the first paragraph of the article.
   - Write a clear and compelling `description` (meta description) in the frontmatter (between 140-160 characters).
   - Assign the correct category to the frontmatter (e.g., `"AI Apps"`).

4. **Featured Image Handling**:
   - Place the featured image in `/public/wp-content/uploads/YYYY/MM/` with a clean, lowercase, dash-separated filename.
   - Define the `featuredImage` path correctly in the frontmatter pointing to this uploaded image.
