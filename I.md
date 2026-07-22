# Slide 1: Repetition „Memory“

- Header: **Repetition „Memory“**
- Core Review Questions:
  - What is the main task of a memory?
  - Which basic reasons for remembering do you know?
  - How would you implement fogetting? (Typo: fogetting)
  - What is a name?
  - What are names used for?
  - Why are names so importand for remembering? (Typo: importand)
  - How is the memory related to time logic and space logic?

### Conceptual Explanation

The presenter opens the "I Mind" module by reviewing the previous module ("H Memory"). Memory's core tasks are to persist (write) and recall (read) data, and to algorithmically prune dead data (forgetting). Names act as fast, zero-compute pointers for complex entities. 

This sets up the transition: If "Memory" is the hard drive where data sits at rest, what is the processor that actively runs algorithms on that data? That processor is the "Mind."

---

# Slide 2: Title and Administration

- Header/Title: **Strong Artificial Intelligence**
- Module Name: **I Mind**
- Subtitle: **Thought Centre**
- Presenter: **Prof. Dr. Dr. h. c. Robert Grebner**
- Institution: **Technical University of Applied Sciences, Würzburg**
- Date: 2026-06-12

### Conceptual Explanation

This is the title slide for the ninth module in the seminar, "I Mind." 
The subtitle "Thought Centre" defines the Mind's role. It is the active CPU (Central Processing Unit) of the intelligent agent. It is the place where static data from Memory is loaded into volatile state (thoughts) so logic operations can be run on it.

---

# Slide 3: The Brain (Hardware Specs)

- Header: **Strong Artificial Intelligence**
- Visual: A Brain graphic with literal hardware specifications:
  - **86 Billion Neurons**
  - **100 Trillion Connections**
  - **> 2 Million years evolution**
  - **35,000 to 100,000 years old** (modern homo sapiens configuration)
  - **1.3 kg +/-**
  - **20 Watt**

### Conceptual Explanation

This slide presents the human Brain purely as a piece of biological hardware. The most striking metric here is **"20 Watt."** The human brain runs a 100-trillion-parameter neural network on less electricity than a dim lightbulb. 

### Why this matters

For AI engineering, this is the ultimate benchmark. Currently, training and running an LLM with 1 trillion parameters requires massive server farms pulling megawatts of power. The human brain proves that a hyper-efficient, 20-Watt AGI architecture is physically possible in this universe.

---

# Slide 4: Workshop „Mind“

- Header: **Workshop „Mind“**
- Core Brainstorming Prompts:
  - What is the a mind? (Typo: the a)
  - What is the main task of a mind?
  - What are tasks of the mind in respect to our daily life?
  - What has the mind to do with writing?
  - What is writing?
  - What do we think about, when we are writing?
  - What is a thought?
  - What is the difference between thought and information?

### Conceptual Explanation

This workshop forces the audience to separate the "Mind" (software) from the "Brain" (hardware). 

The prompts tease apart the concept of a "thought." What is the difference between a thought and raw information? Information is static data sitting in memory. A "thought" is information that has been loaded into active, volatile execution space. Writing is just the physical manifestation (the logging) of active thoughts onto a physical carrier. 

---

# Slide 5: Agenda — I Mind

- Header: **I Mind**
- Agenda Items:
  1. **Thought** $\rightarrow$ *Mental Substance*
  2. **Understanding** $\rightarrow$ *Associating*
  3. **Reasoning** $\rightarrow$ *Decider*
  4. **Learning** $\rightarrow$ *Growth*
  5. **Logic** $\rightarrow$ *Right or Wrong*
  6. **Initiating** $\rightarrow$ *Motion Start-up Setter*
  7. **Conclusion** $\rightarrow$ *Processing Core*

### Conceptual Explanation

This agenda outlines the complete operational lifecycle of a CPU (the Mind).
1. It defines the raw data type it processes (**Thought** / Volatile State).
2. It executes graph traversals (**Understanding**).
3. It runs decision trees (**Reasoning**).
4. It updates the database (**Learning**).
5. It applies boolean constraints (**Logic**).
6. It compiles the final output and sends an execution command to the hardware/body (**Initiating**).

### Why this matters

If you want to code an autonomous AGI, this slide is the exact event loop you must program. `while(true) { load_thought(); understand(); reason(); learn(); validate_logic(); initiate_action(); }`. 

---

# Slide 6-7: Thought (Mental Substance)

- Header: **1. Thought**
- Matrix (Slide 7):
  - **What is a Thought?** $\rightarrow$ *Aware Information Just Processing.*
  - **Where are Thoughts?** $\rightarrow$ *Mind‘s eye.*
  - **What is the Smallest Possible Thought?** $\rightarrow$ *One Entity.*
  - **How Many Thoughts Can We Have in Parallel?** $\rightarrow$ *?*

### Conceptual Explanation

These slides define the core "substance" of the Mind. A thought is defined as "Aware Information Just Processing." This means a thought is simply data that is currently being executed by the CPU. The "Mind's Eye" is the volatile RAM where this processing happens. 

The most important computer science rule here is: **The smallest possible thought is One Entity**. You cannot think about half of a variable. You must load a complete, discrete entity from memory to process it. The question mark regarding parallel processing hints at the single-threaded bottleneck of human consciousness.

### Why this matters

This defines the scope of the **Context Window** in an AI. The Mind's Eye (RAM) can only hold a certain amount of "thoughts" (tokens/entities) at once. While a computer can run thousands of parallel threads, the core "aware" logic engine must handle discrete, intact entities.

---

# Slides 8-9: Thought — Highlighted Information

- Header: **1. Thought**
- Subtitle: **Highlighted Information**
- Core Visual:
  - A Knowledge Graph mapping the spatial layout of a castle (`main door`, `side doors`, `towers`, `bridge` connected by `left/right/front/back` edges).
  - In Slide 8, the `main door` node has a massive glowing highlight ring around it.
  - In Slide 9, the highlight ring jumps to the `bridge` node.

### Conceptual Explanation

These slides visually demonstrate what "Thinking" actually is at a mechanical level. 

The entire graph of the castle sits in Memory. A "Thought" is simply the active highlight (the cursor, or the active execution thread) jumping from node to node across the graph. When you "think" about the main door, that specific node is loaded into the active Mind's Eye. When you "think" about the bridge, the highlight shifts. The graph structure itself doesn't change during a thought; only the active pointer changes position.

### Why this matters

In software engineering, this perfectly visualizes a **Graph Traversal Algorithm**. The mind is a cursor moving along associative edges in a database.

---

# Slide 10-12: Understanding (Associating)

- Header: **2. Understanding**
- Subtitle: **Associating**
- Core Matrix (Slide 12):
  - **What is Understanding?** $\rightarrow$ *Taking Description/Explanation to Form Consistent Concepts.*
  - **What is the Result of Understanding?** $\rightarrow$ *Knowledge.*
  - **What Information is Needed?** $\rightarrow$ *Information Related to the Concept that is not Understood.*
  - **What is Changed by Understanding?** $\rightarrow$ *The Information Network of the Memory.*

### Conceptual Explanation

The second step in the Mind's lifecycle is "Understanding." 
Understanding is defined mechanically: It is the process of receiving an external description, finding a gap or inconsistency in your internal Concept schema, and permanently drawing new associative edges in your memory graph to fix the inconsistency. The physical result of this process is called **"Knowledge."** 

Therefore, "Knowledge" is not just raw data. Raw data is Information. Knowledge is information that has been successfully wired into a consistent graph structure (Concept) that the system *Understands*. 

### Interpretive note

- The typos *"live"* (life) and *"knoledge"* (knowledge) from Workshop Slide 11 are preserved from the original text.

---

# Slide 13: Understanding Example — Time Machine

- Header: **2. Understanding**
- Subtitle: **Example Time Machine**
- Core Matrix:
  - **What is a Time Machine?** $\rightarrow$ *Moving our Brain and/or Body in the Time.*
  - **What Restrictions do Time Machines have?** $\rightarrow$ *...*
  - **How can you Build a Time Machine?** $\rightarrow$ *...*
  - **Why are Time Machines not Build yet?** $\rightarrow$ *High Complexity! Lack of Technology!*

### Conceptual Explanation

This slide proves that the Mind can build schemas (Concepts) for things that do not physically exist in reality. 
We can "Understand" a time machine. The mind simply takes the native concepts of `Movement`, `Body`, and `Time`, and logically connects them with new edges. Even though the "How to Build it" variables are totally blank (uncomplete concepts), the central `is_a` concept of a Time Machine exists perfectly well in the mental graph.

### Why this matters

This is the origin of **Creativity and Generation**. An AI doesn't need to observe something physical to "understand" it. It just needs to logically associate existing variables in novel ways. This is how Generative AI creates images of objects that don't exist.

---

# Slide 14-16: Reasoning (Decider)

- Header: **3. Reasoning**
- Subtitle: **Decider**
- Core Matrix (Slide 16):
  - **What is Reasoning?** $\rightarrow$ *Gaining new Insights/Concepts out of Known Concepts.*
  - **What is it Used for Externaly?** $\rightarrow$ *Decision Making, Action Plans.*
  - **What is it Used for Internaly?** $\rightarrow$ *Learning.*
  - **Precondition?** $\rightarrow$ *Logic.*

### Conceptual Explanation

The third step in the Mind's lifecycle is "Reasoning." 
If *Understanding* is drawing lines based on external descriptions, *Reasoning* is drawing lines entirely on your own. It is the process of generating new insights purely by traversing known concepts inside the brain, without any new physical input. 

Internally, reasoning generates new learning (new edges). Externally, reasoning is used to decide between paths and build Action Plans. The absolute prerequisite for this process to work without crashing is strict adherence to **Logic**. 

### Why this matters

This is the definition of **Inference** in Artificial Intelligence. A system executing reasoning (an inference engine) takes known graph structures and infers completely new, unobserved relationships. If A=B and B=C, the inference engine independently generates the insight A=C.

### Interpretive note

- The typos *"Externaly"* and *"Internaly"* are preserved from the original text.

---

# Slide 17-18: Learning (Growth)

- Header: **4. Learning**
- Subtitle: **Growth**
- Core Matrix:
  - **What is Learning?** $\rightarrow$ *Enlarging the Knowledge Base (Known Concepts).*
  - **Where Comes the Information From?** $\rightarrow$ *Self Experience or Others Experience.*
  - **How is it Done?** $\rightarrow$ *Understanding and Reasoning.*
  - **Where is the Learned Stored?** $\rightarrow$ *(Subjective) Memory.*

### Conceptual Explanation

The fourth step is "Learning," which the presenter defines as "Growth."
Mechanically, Learning is nothing more than writing the outputs of "Understanding" and "Reasoning" into permanent Memory. If Reasoning draws a new logical edge between two nodes in RAM, "Learning" is the `commit()` command that permanently saves that new edge into the storage database. Because learning is based on an individual agent's unique experiences and internal reasoning, the resulting memory is highly *Subjective*.

### Why this matters

This clarifies the difference between Inference (Reasoning) and Training (Learning) in AI. An LLM can "reason" in its context window (RAM), but when the context window is cleared, the AI forgets the insight. True "Learning" only happens when the model's weights (the subjective memory database) are permanently updated.

---

# Slide 19-23: Logic (Decider)

- Header: **5. Logic**
- Core Concepts (Slide 21):
  - **Basic Logics**: Naming, Placeholder, Abstraction, Transitivity, Exclusivity.
  - **Complex Logics**: Temporal logic, Spatial logic, Concepts, Action plans.
- Historical Context (Slide 22):
  - Credits the philosopher **Chrysippos** (280-210 B.C.) for creating the two-valued axiomatic propositional logic (true/false, AND/NOT/IF/ELSE, transitivity). 
- Logical Domains (Slide 23):
  - **Time Logic**: before, after, overlapping.
  - **Number Logic**: greater than, less than.
  - **Space Logic**: left, right, overlapping, distance.

### Conceptual Explanation

The fifth step is "Logic." Logic is the absolute rule engine that governs *how* the Mind is allowed to draw edges during Understanding and Reasoning. 
The presenter credits Chrysippos with defining `IF`, `AND`, `OR`, `ELSE`, and `NOT`—the exact Boolean operators that govern all modern computer code. 
Slide 23 shows that this core Boolean logic can be mapped onto specific domains. "Before" and "After" are just logical constraints applied to the Time primitive. "Left" and "Right" are logical constraints applied to the Space primitive. 

### Why this matters

This is the foundation of **Symbolic AI and Rule Engines**. An AI cannot reason safely without strict constraints. If an AI doesn't have a rigid engine enforcing "Space Logic" (e.g., an object cannot be left of A and right of A simultaneously), its spatial reasoning will hallucinate and crash. 

### Interpretive note

- The typo *"Hypothentical"* (Hypothetical) is preserved from the original text.

---

# Slide 24-32: Applying Logic

- Header: **5. Logic**
- Subtitle: **Example: Castle / Missing View Point**
- Core Visual Flow:
  - Slides 24-26 show the castle graph with missing information.
  - Slide 27 asks: **WHERE is the View Point?**
  - Slides 28-29 show the graph resolving by introducing a `view point` node that anchors the spatial logic (left/right/front/back) relative to the observer.
- Exclusivity (Slide 30):
  - "I cannot place myself where another entity already occupies space."
- Naming & Time Logic (Slide 32):
  - "Gulf of Mexico ? - 2025-01-19" $\rightarrow$ "Gulf of America 2025-01-20 - ?"

### Conceptual Explanation

These slides show how Logic actively resolves errors in the Mind. 
Spatial relationships (Left/Right) make zero sense without a relative View Point. The Mind uses logic to deduce that a View Point must exist, and injects it into the graph to make the math work. 
Slide 32 shows Time Logic overriding Name Logic. An entity's name can change at a specific timestamp (e.g., the Gulf of Mexico being renamed on 2025-01-20). The logical engine must track the `StartTime` and `EndTime` of the name to maintain a consistent reality. 

### Why this matters

This demonstrates **State Management and Collision Detection**. In a 3D video game or robotics simulation, the physics engine uses "Exclusivity Logic" to prevent two hitboxes from occupying the same coordinates. It uses "Time Logic" to track state changes over the simulation lifecycle.

---

# Slide 33-34: Initiating (Motion Start-up Setter)

- Header: **6. Initiating**
- Subtitle: **Motion Start-up Setter**
- Core Matrix:
  - **What is Initiated?** $\rightarrow$ *Motion, Speech and Thinking Acts.*
  - **Why is Something Initiated?** $\rightarrow$ *Impressions are Hurting our Values.*
  - **What Helps?** $\rightarrow$ *Action Plans.*
  - **Challange?** $\rightarrow$ *Immediate and Intermediate Feedback by Senses.* (Typo: Challange)

### Conceptual Explanation

The final active step in the Mind's lifecycle is "Initiating." 
Once the CPU has loaded the thoughts, understood the environment, reasoned a solution, and validated it with logic, it must actually *do* something. 
Action is always initiated because an external impression conflicts with internal Values (causing "hurt" or a negative reward). The mind loads an "Action Plan" to fix the discrepancy, and sends the execution commands to the hardware (Motion, Speech, or further Thinking). As it executes, it requires a continuous feedback loop from the sensors to ensure the action is working. 

### Why this matters

This is the exact control loop for **Robotics and Autonomous Agents**. The AI detects a negative state (e.g., battery low). It reasons a path to the charger. It initiates a `move()` command to the wheels. It uses immediate feedback (cameras/LiDAR) to adjust its path in real-time until the value is satisfied.

---

# Slide 35-37: Conclusion

- Header: **7. Conclusion**
- Core Takeaways:
  - The Mind is the central unit (CPU) where thoughts and thinking take place.
  - Understanding, reasoning, learning, and initiating are the main tasks.
  - Without logic, the mind could not work properly.
  - The mind gives commands to act and permanently observes the feedback for control and correction.

### Conceptual Explanation

The final slide synthesizes the entire module. The Mind is simply a processor running a continuous `while(true)` loop. It takes inputs, processes them through strict logical constraints, learns from the results, and initiates outputs to correct the environment, constantly monitoring the feedback.

This concludes the theoretical architecture of the Mind. The "I Mind" module proves that human cognition can be cleanly mapped to standard Computer Science architectures (CPU, RAM, Graph Search, Boolean Logic, Control Loops).

### Interpretive note

- Slide 37 is the final "Thank You" slide.
