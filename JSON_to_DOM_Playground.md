# JSON-to-DOM Playground – Build & Render Process

## Project Links

- **Base / Menu:** https://keshavsoft.github.io/json-to-tag/menu/index.html
- **Playground / Visual Renderer:** https://keshavsoft.github.io/json-to-tag/playground/show.html


## Process

1. Open the [Base Menu](https://keshavsoft.github.io/json-to-tag/menu/index.html).
2. Select the Bootstrap example that needs to be converted.
3. Open the original Bootstrap example and inspect its HTML structure.
4. Convert the HTML structure into the project's JSON-to-DOM format.
5. Use `tagName` for HTML elements.
6. Use `attributes` for classes, IDs, types, links, and Bootstrap attributes.
7. Use `children` for nested elements.
8. Use `textContent` for visible text.
9. Save the converted structure as `spec.json`.
10. Open the [JSON-to-DOM Playground](https://keshavsoft.github.io/json-to-tag/playground/show.html).
11. In **Visual Renderer**, select **Choose File**.
12. Upload the created `spec.json`.
13. The Playground reads and parses the JSON specification.
14. The JSON-to-DOM builder creates native DOM elements from the JSON.
15. Bootstrap classes and HTML attributes are applied to the generated elements.
16. The generated DOM is displayed in the Playground.
17. Compare the rendered page with the original Bootstrap example.
18. If the structure or styling differs, update `spec.json`.
19. Upload the updated JSON again and check the result.
20. **Final flow:** Bootstrap Example → HTML Structure → `spec.json` → Playground → JSON-to-DOM → Rendered Page.
