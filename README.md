# Objective of Repo
Learning RTK.
# About Redux
What Is "Redux"?<br/>
Redux is really:<br/>
A single store containing "global" state<br/>
Dispatching plain object actions to the store when something happens in the app<br/>
Pure reducer functions looking at those actions and returning immutably updated state<br/>
![flow of RTK](ReduxDataFlowDiagram-49fa8c3968371d9ef6f2a1486bd40a26.gif)
What Does Redux Toolkit Do?<br/>
While these were the patterns originally shown in the Redux docs, they unfortunately require a lot of very verbose and repetitive code. Most of this boilerplate isn't necessary to use Redux. On top of that, the boilerplate-y code lead to more opportunities to make mistakes.<br/>
We specifically created Redux Toolkit to eliminate the "boilerplate" from hand-written Redux logic, prevent common mistakes, and provide APIs that simplify standard Redux tasks.<br/>
# Jargons used in RTK
`store` - universal store where all the values are stored and can be accessed and updated by anyone.<br/>
`reducers` - all the actions are done via reducers.<br/>
`useSelector`- directly talks to the store.<br/>
`useDispatch` - updates specific reducers. <br/>
# Installation
Refer to ReduxToolkit installation guide  <a target="_blank" href="https://redux-toolkit.js.org/introduction/getting-started">here</a>