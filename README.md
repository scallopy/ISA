# Instruction Set Architecture (ISA)

## Ultra Super Calculation Computer

Write the code for the CPU that will support the functions required by the ISA. Based on the design specification in the code editor window, you know you are asked to perform five functions:

- Add

- Subtract

- Multiply

- Divide

- Display a history of calculations

These five functions will also require several other support functions to be written as well so that we can access different parts of our computer hardware. We must also be able to:

- Read and split up our incoming data

- Store a binary number to a register

- Access what is stored in the register

- Allocate some registers for a ‘history’ of our calculations

- Store/Load from the history when needed


### …create a new repository on the command line

```
echo "# ISA" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:scallopy/ISA.git
git push -u origin main
```
