# test

This is the file


class Node:
    def __init__(self, value):
        self.value = value
        self.next = None

class LinkedList:
    def __init__(self):
        self.head = None
    
    def push(self, newNodeValue):
        newNode = Node(newNodeValue)
        newNode.next = self.head
        self.head = newNode
    
    def reverse(self):
        