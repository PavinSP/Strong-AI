# Slide 1: Title and Administration

- Header/Title: **Strong Artificial Intelligence**
- Module Name: **H Memory**
- Subtitle: **Persistencer**
- Presenter: **Prof. Dr. Dr. h. c. Robert Grebner**
- Institution: **Technical University of Applied Sciences, Würzburg**
- Date: 29.05.2026

### Conceptual Explanation

This is the title slide for the eighth module in the seminar, "H Memory." 
The subtitle "Persistencer" (a neologism for a system that persists data) indicates the core function of Memory. The previous modules established how the mind builds and learns "Concepts" (templates/schemas). This module will explain the architecture of how the brain stores (persists) those concepts and later retrieves them for action.

---

# Slide 2: Repetition „Concept“

- Header: **Repetition „Concept“**
- Core Review Questions:
  - What is a primitive, native and derived concept?
  - What is the counterpart paradigm?
  - What is not a concept?
  - How can concepts be presented? 
  - Why is hourse not a hourse?
  - How are concepts helping us to be curious?

### Conceptual Explanation

As is customary, the presenter begins by reviewing the previous module ("G Concept"). 
This locks in the dependency chain. 
- A **Concept** is an abstract schema/template (not the physical entity itself, hence why a physical horse is not the mental concept of a "hourse"). 
- It scales from **primitive** (names/variables) to **native** (single associations governed by the **counterpart paradigm**) to **derived** (complex graphs). 
- Concepts drive curiosity because the brain naturally wants to fill missing variables in a schema.

This review sets the stage: Now that we know *what* a concept is, we need to know *where* and *how* it is stored.

### Interpretive note

- The typo *"hourse"* (instead of horse) is preserved from the previous module's slide of the same name.

---

# Slide 3: Workshop „Memory“

- Header: **Workshop „Memory“**
- Core Brainstorming Prompts:
  - How and when do we remember experiences or impressions from the past?
  - Which thoughts are coming from alone? And why?
  - How is the access to persisted information implemented?
  - Is persisted information information?
  - How can we remember things that we will do in the future?
  - In which parts or segments would you divide our memory?
  - Which information would you put into which segment?

### Conceptual Explanation

This workshop challenges the audience to deconstruct their intuitive experience of "Memory" into a mechanical, software-like architecture. 

The prompts push the audience to realize that Memory isn't just a passive filing cabinet. It is an active retrieval system. Questions like "How is access to persisted information implemented?" force students to think about database querying. 
The most fascinating prompt is "How can we remember things that we will do in the future?" This hints that "Memory" is not just for the past; it is the storage medium for future Action Plans. 

### Why this matters

For AI engineering, this workshop is basically an architecture planning session for an **Agentic Memory System**. Should memory be divided into segments (e.g., Short-term vs. Long-term / RAM vs. Hard Drive)? How do we index memories for fast retrieval? If we want an AGI, we must build a memory system that answers all these prompts algorithmically.

---

# Slide 4: Agenda — H Memory

- Header: **H Memory**
- Agenda Items:
  1. **Task** $\rightarrow$ *Persistencing and Recalling*
  2. **Remembering** $\rightarrow$ *Associating*
  3. **Forgetting** $\rightarrow$ *No Usage*
  4. **Primitives** $\rightarrow$ *Name Time Space*
  5. **Segments** $\rightarrow$ *Allocation of Knowledge*
  6. **Implementation** $\rightarrow$ *Database*
  7. **Conclusion** $\rightarrow$ *Core*

### Conceptual Explanation

This slide outlines the structural roadmap for Module H, mapping the lifecycle of stored data.

The presenter breaks the module down into a strict logical progression:
1. It defines the core **Task** of memory (writing/persistencing and reading/recalling).
2. It defines the mechanics of **Remembering** (using associative links).
3. It defines the mechanics of **Forgetting** (pruning unused data).
4. It categorizes the **Primitives** used to index memories (Name, Time, Space).
5. It breaks the memory down into functional **Segments** (allocating knowledge to different buckets like short/long term).
6. Finally, it provides the literal software **Implementation** (Databases).

### Why this matters

This agenda is a direct parallel to **Database Management System (DBMS)** design. The concepts of writing/reading data, creating associative relational links, pruning dead data (garbage collection), indexing by Time/Space, and partitioning storage are fundamental to computer science. The presenter is proving that biological memory and digital databases are conceptually identical.

### Interpretive note

- The typo *"Persistencing"* (persisting) is preserved from the original text.

---

# Slide 5: Section 1 Transition

- Header: **1 Task**
- Subtitle: **Persistencing and Recalling**

### Conceptual Explanation

This is a structural transition slide, opening the first section of the module's agenda. It establishes the two fundamental, binary tasks of any memory system: Persisting (writing data to storage) and Recalling (reading data from storage).

---

# Slide 6: Persisting a thought

- Header: **Persisting a thought**
- Core Visual: 
  - Divided into three horizontal layers: `virtual world` (top), `mental world` (middle), and `physcial world` (bottom). 
  - In the `mental world` (the domain of *thinking*), a thought exists as a **Mental Entity**.
  - To persist this thought, it must cross the boundary downward into the `physcial world` (the domain of *memory*), where it is stored as a **Physical Entity (Carrier)**.

### Conceptual Explanation

This slide illustrates the physics of "Writing" to memory, heavily relying on the Body-Mind Dualism established in the "Reality" module. 

A "thought" is purely mental. But mental entities are ephemeral; they vanish as soon as you stop thinking about them. If you want to save a thought, you must translate it into physical matter. You must write it down on paper, or your brain must literally restructure physical synapses and chemical states to hold the pattern. The memory itself is a *Physical Entity* (a carrier) that holds the shape of the mental thought. 

### Why this matters

For computer science, this is the distinction between **RAM (Mental World)** and a **Hard Drive (Physical World)**. When an AI is actively processing a prompt, the data is in volatile RAM (thinking). If the power is cut, the thought dies. To persist the data, the AI must execute a `write()` command to magnetically or electrically alter the physical state of a hard drive (the Physical Carrier).

### Interpretive note

- The typos *"Entiy"* (Entity) and *"physcial"* (physical) are preserved from the original text.

---

# Slide 7: Recalling a thought

- Header: **Recalling a thought**
- Core Visual:
  - The inverse of Slide 6. 
  - The solid block of data exists at the bottom in the `physcial world` as the **Physical Entity (Carrier)**.
  - An empty projection extends upward into the `mental world`. The mind reads the physical carrier to reconstruct the **Mental Entity (Thought)**.

### Conceptual Explanation

This slide illustrates the physics of "Reading" from memory. 

The mind cannot "think" using the physical carrier directly. It must scan the physical carrier (e.g., reading a notebook, or the brain firing impulses through a specific synaptic pathway) and project that physical pattern back up into the mental realm to recreate the original thought. 

### Why this matters

This confirms that memory retrieval is a reconstructive translation process. In computing, this is identical to a `read()` command. The CPU (the mind) cannot execute operations directly on the magnetic platters of a hard drive. It must read the physical magnetic states, translate them into binary, and load them back into the volatile RAM (mental world) to actually "think" about the data.

---

# Slide 8: Task — Primitive Concept Name and Name Association

- Header: **1. Task**
- Subtitle: **Primitive Concept Name and Name Association**
- Core Visual:
  - **Left**: An image of the physical Eiffel Tower (the `nominee`).
  - **Right**: Three different textual Primitive Concepts (`La tour Eiffel`, `Eiffelturm`, `Eiffel Tower`).
  - **Edges**: The arrows connecting the names to the physical entity are defined by their linguistic roles (`french name`, `german name`, `english name`).

### Conceptual Explanation

This slide merges the "Concept" module with the "Memory" module. It shows how the mind persists a simple associative edge.

The physical object (the Eiffel Tower) is the "nominee" (the thing being named). The mind does not store the physical tower. Instead, it stores a Primitive Concept (a text string like "Eiffel Tower"). It then stores an associative edge linking that string to the mental entity of the tower, categorized by a specific role ("english name"). 

### Why this matters

This is exactly how a **Key-Value Store** or a **Translation Dictionary** works in software. The AI stores the core Entity in memory. It then attaches multiple string properties to it (`{ "french_name": "La tour Eiffel", "german_name": "Eiffelturm" }`). When the AI needs to communicate about the entity to a German user, it queries the memory for the string associated with the `german_name` edge.

---

# Slide 9: Task — Persisting Information (Internalization)

- Header: **1. Task**
- Subtitle: **Persisting information**
- Core Visual:
  - Identical to Slide 8, but now the associative network (the edges mapping the physical tower to the text strings) is visually superimposed over a graphic of a **Brain** containing a complex neural network.

### Conceptual Explanation

This slide illustrates the internalization of the concept from Slide 8. The abstract linguistic mapping (assigning names to a physical object) does not exist in the air between two people; it must be mapped entirely inside the internal network of the Brain. The brain acts as the central router, taking the visual input of the tower and internally drawing the associative edges to the string variables.

### Why this matters

For AI, this proves that intelligence must have localized storage. A camera (sensor) can see the tower, but the camera isn't intelligent. The intelligence happens in the central processing unit (the Brain) where the raw visual data is cross-referenced against the internal Knowledge Graph to pull up the associated text strings.

---

# Slide 10: Task — Persisting Information (Dualism)

- Header: **1. Task**
- Subtitle: **Persisting information**
- Core Visual:
  - The slide is split horizontally into the `mental world` (top) and `physcial world` (bottom).
  - The brain and its associative network sit in the top right (mental world).
  - The actual, real-life Eiffel Tower sits in the bottom left (physical world).
  - A massive red arrow labeled **"physical representation"** points from the right side over to the physical tower on the left.

### Conceptual Explanation

This slide reinforces the Body-Mind Dualism applied to memory. The associative network inside the brain is completely isolated from the real world. The real Eiffel Tower is merely the "physical representation" that the mental network is trying to model. When the brain persists (saves) this information, it is saving a localized, mental model of reality, not reality itself. 

### Why this matters

This is the definition of a **Digital Twin** in software architecture. An AI system simulating a factory does not actually contain the factory. It contains a localized, persisted mental model (data structures) that *represents* the physical factory. If the physical factory changes, the AI's persisted memory is suddenly out of date until it observes the change and updates its internal edges.

### Interpretive note

- The typo *"physcial"* is preserved from the original text.

---

# Slide 11: Task — Recall Persisted Information

- Header: **1. Task**
- Subtitle: **Recall persisted information**
- Core Visual:
  - The `mental world` / `physcial world` split remains.
  - The associative network (the tower image, the edges, and the text names) has been pulled *out* of the mental brain and pushed down into the `physcial world` layer on the bottom right (the "memory" block).
  - Faint blue arrows point from that physical memory block *up* into the mental brain.

### Conceptual Explanation

This is the visual execution of the theory from Slide 7. 

To "Recall" information, the brain cannot just magically summon it from the ether. The data was persisted (written) into a physical medium (the synaptic layout of the biological brain, acting as the "memory" block). To remember the names of the Eiffel Tower, the active, conscious part of the brain must "read" the data stored in that physical memory block and project it back up into the active mental world. 

### Why this matters

In computer science, this perfectly illustrates the separation of **CPU/RAM** (Mental World) and **Storage/SSD** (Physical Memory). When the AI is turned off, its Knowledge Graph of the Eiffel Tower rests entirely in physical storage. When the AI boots up and needs to answer a question, it must `read()` from the SSD and load the graph into active RAM to recall the information.

---

# Slide 12: Section 2 Transition

- Header: **2 Remembering**
- Subtitle: **Associating**

### Conceptual Explanation

This is a structural transition slide, opening the second section of the module's agenda. Having defined the basic tasks of reading and writing data (Persistencing and Recalling), the presenter now moves to the mechanics of *how* the mind actually executes a recall: through "Associating."
