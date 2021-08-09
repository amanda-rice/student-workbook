# How to use Props in Vue
## What are props?
Props allow us to pass information between components. They must be passed from parent to child and cannot be sent the other way. The child cannot modify this info.
## What are props used for?
We use props to send data from a parent component to its child. They are only updated by the parent.

## Where can props be used or accessed?
They are accessed by the child component they are sent to and within the parent. In the child, they can be accessed in the template with the double curly braces and the prop name. They can also be used outside the template if called with this.name.

[NASA Vue](https://github.com/amanda-rice/nasa-vue)