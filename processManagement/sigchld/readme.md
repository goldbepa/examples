This example demonstrates the use of sigchld to know about the death of the child. As you can see one mechanism is to attach a sigchld handler and in that handler wait for the children that just caused the sigchld to be thrown.