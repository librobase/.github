A **Libro** (meaning 'book' in Spanish) is essentially a Jupyter Notebook 
packaged as a self-contained native app.

**LibroBase** is a framework for rapidly developing reliable native apps.
It leverages **Jupyter Server** as its central processing component, and all its 
components are bundled together using **Tauri** to ensure consistent operation 
across various operating systems. Additionally, the package includes a 
small **MicroMamba** executable to facilitate the creation and management of 
necessary dependencies within a local conda environmnt on computers without 
requiring having Python or Conda installed.

Developers can focus the majority of their efforts on creating a custom 
JavaScript frontend. LibroBase provides a comprehensive set of APIs that enable 
developers to implement all their backend logic within their frontend.

