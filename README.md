

    
# ReactTestGenie
<img  src="https://github.com/jtwray/ReactTestGenie/assets/42871401/45630c1f-98ea-4bc6-b44c-1211bb95377c" style="width: 300px; height: auto;"><img src="https://github.com/jtwray/ReactTestGenie/assets/42871401/353e95de-920e-4464-a294-96e05020fcd0" style="width: 300px; height: auto;" />



 
ReactTestGenie is a tool for generating unit tests for single React components in the browser. It leverages the power of a Language Model to suggest user interactions and happy paths, helping developers create comprehensive test suites for their React applications more efficiently.

ReactTestGenie is a tool for generating unit tests for single React components in the browser. It leverages the power of a Language Model to suggest user interactions and happy paths, helping developers create comprehensive test suites for their React applications more efficiently.

## Features

- **Automatic Test Generation**: Input your React component code and let ReactTestGenie suggest user interactions and test scenarios.
- **Customizable Suggestions**: Select and customize the suggested test scenarios according to your specific testing needs.
- **Code Generation**: Generate Jest or React Testing Library unit test code based on the selected scenarios.
- **In-Browser Interface**: All functionality is accessible through a user-friendly web interface, making it easy to integrate into your development workflow.
- **Copy-Paste Convenience**: Copy generated test code directly from the browser for seamless integration into your project.

## Getting Started

To use ReactTestGenie, follow these steps:

1. Clone this repository to your local machine.
2. Open the `index.html` file in your web browser.
3. Input your React component code into the designated area.
4. Review the suggested test scenarios and select the ones you want to include in your unit tests.
5. Customize the selected scenarios as needed.
6. Click the "Generate Tests" button to generate the unit test code.
7. Copy the generated test code and integrate it into your React project's test suite.

## Usage Examples

Here's a quick example of how to use ReactTestGenie:

```jsx
// Sample React Component
import React from 'react';

const Button = ({ onClick, children }) => (
  <button onClick={onClick}>{children}</button>
);

export default Button;
