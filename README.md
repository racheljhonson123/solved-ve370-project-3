Download Link: https://assignmentchef.com/product/solved-ve370-project-3
<br>
Cache memory is the top of the memory hierarchy that interacts with the CPU directly. Communications between CPU and the rest of the memory hierarchy are typically through cache. Simplified interfaces between the CPU and cache and between cache and the main memory are shown in the following structural diagram.

Assume the following properties of the memory:

<ul>

 <li>Byte addressable</li>

 <li></li>

</ul>

<table>

 <tbody>

  <tr>

   <td width="74"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Size of the main memory: 1024 bytes</li>

 <li>Size of the cache: 64 bytes</li>

 <li>Size of a block: 4 words</li>

 <li>Cache associativity: (a) Direct mapped; (b) 2-way associative</li>

 <li>Write technique: (1) write through; (2) write back</li>

 <li>Cache replacement policy: Least Recently Used (LRU)</li>

</ul>




When CPU needs to access a data/instruction in the memory, it sends a 10-bit address to the cache. If there is a hit in cache, CPU then reads/writes the cache memory. If there is a cache miss, cache should request the missing block from the main memory by sending the 10-bit address to the main memory. Then CPU should resend the same address to try again. For simplicity purpose, assume the main memory always has hit and latency of the main memory access is not considered.

Model the cache memory and main memory in Verilog HDL with combinations of (1)(a), (1)(b), (2)(a), and (2)(b) for cache associativity and writing mechanism. Write a testbench to act like a CPU to provide a sequence of addresses for reading or writing. Pre-load the main memory with randomly generated data by your team. Simulate the functions of the memory hierarchy with an appropriate Verilog simulator.

DELIVERABLES

Written report is OPTIONAL for this project. The entire project including all Verilog modules must be submitted in a zipped folder and clearly indicate which Verilog simulator has been used. Simulations for all four different combinations (for cache associativity and writing mechanism) must be separated and clearly indicated. All Verilog modules must be clearly commented to receive full marks. Screen shots and explanations of simulation results can be submitted in a PDF file if you think it will be helpful.




1




This is a group assignment. One submission for each group is needed. Your work must be submitted electronically to Canvas before the specified due date.