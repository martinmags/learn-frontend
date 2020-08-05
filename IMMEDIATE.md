# GENERAL
[TDY] JS BASICS
  [x] Closures: data defined outside a function is
      accessible inside the function due to lexical
      scoping. How it works is that the inner 
      function will keep looking outside its wrapper
  [x] Threading and Web APIs
    [x] setTimeout()
    [x] Promises: a representation of a success or failure of a
        function call. If the function call was successful
        (ex: api fetch) then proceed to do whatever with that 
        function's result. If failure then return some error msg.
    [x] callback: passing a function as an argument to 
        another function
  [x] is Case Sensitive
  [x] == equality, === equality and data type
  [x] protoypes
  [x] Modules (like classes, but not instantiable
      and modules are function-based)
  [x] Classes (instantiable objects)
[TDY] HTTP/HTTPS protocol
[ ] Review Data Structures
[ ] Review Algorithms
[ ] SQL Queries and Aggregate Functions

# REACT
[ ] Top-bottom approach (Take out pieces in your app.js 
    as u notice patterns)
[TDY] Learn Webpack
[?] MaterialUI Framework
[?] Emotion vs Styled Components
[ ] Redux and Redux Thunk
  [ ] Helpers: rematch and reselect
[TDY] PropTypes
[ ] Testing with Jest and Enzyme

[ ] this.state: mutable through this.setState({ someVar: 'val'});
     passable attributes to children components
[ ] this.props: immutable; passable attributes to children 
    components

[ ] Lifecycle methods

  [ ] Mounting: setups the component and renders to the DOM
    [ ] componentWillMount(): runs before component is rendered;
        not used too much because can't do much when component
        isn't rendered on DOM yet.
    [ ] componentDidMount(): runs after component is rendered on DOM;
        fetch data from APIs in here
    [ ] render():
  
  [ ] Update states and/or props: 
    [ ] componentDidUpdate(prevProps, prevState): 
      executed in response to a state or prop change on the DOM;
      normal use of where you would setState(); equivalent to
      useEffect() if we use functions instead.
    [ ] shouldComponentUpdate(nextProp, nextState): 
        helps optimize by only rerendering when a component 
        needs to rerender; runs before render
    [ ] render( ):


  [ ] Unmounting: clears the component when removed from DOM
    [ ] componentWillUnmount(): executed before removed from DOM;
        clear caches, cancel api calls, etc.

  [ ] Redux
    [ ] Store: global state accessible by all components
    [ ] Reducer: function that returns the state of the app
    [ ] Action: gives information about the Store.

TMR
6-7: Breakfast, Stocks
7-9: Look Through React documentation
9-10: Review Data Structures
10-11: Review Common Algorithms
11-12: Review SQL
12-1: Lunch and Shower
1-2: Learn Redux and Redux Thunk conceptually
2-4: Interview

UPDATED todo:
[Redux_Concept]
[React_Docs]
  [React_Lifecycle]
[Review_Data_Structure]
