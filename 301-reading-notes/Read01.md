## Component-Based Architecture

1. What is a “component”?
- Modular, portable, replaceable, and resusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface. All of that tech-speak means it is something that comes from the React library and can be referenced however and whenever in your code for certain functionality you need.
2. What are the characteristics of a component?
- Reusability, replaceable, not context specific, extensible(can be extended from existing components to provide new behavior), encapsulated, independent.
3. What are the advantages of using component-based architecture?
- Ease of deployment, reduced cost, ease of development, reusable, modification of technical complexity, reliability, system maintenance and evolution, independent. 

[For Reference](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

## Props

1. What is “props” short for?
- "properties." 
2. How are props used in React?
- They are used for passing data from one component to another. They are being passed in a uni-directional flow. Child elements cannot change them.
3. What is the flow of props?
- define an attribute and its value(data)>pass it to child components by using Props>render the Props Data

[For Reference](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0#:~:text=%E2%80%9CProps%E2%80%9D%20is%20a%20special%20keyword,way%20from%20parent%20to%20child)