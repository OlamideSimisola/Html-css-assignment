# Html-css-assignment
CSS Float
Originally created for newspaper-style layouts, the float property pushes an element to the far left or right of its container, allowing text to wrap cleanly around it.
One-Dimensional Flow: Float only controls horizontal positioning. Surrounding text flows around the floated element based on where it sits in the document.

The Layout Hack: In early web development, developers forced float to build multi-column page layouts. However, floating elements removes them from the normal document flow, which frequently causes parent elements to "collapse" to zero height. This required developers to use extra code workarounds, known as "clearfixes," to keep containers intact.

Best Use Case Today: Float is rarely used for entire page layouts now. Its main role is its original purpose: wrapping paragraph text around images or callout boxes inside articles.

CSS Grid
CSS Grid is a dedicated, two-dimensional layout system built specifically for complex web layouts. Instead of positioning individual elements relative to surrounding text, Grid lets you define a framework of rows and columns on a parent container first, then place child items anywhere within that framework.

Two-Dimensional Control: Grid manages both horizontal columns and vertical rows at the same time from a single parent container.

Clean Code: Grid handles spacing, alignment, and sizing automatically using simple properties like gap. It completely eliminates the need for clearfixes or complex margin math.

Best Use Case Today: Grid is the standard tool for full-page structures, card layouts, photo galleries, dashboards, and any interface requiring precise alignment across rows and columns.

CSS Grid Components
A grid always consists of:
A Grid Container - The parent (container) element, where the display property is set to grid or inline-grid
One or more Grid Items - The direct children of the grid container automatically becomes grid item
