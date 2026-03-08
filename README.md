# AI Product Designer Portfolio

Portfolio for the Tangent AI Product Designer role and similar positions.

## How to view locally

1. Open `index.html` in a browser, or
2. Run a simple server:
   ```bash
   cd portfolio
   python3 -m http.server 8000
   ```
   Then open http://localhost:8000

## Adding your own images

Replace the placeholder divs with your actual screenshots:

1. **Create an `images/` folder** in the portfolio directory
2. Add your images (e.g. `chatbot-flow.png`, `pareto-plot.png`)
3. In the HTML, replace:
   ```html
   <div class="placeholder-image"><span>Add screenshot here</span></div>
   ```
   with:
   ```html
   <img src="images/chatbot-flow.png" alt="Chatbot flow diagram">
   ```

## Suggested images to add

- **Chatbot case study:** Figma screenshots of conversation flows, wireframes, or a flow diagram
- **AI interfaces case study:** UI mockups, prototype screens, or design system components
- **Research case study:** Pareto plot from your dissertation (`analysis plot/pareto_accuracy_vs_latency.png`), accuracy charts, or explainability visualisations

## Hosting

- **GitHub Pages:** Push to a repo, enable Pages, set source to main branch
- **Netlify:** Drag and drop the `portfolio` folder to netlify.com/drop
- **Vercel:** Connect repo or run `vercel` in the portfolio folder

## Customisation

- Update colours in `styles.css` (`:root` variables)
- Edit `index.html` and case study pages to match your voice
- Add or remove case studies as needed
