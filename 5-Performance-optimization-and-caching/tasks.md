Preventing main thread blocking with a dedicated web worker

Providing an optimized critical rendering path using:
    Compressed or minified JavaScript, HTML and CSS files to reduce render blocking
    
    Inline CSS for essential styles on a specific page, with asynchronous loading for additional styles as necessary

    Inline JavaScript files for initial rendering only where necessary (or otherwise eliminated, deferred, or marked as async)

    Ordered loading of remaining critical resources and early download of all critical assets to shorten the critical path length

    Reduced DOM depth to minimize browser layout/reflow

    Your browser's developer tools to diagnose performance issues on mobile devices

Prefetching files that load when resources are available, reducing the time to meaningful interaction

Providing client storage that is appropriate to a web application’s data persistence needs, including:

    Session state management
    
    Asset caching based on their impact on load time and offline functionality

    Using IndexedDB to store dynamic content in offline mode