# 8086_microprocessor
## reference url : https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/f--fp--fill-memory-
- a : to write a code

  a
  mov ax,05
  mov bx,03
  add ax,bx
  int 03 // interupt to break 
  // or int 21
- c : to compare value

  c 0101 L 1 0103
  
- d : dumb mermory content

  d 100
  
- e 100 05

- f : fill memory in bulk

  f 0100 L4 20

- g : go command 

  //running process
  
  g 100
  
- h : add sub result of hex numbers

  h 3 2
  


 

  
  
