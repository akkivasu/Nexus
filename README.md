# Nexus
C library providing templates and associated functions for common data structures that aren't primitive to C.

1. nexList
2. nexStack
3. nexQueue
4. nexCList
5. nexDlist
6. nexDQueue
7. nexCQueue
8. nexTree
9. nexGraph

1.1 Functions on nexList
nexList(), isEmpty(), pushFront(), pushRear(), pop(), sort(), deleteEle(), deletePos(), deleteEleAll(), deleteAll(), EleAt(), posOf(), reverse();

1.2. Syntax
> nexList():
	nexList *<var_name> = nexList(e1, e2, ..., eN);
> isEmpty():
	isEmpty(<var_name>); //<var_name> must refer to the pointer in question
> pushFront():
	pushFront(<var_name>, e);
> pushRear():
	pushRear(<var_name>, e);
> pop():
	<datatype> <var_name1> = pop(<var_name>);
> sort():
	sort(<var_name>);
> deleteEle():
	deleteEle(<var_name>, e);
> deletePos():
	deletePos(<var_name>, p);
> deleteEleAll():
	deleteEleAll(<var_name>, e);
> deleteAll():
	deleteAll(<var_name>);
> eleAt():
	eleAt(<var_name>, p);
> posOf():
	posOf(<var_name>, e);
> reverse():
	reverse(<var_name>);
