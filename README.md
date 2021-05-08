# Routing using react-router Part 3

- Navigating to Specific Blog
  - using Path Parameters
- Path Params
  - match

### API Calls
In General we make API Calls inside componentDidMount(). So that it doesn’t block render()
![image](https://user-images.githubusercontent.com/46521639/117536537-2963a800-b019-11eb-938e-296605a11dc6.png)
### Fetch
Fetch is a promise-based API which returns a response object. In the backend, we use snake_case for naming conventions

### third party packages (react-loader-spinner)
npm install react-loader-spinner –save
import Loader from ‘react-loader-spinner’
import "react-loader-spinner/dist/loader/css/react-spinner-loader.css";

### Route Props
When a component is rendered by the Route, some additional props are passed

1.match
2.location
3.history


### Match
The match object contains the information about the path from which the component is rendered.
