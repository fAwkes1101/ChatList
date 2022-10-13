# ChatList
LRU Cache Implementation  
                                                                                                                            
⮞ Approach.                                                                                                                             
 • The idea is very basic that keep inserting the elements at the head.  
 • If the element is not present in the list the add it to the head of the list.                                                                                       
 • If the element is present in the list then move the element to the head and shift the remaining element of the list.                                                                                       

⮞ Two major operations in ChatList.                                                                                                                            
 • When we receive a new message it gets on top of the list.                                                                         
   If the message was already present in the ChatList it will get to the top and the messages below it will be shifted.
   If message was not present already in the list then it will only get to the top shifting all other messsages down.

 • When a message is to be deleted all the message below it shifts upwards.

⮞ Data Structure Used.                                                                                                                            
 • Doubly Linked List and HashMap.                                                                                                                             
 • The find, shift and delete operations could be performed in O(1) time complexcity.                                                                                                                                                                                                                                                          
  
![image](https://user-images.githubusercontent.com/86714900/194227716-dec2bba8-124b-4d18-aa27-7060676e3981.png)













