---
layout: post
title: Linked Lists
---
Linked List, like arrays, is a linear structure of data. Unlike arrays, linked list elements are not stored in the contiguous location ; using pointers, the elements are linked.

Linked Lists are better because:

  1) Dynamic size 
  
  2) Facility of insertion / deletion

To Insert something:

def push(self, new_data):

    new = Node(new_data) 
    
    new.next = self.head
    
    self.head = new

![_config.yml]({{ site.baseurl }}/images/Linkedlist.png)
