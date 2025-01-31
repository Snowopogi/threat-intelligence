Threat Intelligence Correlation & Visualization ToolThis project is a full-stack web application that collects and visualizes threat intelligence data. It consists of a React.js frontend and a Node.js (Express) backend.
FeaturesFetch and display threat intelligence data in a structured format.
Simple API with mock threat reports.
Frontend developed using React.js.
Backend developed using Node.js + Express.
Tech StackFrontend: React.js
Backend: Node.js, Express
API Communication: Axios
Installation & Setup1. Clone the Repositorygit clone https://github.com/yourusername/threat-intelligence-tool.git
cd threat-intelligence-tool2. Setup the Backendcd backend
npm install
node server.jsThis starts the backend server on http://localhost:5000.
3. Setup the Frontendcd ../frontend
npm install
npm startThis starts the frontend on http://localhost:3000.
API EndpointMethodEndpointDescriptionGET/api/threatsFetches threat intelligenceUploading to GitHub1. Initialize a Git Repositorygit init
git add .
git commit -m "Initial commit"2. Add Remote Repositorygit remote add origin https://github.com/yourusername/threat-intelligence-tool.git
git branch -M main
git push -u origin mainLicenseThis project is licensed under the MIT License.
