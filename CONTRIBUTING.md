# Contributing to EdgeOps Editorial

Thank you for your interest in contributing to the EdgeOps Blog! We aim to provide high-signal technical content for the modern engineering community.

## Editorial Workflow

To ensure a high standard of quality and consistency, we follow a structured editorial process. **Please do not open a Pull Request without an approved proposal.**

### 1. The Proposal Stage
- **Action**: [Open a "Blog Proposal" Issue](https://github.com/EdgeOpslabs/blogs/issues/new?template=blog_proposal.md).
- **Goal**: Share your topic, a brief outline, and why it matters to the EdgeOps audience.
- **Label**: Your issue will be labeled `editorial:proposal`.
- **Approval**: Once the core team reviews and approves the outline, the issue will be labeled `editorial:approved`.

### 2. The Writing Stage
- **Action**: Fork the repository and create a new branch `content/your-post-title`.
- **Content**: Create a new `.md` file in the `/post` directory.
- **Images**: Place any custom images in `/public/post/` and reference them using absolute paths like `/post/your-image.png`.
- **Frontmatter**: Ensure all required fields are filled out.

### 3. The Review Stage
- **Action**: Submit a Pull Request.
- **Review**: Technical and grammatical review by the EdgeOps team.
- **Label**: `editorial:review`.
- **Feedback**: Address any comments or suggested edits.

### 4. Publication
- **Action**: PR merged by a maintainer.
- **Deployment**: Automatic deployment to production.
- **Newsletter**: If `newsletter: true`, the post will be dispatched to subscribers.

## Technical Guidelines

### Markdown Standards
- Use H2 (`##`) and H3 (`###`) for content hierarchy. Reserve H1 (`#`) for the article title.
- Use fenced code blocks with language identifiers for syntax highlighting.
- Use inclusive, professional language.

### Image Optimization
- Use clear, professional diagrams (Mermaid, Excalidraw, etc.).
- Keep file sizes under 500KB where possible.
- Preferred formats: `.png`, `.jpg`, `.webp`.

## Labeling Strategy

We use labels to manage the lifecycle of content:
- `editorial:proposal`: Initial content idea.
- `editorial:approved`: Ready for writing.
- `editorial:review`: PR submitted and undergoing review.
- `editorial:published`: Merged and live on the platform.
- `type:technical`: Deep-dive technical content.
- `type:case-study`: Real-world implementation stories.

---
Questions? Open an issue or contact the maintainers.
