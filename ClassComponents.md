JUst like regualr class but extend from React.Component

render() method needed in class based components.

when using constructor(props){
super(props);
} is needed.

states are craeted inside the constructor
can be created using this.state ={count:0,count2:0}
setting states this.setState({ count: 1 ,count2: 2})

react lifycycle -google react lifecycle diagram
-Two phases
--- render phase
--- commit phase
1-constructor() for states
2- render() for jsx
if child comp present in render.
-child consructure()
-child render()
-child componentDidRender()
3- componentDidMount() for api calls
