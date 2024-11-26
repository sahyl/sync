

**SYNC**
========

SYNC is a Next.js-based video conferencing platform inspired by Zoom. It leverages modern libraries like @stream-io/video-react-sdk for video functionality and TailwindCSS for UI design. The project includes features like scheduling meetings, joining calls, recording sessions, and managing user authentication through Clerk.

**Features**
------------

*   🎥 **Video Conferencing:** Join and host video meetings powered by Stream's Video SDK.
    
*   📅 **Meeting Scheduling:** Plan and schedule meetings with custom descriptions and date-time settings.
    
*   📼 **Recordings Management:** View and play back recorded meetings.
    
*   📱 **Responsive UI:** Built with TailwindCSS for a seamless experience on any device.
    
*   🔐 **User Authentication:** Secure authentication using Clerk's Next.js integration.
    

**Tech Stack**
--------------

*   **Frontend Framework:** [Next.js](https://nextjs.org/) v15
    
*   **UI Framework:** [React](https://reactjs.org/) v18 with [TailwindCSS](https://tailwindcss.com/)
    
*   **Video SDK:** [@stream-io/video-react-sdk](https://getstream.io/video/)
    
*   **Authentication:** [Clerk](https://clerk.dev/) for user management
    
*   **State Management:** Radix UI components and hooks
    
*   **Date Picker:** [react-datepicker](https://reactdatepicker.com/)
    

**Getting Started**
-------------------

### 1\. Clone the Repository

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   bashCopy codegit clone https://github.com/yourusername/yoom.git  cd yoom   `

### 2\. Install Dependencies

Make sure you have Node.js installed, then run:

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   bashCopy codenpm install   `

### 3\. Set Environment Variables

Create a .env.local file in the project root and set the following:

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   envCopy codeNEXT_PUBLIC_BASE_URL=http://localhost:3000  STREAM_API_KEY=  CLERK_FRONTEND_API=  CLERK_API_KEY=   `

### 4\. Run the Development Server

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   bashCopy codenpm run dev   `

The application will be available at http://localhost:3000.

**Scripts**
-----------

ScriptDescriptionnpm run devStarts the development server with Turbopack.npm run buildBuilds the project for production.npm run startRuns the production build.npm run lintLints the codebase using ESLint.

**Dependencies**
----------------

Refer to the package.json for all dependencies. Key packages include:

*   @stream-io/video-react-sdk: For video calling functionality.
    
*   @clerk/nextjs: User authentication.
    
*   tailwindcss: Styling framework.
    
*   react-datepicker: Scheduling features.
    

**Development Tools**
---------------------

*   **TypeScript**: Ensures type safety across the application.
    
*   **ESLint**: For linting and maintaining code quality.
    
*   **PostCSS**: For enhanced styling workflows.
    

**Contributing**
----------------

Contributions are welcome! Follow these steps:

1.  Fork the repository.
    
2.  bashCopy codegit checkout -b feature-name
    
3.  bashCopy codegit commit -m "Add your message here"git push origin feature-name
    
4.  Create a pull request.
    

**License**
-----------

This project is licensed under the MIT License. See the LICENSE file for details.

**Acknowledgements**
--------------------

*   [Stream.io](https://getstream.io/) for their powerful video SDK.
    
*   [Clerk](https://clerk.dev/) for seamless authentication.
    
*   [Next.js](https://nextjs.org/) for the robust framework.
