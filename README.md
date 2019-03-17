Exercise files download location: https://app.pluralsight.com/library/courses/react-redux-react-router-es6/exercise-files

Environment
OS: Windows 10
Node: v10.15.0
npm: v6.4.1


Steps to reproduce

1. Download exercise files from:-
	https://app.pluralsight.com/library/courses/react-redux-react-router-es6/exercise-files

2. Extract .zip to "C:\mydev\pluralsight\react-redux-react-router-es6"

3. Within VS Code open folder "C:\mydev\pluralsight\react-redux-react-router-es6\05\demos\demos\after"

3. Navigate to project root, via command line, and run "npm install"

4. Launch app by running npm start

5. Navigate to http://localhost:3000/. Blank screen is displayed with errors below in console


************************************************************************************************************************
*
*Chrome Console Log
*
************************************************************************************************************************
warnAboutDeprecatedESMImport.js:17 Warning: Please use `import { Router } from "react-router"` instead of `import Router from "react-router/es/undefined"`. Support for the latter will be removed in the next major release.
printWarning @ warnAboutDeprecatedESMImport.js:17
warnAboutDeprecatedESMImport.js:17 Warning: Please use `import { MemoryRouter } from "react-router"` instead of `import MemoryRouter from "react-router/es/undefined"`. Support for the latter will be removed in the next major release.
printWarning @ warnAboutDeprecatedESMImport.js:17
warnAboutDeprecatedESMImport.js:17 Warning: Please use `import { Route } from "react-router"` instead of `import Route from "react-router/es/undefined"`. Support for the latter will be removed in the next major release.
printWarning @ warnAboutDeprecatedESMImport.js:17
warnAboutDeprecatedESMImport.js:17 Warning: Please use `import { Prompt } from "react-router"` instead of `import Prompt from "react-router/es/undefined"`. Support for the latter will be removed in the next major release.
printWarning @ warnAboutDeprecatedESMImport.js:17
warnAboutDeprecatedESMImport.js:17 Warning: Please use `import { Redirect } from "react-router"` instead of `import Redirect from "react-router/es/undefined"`. Support for the latter will be removed in the next major release.
printWarning @ warnAboutDeprecatedESMImport.js:17
warnAboutDeprecatedESMImport.js:17 Warning: Please use `import { StaticRouter } from "react-router"` instead of `import StaticRouter from "react-router/es/undefined"`. Support for the latter will be removed in the next major release.
printWarning @ warnAboutDeprecatedESMImport.js:17
warnAboutDeprecatedESMImport.js:17 Warning: Please use `import { Switch } from "react-router"` instead of `import Switch from "react-router/es/undefined"`. Support for the latter will be removed in the next major release.
printWarning @ warnAboutDeprecatedESMImport.js:17
warnAboutDeprecatedESMImport.js:17 Warning: Please use `import { generatePath } from "react-router"` instead of `import generatePath from "react-router/es/undefined"`. Support for the latter will be removed in the next major release.
printWarning @ warnAboutDeprecatedESMImport.js:17
warnAboutDeprecatedESMImport.js:17 Warning: Please use `import { matchPath } from "react-router"` instead of `import matchPath from "react-router/es/undefined"`. Support for the latter will be removed in the next major release.
printWarning @ warnAboutDeprecatedESMImport.js:17
warnAboutDeprecatedESMImport.js:17 Warning: Please use `import { withRouter } from "react-router"` instead of `import withRouter from "react-router/es/undefined"`. Support for the latter will be removed in the next major release.
printWarning @ warnAboutDeprecatedESMImport.js:17
checkPropTypes.js:20 Warning: Failed context type: The context `router` is marked as required in `Link`, but its value is `undefined`.
    in Link (created by Context.Consumer)
    in Route (created by NavLink)
    in NavLink (at Header.js:8)
    in nav (at Header.js:7)
    in Header (at App.js:12)
    in div (at App.js:11)
    in App (at src/index.js:10)
    in Router (created by BrowserRouter)
    in BrowserRouter (at src/index.js:9)
printWarning @ checkPropTypes.js:20
4browser.js:45 Uncaught Invariant Violation: You should not use <Link> outside a <Router>
    at invariant (http://localhost:3000/bundle.js:3161:15)
    at Link.render (http://localhost:3000/bundle.js:27109:53)
    at finishClassComponent (http://localhost:3000/bundle.js:20040:31)
    at updateClassComponent (http://localhost:3000/bundle.js:19995:24)
    at beginWork (http://localhost:3000/bundle.js:20943:16)
    at performUnitOfWork (http://localhost:3000/bundle.js:24611:12)
    at workLoop (http://localhost:3000/bundle.js:24651:24)
    at HTMLUnknownElement.callCallback (http://localhost:3000/bundle.js:5654:14)
    at Object.invokeGuardedCallbackDev (http://localhost:3000/bundle.js:5704:16)
    at invokeGuardedCallback (http://localhost:3000/bundle.js:5761:31)
react-dom.development.js:16911 The above error occurred in the <Link> component:
    in Link (created by Context.Consumer)
    in Route (created by NavLink)
    in NavLink (at Header.js:8)
    in nav (at Header.js:7)
    in Header (at App.js:12)
    in div (at App.js:11)
    in App (at src/index.js:10)
    in Router (created by BrowserRouter)
    in BrowserRouter (at src/index.js:9)

Consider adding an error boundary to your tree to customize error handling behavior.
Visit https://fb.me/react-error-boundaries to learn more about error boundaries.
logCapturedError @ react-dom.development.js:16911
react-dom.development.js:16911 The above error occurred in the <Link> component:
    in Link (created by Context.Consumer)
    in Route (created by NavLink)
    in NavLink (at Header.js:12)
    in nav (at Header.js:7)
    in Header (at App.js:12)
    in div (at App.js:11)
    in App (at src/index.js:10)
    in Router (created by BrowserRouter)
    in BrowserRouter (at src/index.js:9)

Consider adding an error boundary to your tree to customize error handling behavior.
Visit https://fb.me/react-error-boundaries to learn more about error boundaries.
logCapturedError @ react-dom.development.js:16911
react-dom.development.js:16911 The above error occurred in the <Link> component:
    in Link (created by Context.Consumer)
    in Route (created by NavLink)
    in NavLink (at Header.js:16)
    in nav (at Header.js:7)
    in Header (at App.js:12)
    in div (at App.js:11)
    in App (at src/index.js:10)
    in Router (created by BrowserRouter)
    in BrowserRouter (at src/index.js:9)

Consider adding an error boundary to your tree to customize error handling behavior.
Visit https://fb.me/react-error-boundaries to learn more about error boundaries.
logCapturedError @ react-dom.development.js:16911
react-dom.development.js:16911 The above error occurred in the <Link> component:
    in Link (at HomePage.js:8)
    in div (at HomePage.js:5)
    in HomePage (created by Context.Consumer)
    in Route (at App.js:14)
    in Switch (at App.js:13)
    in div (at App.js:11)
    in App (at src/index.js:10)
    in Router (created by BrowserRouter)
    in BrowserRouter (at src/index.js:9)

Consider adding an error boundary to your tree to customize error handling behavior.
Visit https://fb.me/react-error-boundaries to learn more about error boundaries.
logCapturedError @ react-dom.development.js:16911
react-dom.development.js:20106 Uncaught Invariant Violation: You should not use <Link> outside a <Router>
    at invariant (http://localhost:3000/bundle.js:3161:15)
    at Link.render (http://localhost:3000/bundle.js:27109:53)
    at finishClassComponent (http://localhost:3000/bundle.js:20040:31)
    at updateClassComponent (http://localhost:3000/bundle.js:19995:24)
    at beginWork (http://localhost:3000/bundle.js:20943:16)
    at performUnitOfWork (http://localhost:3000/bundle.js:24611:12)
    at workLoop (http://localhost:3000/bundle.js:24651:24)
    at renderRoot (http://localhost:3000/bundle.js:24734:7)
    at performWorkOnRoot (http://localhost:3000/bundle.js:25641:7)
    at performWork (http://localhost:3000/bundle.js:25553:7)

************************************************************************************************************************