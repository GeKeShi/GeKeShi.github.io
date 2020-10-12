# Is Network the Bottleneck of Distributed Training?
Proceedings of the Workshop on Network Meets AI & ML

- The famous analysis from [OpenAI] [1] shows that the amount of computing needed to train the state-of-the-art model doubles every 3.4 months, while in comparison, the number of transistors on a chip only doubles every 18 months even when Moore’s law is still effective.
- The dream for every scaleout system is linear scalability. That is, given that the throughput of a single device is $T$, the throughput of a system with $n$ devices should be $T$. Let the throughput actually achieved by the system with 𝑛 devices be $𝑇_n$ . We define the scaling factor as 
$$
scaling\ factor = \frac{T_n}{nT}
$$

[1]: “AI and Compute.” https://openai.com/blog/ai-and-compute/.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxNTI3NjMwNV19
-->