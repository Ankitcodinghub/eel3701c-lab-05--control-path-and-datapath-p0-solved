# eel3701c-lab-05--control-path-and-datapath-p0-solved
**TO GET THIS SOLUTION VISIT:** [EEL3701C LAB 05- Control Path and Datapath P0 Solved](https://www.ankitcodinghub.com/product/eel-3701c-digital-logic-computer-system-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124498&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEL3701C LAB 05- Control Path and Datapath P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
LAB 05: Control Path and Datapath

Objectives:

The main objectives of this lab are:

– Understand the components of the Datapath

– Designing a simple ALU

– Specifying Controller

– Finally implement and simulate the behavior of simplified processor

Introduction:

In this lab, you will design a small processor which has an ALU. The ALU can be configured to several Assignment Project Exam Help

when required. In addition, the controller sets the operation in the ALU by extracting the received

Prelab Questions:

1. A left shift is equivalent to which mathematical operation? (Add, subtract, multiply, divide, etc.)

2. A right shift is equivalent to which mathematical operation?

3. What is the difference between a logical right shift and an arithmetic right shift? When must an arithmetic right shift be used to preserve algebraic correctness?

4. How many possible distinct operations can a CPU with a single 4-bit instruction field and two 2bit register fields perform?

For example, a single operation could be ADD R1, R2. A second operation could be

ADD R2, R1. A third operation could be ADD R1, R1. A fourth operation SUB R3, R2. Based on the given parameters, how many possible operations are there?

There are two prelab problems. Submit your prelab report before your lab session begins.

There are no video demos for this lab.

Pre-Lab Problem 1: ALU Design

Figure 1 illustrates the architecture of a 4-bit ALU that must be designed for a simplify processor called the G-CPU processor.

Assignment Project Exam HelpFigure 1: Schematic ALU representation

(Note: only 4/8 functions are shown in the right block diagram)

OP Operation Description Meaning

000 2CMP 2’s Complement F = 2’s Complement of A

001 AND Logical AND F = A AND B

010 AddOR WeChatLogical OR powcoderF = A OR B

011 ADD Binary Addition F = A + B + Cin; Cout = Carry of sum

100 OUTA Output A F = A

101 OUTB Output B F = B

110 SLL Shift Left Logical F = A &lt;&lt; 1

111 SRL Shift Right Logical F = A &gt;&gt; 1

Table 1: ALU Operations. Note: Let Cout be a don’t care OP != ADD.

1. Provide the VHDL implementation of the ALU according to the block diagram. Recall that multiplexers are case differentiations that can be represented with “if then/else,” “case/when,” or “when/else” statements. Processes are permissible.

2. Create an annotated simulation to prove the correctness of your design.

To implement the shift operator, use the concatenation operator &amp;. For example, to implement a leftlogical shift:

For your deliverable, provide the VHDL implementation and annotated simulation of the above.

Pre-Lab Problem 2: G-CPU Datapath Design

In the second part of this lab, the ALU designed in Problem 1 will be used to build a datapath. The datapath is connected to an input bus to read externally inputted operands, and an output bus to send results out.

Figure 2: G-CPU Datapath

1. Provide the VHDL implementation of the data path design. Analyze Figure 2 carefully and complete the given template of GCPU_Datapath.vhd.

2. Create an annotated simulation to prove the correctness of your design.

For your deliverable, provide the VHDL implementation and annotated simulation of the above.

There is no prelab demo. Just simulations.

In-Lab Problem 3: G-CPU Control Path

The purpose of the controller is to take an instruction as an input and guide the datapath to execute said instruction. The reading of the operands from INPUT and the storage of the results into registers must all be controlled by your controller.

As shown on Figure 3, your controller should have three inputs: START, COUT, and the 5-bit machine code. (Remember: clocks and resets are implied). Note that COUT is an input here because it allows for us to put two GCPUs in a row and connect the COUT of the ALU to the COUT of the controller.

It should have five outputs: SEL1, SEL2, CIN, OP, and DONE.

Figure 3: Control and Datapath for the G-CPU. For this part, you will create the Controller.

INST Opcode Meaning

000 LOAD DEST = IN_OP

001 TAB If DEST == RegA, RegA = RegB

Else if DEST == RegB, RegB = RegA

010 AND DEST = RegA AND RegB

011 OR DEST = RegA OR RegB

100 ADD DEST = RegA + RegB

101 SUB DEST = RegB – RegA; A is not preserved

110 SRL DEST = Logical Right Shift(A)

111 OUT Output Bus = DEST

DEST Register

00 RegA

01 RegB

1- Nothing

Table 4: Interpretation of DEST.

Table 3: Possible INST values and their meanings

Your controller should take the form of a state machine. Below is only a small portion of an Algorithmic State Machine diagram you must complete. An ASM is like a mix between a Moore and a Mealy machine, in which outputs can depend on either state, inputs, or both.

Your controller should not begin execution of a malformed instruction; an instruction is malformed if DEST is pointing to Nothing. But you can assume that an instruction will not become malformed after execution begins (i.e., you leave the Decode state).

Figure 4 – ASM for the Control Path Note updates to the legend, and transitions near Decode Hint: For the OUT instruction, you should use the syntax from the legend for the OP output

1. Finish the preceding ASM diagram for all defined instructions. Optionally, the draw.io file used to create the above is provided if you wish to use it. Use https://draw.io to edit it.

3. Create an annotated simulation to prove the correctness of your design.

For your deliverable, provide the ASM, VHDL implementation and annotated simulation of the above.

In-Lab Problem 4: G-CPU Design

You have implemented the different modules in the GCPU. Now, you need to write a top-level file to complete the implementation. Carefully observe Figure 3 and complete a new VHDL file Lab4.vhd. This should only be an instantiation of the two modules you created before, the datapath and the control path.

You should have two inputs: a 9-bit machine code and START.

You should have two outputs: Output (from the datapath) and DONE.

(Note, output and input are reserved keywords in VHDL and should NOT be used as a name)

The format of the 9-bit machine code looks like this:

INST [Bits 8-6] IN_OP [Bits 5-2] DEST [Bits 1-0]

What the G-CPU should do Operand Destination register

3 bits 4 bits 2 bits

Refer to Table 3 IN_OP should be placed on INPUT Refer to Table 4

Program: X = Assignment Project Exam Help((A + B) / 4 + B) OR 3

1. Create the VHDL implementation of Lab4.vhd. No template is provided for this.

Show X by using the OUT instruction once the calculation is completed.

3. Answer: Give one example of a combination of inputs A and B that would cause an

For your deliverable, provide the VHDL implementation, annotated simulation, and answer from above. No video demos for this lab.
