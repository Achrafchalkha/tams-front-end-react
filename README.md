# Talent Acquisition Management System (TAMS)

This project is the frontend of a full-stack microservices-based Talent Acquisition Management System (TAMS), built with React and Redux. It interacts with a Spring Boot backend and enables hiring managers to create and manage talent requests, talent acquisition specialists to fulfill these requests, and job seekers to explore job openings.

## Table of Contents

- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with this project, clone the repository and install the dependencies:

```sh
git clone https://github.com/Achrafchalkha/TAMS-REACT-FRONTEND
npm install
Available Scripts
In the project directory, you can run:

npm start
Runs the app in development mode.
Open http://localhost:3000 to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

npm test
Launches the test runner in interactive watch mode.
See the section about running tests for more information.

npm run build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.
The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

npm run eject
Note: this is a one-way operation. Once you eject, you can't go back!

If you aren't satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc.) right into your project so you have full control over them. All of the commands except eject will still work, but they will point to the copied scripts so you can tweak them. At this point, you're on your own.

You don't have to ever use eject. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However, we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Project Structure

├── .gitignore
├── [package.json](http://_vscodecontentref_/0)
├── [README.md](http://_vscodecontentref_/1)
├── public
│   ├── favicon.ico
│   ├── [index.html](http://_vscodecontentref_/2)
│   ├── logo192.png
│   ├── logo512.png
│   ├── [manifest.json](http://_vscodecontentref_/3)
│   └── [robots.txt](http://_vscodecontentref_/4)
└── src
    ├── [App.js](http://_vscodecontentref_/5)
    ├── [index.css](http://_vscodecontentref_/6)
    ├── [index.js](http://_vscodecontentref_/7)
    ├── [reportWebVitals.js](http://_vscodecontentref_/8)
    ├── app
    │   └── [store.js](http://_vscodecontentref_/9)
    ├── components
    │   ├── [BackButton.jsx](http://_vscodecontentref_/10)
    │   ├── [Header.jsx](http://_vscodecontentref_/11)
    │   ├── [LoadingSpinner.jsx](http://_vscodecontentref_/12)
    │   ├── Career-Portal
    │   │   ├── [CareerPortalHome.jsx](http://_vscodecontentref_/13)
    │   │   ├── [JobPostByIdView.jsx](http://_vscodecontentref_/14)
    │   │   ├── [JobPostItem.jsx](http://_vscodecontentref_/15)
    │   │   └── [JobPostsView.jsx](http://_vscodecontentref_/16)
    │   ├── Hiring-Manager-Portal
    │   │   ├── [CreateTalentRequestForm.jsx](http://_vscodecontentref_/17)
    │   │   ├── [HiringManagerPortalHome.jsx](http://_vscodecontentref_/18)
    │   │   ├── [TalentRequestByIdView.jsx](http://_vscodecontentref_/19)
    │   │   ├── [TalentRequestItem.jsx](http://_vscodecontentref_/20)
    │   │   └── [TalentRequestsView.jsx](http://_vscodecontentref_/21)
    │   └── Talent-Acquisition-Portal
    │       ├── [ApprovedTalentFulfillmentByIdView.jsx](http://_vscodecontentref_/22)
    │       ├── [TalentFulfillmentByIdView.jsx](http://_vscodecontentref_/23)
    │       ├── [TalentFulfillmentItem.jsx](http://_vscodecontentref_/24)
    │       ├── [TalentFulfillmentPortalHome.jsx](http://_vscodecontentref_/25)
    │       └── [TalentFulfillmentsView.jsx](http://_vscodecontentref_/26)
    ├── features
    │   ├── CareerPortal
    │   │   ├── [careerPortalService.js](http://_vscodecontentref_/27)
    │   │   └── [careerPortalSlice.js](http://_vscodecontentref_/28)
    │   ├── TalentFulfillment
    │   │   ├── [talentFulfillmentService.js](http://_vscodecontentref_/29)
    │   │   └── [talentFulfillmentSlice.js](http://_vscodecontentref_/30)
    │   └── TalentRequest
    │       ├── [TalentRequestService.js](http://_vscodecontentref_/31)
    │       └── [TalentRequestSlice.js](http://_vscodecontentref_/32)
    └── pages
        └── [TAMSHome.jsx](http://_vscodecontentref_/33)



## Dependencies

React
Redux
Redux Toolkit
React Router DOM
Axios
React Toastify

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

