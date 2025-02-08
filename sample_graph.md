```mermaid
classDiagram
    ProjectManagement --> Development
    ProjectManagement --> Documentation
    ProjectManagement --> Testing
    
    Development --> Frontend
    Development --> Backend
    
    class Frontend {
        +React
        +Vue
    }
    click Frontend "https://example.com/frontend" "Frontend Documentation"
    
    class Backend {
        +Node.js
        +Python
    }
    click Backend "https://example.com/backend" "Backend Documentation"
    
    class Documentation {
        +Technical_Specs
        +User_Guide
    }
    
    class Testing {
        +Unit_Tests
        +Integration_Tests
    }
    
    %% Add clickable links for specific technologies
    class React
    click React "https://reactjs.org" "React Documentation"
    
    class Vue
    click Vue "https://vuejs.org" "Vue Documentation"
    
    class Node.js
    click Node.js "https://nodejs.org" "Node.js Documentation"
    
    class Python
    click Python "https://python.org" "Python Documentation"
```
