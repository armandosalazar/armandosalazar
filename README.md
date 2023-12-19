```asm
global _main

section .text
_main:
    mov     rax, 0x2000004
    mov     rdi, 1
    mov     rsi, msg
    mov     rdx, msg.len
    syscall

    mov     rax, 0x2000001
    mov     rdi, 0
    syscall
section .data
    msg: db "Hi! <3",10
        .len: equ $ - msg
```

<!--
**armandosalazar/armandosalazar** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
