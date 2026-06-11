Build a modern, highly interactive web application for an advanced calculator using HTML, Tailwind CSS, and vanilla JavaScript in a single self-contained file. 

Key Requirements:
1. DESIGN & LAYOUT:
   - Modern, glassmorphic dark-mode interface using a "Plus Jakarta Sans" font, slate/indigo colors, and subtle border highlights.
   - The main standard grid must have 5 columns: 4 columns for numbers (0-9), decimal, backspace, and clear, and 1 dedicated column for mathematical operators (+, -, *, /, =).
   - An expandable "Scientific" panel containing sin, cos, tan, log, ln, xʸ, √, x!, π, and e.
   - Responsive, fluid design with no vertical scrolling. If the viewport is too small, a native scrollbar handles it gracefully.

2. DYNAMIC LABELS & TOGGLES:
   - Add a mode toggle button that changes between "Scientific" and "Basic" modes.
   - Dynamically update the header title: "Interactive Basic Calc v2.2" when in basic mode, and "Interactive Scientific Calc v2.2" when the scientific panel is open.

3. WINDOW CONTROLS:
   - Make the red, yellow, and green window headers interactive:
     * Red (Close): Fades out the calculator and reveals a "Launch Calculator" restore button on the desktop.
     * Yellow (Minimize): Collapses the display, workspace grid, and history panel while keeping the header visible.
     * Green (Maximize): Alternates the layout between a compact width (max-w-lg) and a wide layout (max-w-2xl). Maximize must automatically un-minimize the content container if it was hidden.

4. TOOLTIPS (HOVER BALLOONS):
   - Add sleek, custom Tailwind absolute-positioned hover tooltips for all non-numeric buttons (Close, Minimize, Maximize, Scientific/Basic toggle, standard operators, modulo, scientific operators, decimal, clear, backspace, and equals). 
   - Tooltips must be styled like modern glassmorphic capsules and use `pointer-events-none` to never obstruct clicks.

5. LOGIC & HISTORY:
   - Full keyboard event binding support (number keys, basic operators, Enter, Backspace, Escape).
   - A scrollable "Recent Calculations" history section displaying the last 5 operations.
   - Floating-point arithmetic precision up to 8 decimal places.
