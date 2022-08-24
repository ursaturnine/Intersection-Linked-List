# Intersection-Linked-List
Given the heads of two singly linked-lists `head_a` and `head_b`, return the value of the node at which the two lists intersect. If the two linked lists do not intersect, the function should return `None`.

For example, the following two linked lists begin to intersect at 5.

`linked_list_a: 3 -> 4 -> 5 -> 6 -> 7`

`linked_list_b: 1 -> 2 -> 5 -> 6 -> 7` 


The following two linked lists do _not_ intersect at all because while the node with value 5 is in the same place, the subsequent nodes are different.

`linked_list_a: 3 -> 4 -> 5 -> 6 -> 7`

`linked_list_b: 1 -> 2 -> 5 -> 4 -> 3` 



## Getting Started

As usual with a python project, create a virtual environment:

```
python3 -m venv venv
```

Then activate the virtual environment

```
source venv/bin/activate
```

Then install the required packages.

```
pip install -r requirements.txt
```
