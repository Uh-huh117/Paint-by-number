This is a completely AI made program- mainly for me to test the capabilities of Gemini and ChatGPT.

This is intended to be a web app for iOS. If you want to use it, open https://uh-huh117.github.io/Paint-by-number/ in Safari. From there, share the link and add it to your home screen. It should be ready to use.

I have no idea how it works on Android, Mac, Windows, or Linux. This was tested on iOS 17.

Current features:

Deployment and Architecture;

-Web-Based Execution: Designed as a single-file Single-Page Application (SPA) deployable via GitHub Pages.

-Optimized Rendering Engine: Utilizes an offscreen canvas and direct ImageData manipulation with hardware acceleration to minimize latency across large grids.
-Image Conversion and Customization

-Pixel Art Conversion: Converts standard raster images into pixel art grids utilizing K-Means color clustering algorithms.

-Configurable Parameters: Features adjustable sliders supporting up to 120 custom colors and up to 40,000 pixels per project.

Gallery and Data Persistence;

-Centralized Gallery Dashboard: Displays all active and completed projects with dynamic progress indicators and thumbnail previews.

-Automatic Storage Management: Integrates local storage capabilities to automatically save progress upon color completion, project exit, or session updates.

-Dual Display Modes: Provides a standard workspace with a white background for active painting and a dark-background viewing mode for completed artworks.
Navigation and Controls

-Streamlined Pan and Zoom: Supports desktop navigation via mouse wheel zooming and spacebar-enabled panning, alongside mobile multi-touch pinch-to-zoom and fluid drag gestures.

-Collapsible UI Elements: Features a slide-out sidebar for efficient workspace maximization.

Painting Tools and Assistance;

-Variable Brush Sizing: Includes a scalable brush utility ranging from 1x1 up to 7x7 dimensions.

-Continuous Drag-Painting: Supports hold-and-drag functionality for fluid application without manual stamping.

-Smart Hint System: Automatically locates, zooms to, and highlights a random unpainted cell corresponding to the active color selection.

-Automated Color Progression: Automatically advances to the next uncompleted color upon finishing a color set, accompanied by non-invasive completion notifications.
