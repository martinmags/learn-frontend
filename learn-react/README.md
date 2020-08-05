# SKILLS LEARNED
================
Basics of Components
# Note: emmet shortcut for react function component boilerplace is 'rfce'
Passing down Props 
File Structure
React Hooks: Adding state to stateless functions
Tailwind: a React CSS Framework (JS configurable)
FontAwesome: Icon package
Conditional Rendering: Show some html depending on some conditions
React-Spring: animation transitions
Single Page Application (SPA) - Changing Components in the 
  same page without needing to refresh
react-router-dom: Manage routing and what components get displayed at each page
  Whatever is inside the Switch component is what components changes
  Anything outside the Switch component i.e. Header and Footer components,
    will not be refreshed upon redirection. 
# Note: Link components must be within a Router component
# Note: Route components must be within a Route component (for url redirecting)
mockapi.io if you wanna play around with api
axios: http library (requests)
useEffect(()=>{ 'stuff' }, [url]): Only run stuff IF 'url' changes
useParams() from react-router-dom: Returns all url parameters


# File Structure
./public
  /index.html:  Shipped to client; binds entire react 
                app into div id=root

./src
  /index.js:    Entry point into the REACT app
  /app.js:      The main entry point

# Components
All components must return ONE wrapper element such as a <div>
Function components are stateless whereas class components maintain
state.
# Pushing an element to the bottom of a dynamic rendering page
className="min-h-screen"
# Props
Pass down data from component to component
HelloWorld Component: <h1> Hello {name} </h1>
App Component: <HelloWorld name="Animal"/>

# Hooks:
# Ex: const [count, setCount] = useState(0)
useState('initial value'): initialize hook with an intial value
update state: setCount (in above ex) is equivalent to class' setState({})
useEffect(): similar to componentDidMount and componentDidUpdate