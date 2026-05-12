# Leakey Labs Website Redesign: From Educator to Trading Systems Engineer

## 1. Goal

To evolve the Leakey Labs personal brand website from a "trading educator" focus to a "trading systems engineer" focus, emphasizing practical system building, experimentation, and technical proof. This involves restructuring the site architecture, introducing new content types, and enhancing visual elements.

## 2. Current Site Analysis (Summary)

The current site (`index.html`) features sections for "Proof & Infrastructure," "Trading Systems & Infrastructure," "Financial System Storytelling," and "Trading Insights & Technical Articles." While relevant content exists, the overall presentation leans heavily towards educational articles, and the most impactful sections (Proof, Systems) are not prominently featured.

## 3. Proposed Site Architecture (Homepage - `index.html`)

The homepage will be reordered to prioritize systems, proof, and experimentation, followed by supporting articles. The new order of sections will be:

1.  **Hero Section**: Remains largely the same, but with refined messaging to immediately convey the "Trading Systems Engineer" identity.
2.  **Featured Systems**: This will be the most prominent section after the hero. It will showcase ONE flagship system in depth, with clear visuals and a link to a dedicated "System Breakdown" page.
3.  **Proof & Experiments**: This section will combine existing proof elements with new "Experiment Logs." It will feature visual evidence of system performance, backtest results, and ongoing research.
4.  **System Breakdown Posts**: A new section linking to detailed posts about the architecture and implementation of various trading systems.
5.  **Experiment Logs**: A new section linking to posts detailing specific trading experiments, their methodologies, and results.
6.  **Trading Insights & Technical Articles**: The existing articles section, repositioned to support the systems and experiments rather than dominate the identity.
7.  **Financial System Storytelling**: Remains as a supporting section for broader narratives.
8.  **Footer**: Standard footer with navigation and contact information.

## 4. New Content Types and Strategy

### A. Featured Systems (Homepage Section)

*   **Purpose**: To immediately demonstrate expertise in building functional trading systems.
*   **Content**: A concise overview of ONE flagship system. This will include:
    *   System Name and primary function.
    *   Key technologies/methodologies used.
    *   A compelling visual (e.g., a dashboard screenshot, architecture diagram).
    *   A clear call to action to "Explore System Breakdown" (linking to a dedicated System Breakdown Post).

### B. System Breakdown Posts (New Page/Section)

*   **Purpose**: To provide in-depth technical details about specific trading systems.
*   **Examples**: "Architecture of My SMT Detection Engine," "How My Python Bot Handles Risk," "Building a Multi-Timeframe Confirmation System."
*   **Content Structure for each post**:
    *   **Overview**: What the system does and its core objective.
    *   **Architecture**: Detailed diagrams (flowcharts, component diagrams) showing how different parts of the system interact.
    *   **Key Components**: Explanation of modules (e.g., data ingestion, signal generation, execution, risk management).
    *   **Technology Stack**: Programming languages, libraries, databases, APIs used.
    *   **Code Snippets**: Illustrative code examples (e.g., a function for SMT detection, a snippet for risk calculation).
    *   **Visuals**: Screenshots of dashboards, execution logs, data flows.
    *   **Challenges & Solutions**: Insights into development hurdles and how they were overcome.
    *   **Future Enhancements**: Potential improvements or next steps.

### C. Experiment Logs (New Page/Section)

*   **Purpose**: To showcase a research-oriented approach and provide empirical evidence.
*   **Examples**: "30-Day FVG Backtest Results," "Testing ML Filters on ICT Setups," "Win Rate Analysis of SMT Divergence."
*   **Content Structure for each log**:
    *   **Experiment Title & Objective**: Clearly state what is being tested.
    *   **Hypothesis**: What is expected to be observed.
    *   **Methodology**: Detailed description of the experiment setup, data used, timeframes, and testing parameters.
    *   **Results**: Presentation of findings, including charts, tables, and statistical analysis.
    *   **Analysis**: Interpretation of results, discussing successes, failures, and unexpected outcomes.
    *   **Visuals**: Performance charts (equity curves, drawdown charts), statistical tables, relevant data visualizations.
    *   **Conclusion & Future Work**: Summary of insights and next steps for research or system integration.

### D. Visual Technical Content (Integrated Across Site)

*   **Purpose**: To enhance credibility, engagement, and clarity.
*   **Integration**: Every section, especially "Featured Systems," "System Breakdown Posts," and "Experiment Logs," will heavily feature:
    *   **Charts**: Performance charts, market data visualizations.
    *   **Screenshots**: Of trading terminals, custom dashboards, code editors, execution logs.
    *   **Dashboards**: Custom-built analytical dashboards showing real-time or historical data.
    *   **Code Snippets**: Well-formatted, highlighted code examples.
    *   **Execution Flows**: Diagrams illustrating the step-by-step process of a system.
    *   **Architecture Diagrams**: Visual representations of system components and their interactions.

## 5. Technical Implementation Notes

*   **HTML Structure**: Modify `index.html` to reorder sections and add new containers for "Featured Systems," "System Breakdown Posts," and "Experiment Logs."
*   **CSS Styling**: Ensure new sections and content types are styled consistently with the existing aesthetic.
*   **Content Management**: For new content types, consider creating dedicated HTML files (similar to existing articles) or a simple templating approach if complexity increases.
*   **Asset Management**: Organize new images and diagrams within the `assets/proof` directory or a new `assets/systems` directory.

## 6. Next Steps

1.  **Generate Visual Assets**: Create or identify suitable images for the new "Featured Systems" and new content types.
2.  **Modify `index.html`**: Implement the new section order and structure.
3.  **Create New Content Pages**: Develop initial "System Breakdown Posts" and "Experiment Logs" pages.
4.  **Integrate Visuals**: Add charts, screenshots, and code snippets to new and existing content.
5.  **Review and Refine**: Ensure the site effectively communicates the "Trading Systems Engineer" brand.
